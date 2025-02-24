# ITCチャンネル] gitチュートリアル用リポジトリ

## 当リポジトリを通じて理解いいただけるGit用語例
- リポジトリ
- ブランチ
- コミット
- マージ
- リベース
- リセット

## 始め方
プロジェクトフォルダを作成したいフォルダへ移動し、以下のコマンドを入力。
```bash
git clone https://github.com/Yulikepython/git-tutorial-by-itc.git
```

プロジェクトフォルダに移動。
```bash
cd git-tutorial-by-itc
```

フォルダ内を見てみよう。
```bash
ls
```

現在のブランチを確認。
```bash
git branch
```
mainと表示されていればOKです。

ほかのブランチの情報を取得します。
```bash
git fetch --all
```

リモートのブランチとローカルのブランチを同期します。
以下のコマンドについては動画にて解説します。
```bash
git checkout -b develop origin/develop
git checkout -b feature/demo-branch-01 origin/feature/demo-branch-01
```