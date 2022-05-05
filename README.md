# Switch-UPGRADE
Ansible script to upgrade cisco 3650 and 3850 switches

The script upgrades IOS-XE (3650/3850) devices in install mode and convert devices in bundle mode to install mode before upgrading.

Vars in IOSXE-UP.yml:
  - size (size of the new file in bytes)
  - image_new (new image file name)

The new software image is uploaded from a FTP server to the switch. FTP server is hardcoded in the install/tasks/main.yml file
