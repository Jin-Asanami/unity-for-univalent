# Unity 7 for Univalent GNU/Linux

ありがとう、Unityメンテナーチーム。

以下の行を/etc/pacman.conf[core]の前に追記する。

```
   [unity-stable]
   Include = /etc/pacman.d/univalent-mirrorlist
```


Unityを導入する。

```
   sudo pacman -Syyuu && sudo pacman -S unity-meta"
```

現在のディスプレイマネージャーを無効化した後、既定のディスプレイマネージャーをLightDMに切り替える。

```
   sudo systemctl enable --now lightdm
```

やったね！これでセッション一覧にUnityが表示され、ログイン可能になります。

