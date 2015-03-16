# README
## Overview
Many roles have a type switch which is used to distinguish between server and client configurations.
- ''hub'': Configure server
- ''access'': Configure client machine for accessing servers

### Roles
#### apps
- type
  - minimal (bare minimum apps)
  - basic
  - full (all apps)
- vars
  - Install command-line apps -->> `cmd: yes`
  - Install gui apps -->> `gui: no`

#### common
- vars
  - hostname [string]: set hostname of machine. Skip if not provided.
  - fish_users [array]: set the shell of all users to fish shell. default = [vagrant]
  - motd_disable_users [array]: disable the motd login banner after ssh. default = [vagrant]

## ToDo's
* Laptop
    * Install dropbox
    * VNC with GUI
* Host box
    * VirtualBox (+ phpVirtualBox)
    * lvm configurations
    * snapraid
    * mhddfs
* Remote boxes
    * Download Manger
    * Subsonic
    * Plex
    * Backup DLNA
    * Monitoring
    * OpenVPN configuration
* All boxes
    * Command line emails
    * BTSync
