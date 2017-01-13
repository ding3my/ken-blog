#o
参考#a
#i
google rpmbuild
[1]https://wiki.centos.org/zh/HowTos/SetupRpmBuildEnvironment
rpm-build
google rpm spec format
https://fedoraproject.org/wiki/How_to_create_an_RPM_package
#a
```
sudo dnf install rpm-build
mkdir shell-script-0.1
echo 'echo hi' > shell-script-0.1/shell-script.sh
tar -czvf shell-script-0.1.tar.gz shell-script-0.1/
mv shell-script-0.1.tar.gz ~/rpmbuild/SOURCES/
echo 'Summary: The do it all script. (Enterprise quality)
Name: shell-script
Version: 0.1
Release: 1
URL:     http://meinit.nl
License: GPL
Group: Applications/Internet
BuildRoot: %{_tmppath}/%{name}-root
Requires: bash
Source0: shell-script-%{version}.tar.gz
BuildArch: noarch
%description
A shell script.
%prep
%setup
%build
%install
rm -rf ${RPM_BUILD_ROOT}
mkdir -p ${RPM_BUILD_ROOT}/usr/bin
install -m 755 shell-script.sh ${RPM_BUILD_ROOT}%{_bindir}
%clean
rm -rf ${RPM_BUILD_ROOT}
%files
%defattr(-,root,root)
%attr(755,root,root) %{_bindir}/shell-script.sh
%changelog
* Tue Jan 12 2010 Robert de Bock <robert@meinit.nl>
- Uberscript!' > hi.spec
rpmbuild -bb hi.spec
sudo rpm -ivh ~/rpmbuild/RPMS/noarch/shell-script-0.1-1.noarch.rpm
shell-script.sh
sudo rpm -e shell-script
rm shell-script-0.1 -rf
```
#sum
- 参考中的shell文件夹需要命名为shell-script-0.1，shell文件需要命名为shell-script.sh
- 参考中的spec文件任意命名
1. https://wiki.centos.org/zh/HowTos/SetupRpmBuildEnvironment
