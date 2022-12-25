# Unity 7 for Univalent GNU/Linux

ありがとう、Unityメンテナーチーム。

Unityは「univalent-stable」リポジトリで利用可能です。

Unityを導入する:

```
   sudo pacman -Syyuu && sudo pacman -S unity-meta"
```

現在のディスプレイマネージャーを無効化した後、既定のディスプレイマネージャーをLightDMに切り替える。

```
   sudo systemctl enable --now lightdm
```

やったね！これでセッション一覧にUnityが表示され、ログイン可能になります。

