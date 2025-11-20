# Hack And Slash Modoki (HASMO)

このmodpackの開発には[pakku](https://github.com/juraj-hrivnak/Pakku)を利用しています。

## 開発について

### 推奨される環境

- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Lazygit](https://github.com/jesseduffield/lazygit)

### 開発環境のセットアップ

```sh
git clone https://github.com/Laundry-Dev/HASMO  # ソースコードのダウンロード
pakku fetch                                     # modのダウンロード
```

`pakku fetch`実行時にCurseforge APIが必要になりますが、
`pakku`側から適宜指示が出るのでそれに従ってください。

### 開発環境の更新

アップストリームの変更に合わせるには

```sh
git fetch
```

を実行してください。
