# cal-linux

an arch based linux distro focused on customization and pentesting

## Login

the credentials for the live iso are:

- username: `cal`
- password: `live`

## TODO

- [x] enable lightdm service
- [x] add powerline config.
  - [x] skell
  - [x] root
- [x] add live user acount and passwd
- [ ] add astronvim install
- [ ] add bspwm configs
- [ ] add hyprland configs
- [ ] add gitlab CI job to do the following on the first of every month:
  - [ ] automatically update git repos in `/root` and `/etc/skel` (astronvim, bspwm configs, hyprland configs, etc).
  - [ ] delete the coresponding .git folders.
  - [ ] commit updates.
  - [ ] make a new ISO. (and add release for it.)
