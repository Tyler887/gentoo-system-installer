# System Installer

The System Installer installs a Gentoo system without requiring copypasting several
commands to do the install. You also get:

* [GNU GRUB](https://www.gnu.org/software/grub/manual/grub/html_node/Overview.html#Overview) bootloader
* Portage package manager
* Several stuff from `@world`

The checksum gets verified, so you don't get any security issues.

## Usage

Use `bash` to execute the installer:
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Tyler887/gentoo-system-installer/HEAD/gsi)
```
