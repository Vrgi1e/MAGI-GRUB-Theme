## CRT-Amber GRUB Theme

Fork of the Generic Amber CRT Terminal theme for use with GRUB. Created using Shvchk's Fallout theme as a base.  

---

### Installation

1. Copy entire folder to your /boot/grub/themes directory.  
2. Edit the /etc/default/grub file with Root permissions and change the #GRUB_THEME= line to GRUB_THEME=/boot/grub/themes/MAGI-GRUB-Theme/theme.txt
3. Run the command: `sudo update-grub`
4. Reboot

If icons do not show beside their correct options, you need to edit your /etc/grub.d files to include the --class entry for each distro. It may be easier just to disable each one and create your own layout in the 40_custom file instead.
