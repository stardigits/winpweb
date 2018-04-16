# Winpweb
Windows portable web developer tools
PHP, Javascript (Nodejs), Python (Winpython), Perl (Strawberryperl), Ruby
MariaDB, MongoDB, SQLite, Redis, Memcached

## Features
* Portable
* Semi-Sandbox

### Winpweb-1.0.10 ###
Release date: 2018-04-16

*Languange*:
* PHP, [PHP (7.2.4)](https://windows.php.net/index.php)
  * PHP-NTS-X64-7.2.4 (For IIS): <https://windows.php.net/downloads/releases/php-7.2.4-nts-Win32-VC15-x64.zip>
  * PHP-NTS-X86-7.2.4 (For IIS): <https://windows.php.net/downloads/releases/php-7.2.4-nts-Win32-VC15-x86.zip>
  * PHP-X64-7.2.4: <https://windows.php.net/downloads/releases/php-7.2.4-Win32-VC15-x64.zip>
  * PHP-X86-7.2.4: <https://windows.php.net/downloads/releases/php-7.2.4-Win32-VC15-x86.zip>
* Javascript, [Nodejs (8.11.1)](https://nodejs.org/en/)
  * Nodejs 8.11.1 (x64): <https://nodejs.org/dist/v8.11.1/node-v8.11.1-win-x64.zip>
  * Nodejs 8.11.1 (x86): <https://nodejs.org/dist/v8.11.1/node-v8.11.1-win-x86.zip>
* Python, [Winpython (3.6.5)](http://winpython.github.io/)
  * Winpython 3.6.5 (x64): <https://sourceforge.net/projects/winpython/files/WinPython_3.6/3.6.5.0/WinPython64-3.6.5.0Qt5.exe/download>
  * Winpython 3.6.5 (x86): <https://sourceforge.net/projects/winpython/files/WinPython_3.6/3.6.5.0/WinPython32-3.6.5.0Qt5.exe/download>
* Perl, [Strawberryperl (5.26.1.1)](http://strawberryperl.com/)
  * Strawberryperl 5.26.1.1 (x64): <http://strawberryperl.com/download/5.26.1.1/strawberry-perl-5.26.1.1-64bit-portable.zip>
  * Strawberryperl 5.26.1.1 (x86): <http://strawberryperl.com/download/5.26.1.1/strawberry-perl-5.26.1.1-32bit-portable.zip>
* Ruby, [Ruby (2.5.1.1)](https://www.ruby-lang.org/en/)
  * Ruby 2.5.1.1 (x64): <https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.5.1-1/rubyinstaller-2.5.1-1-x64.7z>
  * Ruby 2.5.1.1 (x86): <https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.5.1-1/rubyinstaller-2.5.1-1-x86.7z>

*Database*:
* [MariaDB (10.2.14)](https://mariadb.org/)
  * MariaDB 10.2.14 (x64): <https://downloads.mariadb.org/interstitial/mariadb-10.2.14/winx64-packages/mariadb-10.2.14-winx64.zip/from/http%3A//mariadb.biz.net.id/>
  * MariaDB 10.2.14 (x86): <https://downloads.mariadb.org/interstitial/mariadb-10.2.14/win32-packages/mariadb-10.2.14-win32.zip/from/http%3A//mariadb.biz.net.id/>
* PostgreSQL <>
* [SQLite (3230100)](https://sqlite.org/index.html) <https://sqlite.org/2018/sqlite-tools-win32-x86-3230100.zip>
* [MongoDB ()](https://www.mongodb.com/) <>

*Web Server*:
* Apache HTTPD (2.4.3.3)
  * Apachelounge 2.4.3.3 (x64): <http://www.apachelounge.com/download/VC15/binaries/httpd-2.4.33-win64-VC15.zip>
  * Apachelounge 2.4.3.3 (x86): <http://www.apachelounge.com/download/VC15/binaries/httpd-2.4.33-Win32-VC15.zip>
* Nginx

*Tools*:
* GIT (2.16.2)
  * GIT 2.16.2 (x64): <https://github.com/git-for-windows/git/releases/download/v2.16.2.windows.1/PortableGit-2.16.2-64-bit.7z.exe>
  * GIT 2.16.2 (x86): <https://github.com/git-for-windows/git/releases/download/v2.16.2.windows.1/PortableGit-2.16.2-32-bit.7z.exe>

## How to build the portable ##
*Note: Some software required Microsoft C++ Redistribution to be installed!*
- Download

### Winpweb Directory Structure ###
```
bin       Binary files folder
etc       Configuration files folder
data      Data files folder (for database)
project   Script/Program folder
log       Logging files folder
tmp       Temporary files folder
```
