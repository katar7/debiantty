# DebianTTY
DebianTTY is a live distribution of Debian GNU/Linux for professionals for manual installation using the Internet.<br>
The goal is to create a lightweight recovery and console installation tool for Debian.

## Where and to whom can this be useful?
* To automate the installation when setting up multiple computers at once.
* For users who do not like official Debian installers.
* For console lovers.
* For geeks.
* For learning.

## Basic system information
Based on Debian GNU/Linux 11 Bullseye<br>
There is only one user in the system designated for use.<br>
Login - **root**<br>
Password - **root**<br>

To get software from the Internet via apt, first run the `apt update` command. By default, proprietary software repositories (contrib and non-free) are disabled and no packages from these repositories are preinstalled.<br>

DebianTTY is intended for corporate (e.g. offices, factories, ATM, POS, etc.), educational (e.g. schools, universities, etc. ) and home use on x86-compatible processors and/or via virtualization on x86-incompatible processors and is only available for two architectures, i386 (a.k.a. x86/Intel32/IA-32) and amd64 (a.k.a. x86_64/x64/Intel64/EM64T). Two bootloaders are provided for both architectures, SYSLINUX for BIOS and GRUB for UEFI.

## RAM requirement<br>
Normal mode - 384 MB<br>
Copy-to-RAM - 1 GB<br>
You can run DebianTTY with less RAM, but apt will not work.
