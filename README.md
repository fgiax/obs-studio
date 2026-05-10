# Obs-studio is blowing my mind

0. Install from flathub for User

```bash
# ...
```

0. Configure Wayland(Sway) for

```bash
echo "<<<EOF >> ~/.config/sway/config
exec_always dbus-update-activation-environment --systemd WAYLAND_DISPLAY XDG_CURRENT_DESKTOP=sway
exec_always systemctl --user import-environment WAYLAND_DISPLAY XDG_CURRENT_DESKTOP
EOF"
```

0. Sound
