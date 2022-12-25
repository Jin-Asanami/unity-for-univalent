# Unity 7 for Univalent GNU/Linux

Thanks, Unity Maintainers Team.

Unity is available in the "univalent-stable" repository.

Install Unity:

```
   sudo pacman -Syyuu && sudo pacman -S unity-meta"
```

Switch to LightDM as the default display manager after disabling the current display manager:

```
   sudo systemctl enable --now lightdm
```

Voila! You should now see Unity in the session list, and be able to log into it.

