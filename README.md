# sampleGit

## ファイル更新までの基本手順
```
git status

git add [ファイル名] //追加

git commit -a -m "任意のコメント"  //コミット (-aオプションは変更を自動検出してくれる)

git push origin master  //masterを更新
```

## git addの使用例
```
git add . //すべてのファイル・ディレクトリ

git add *.css //すべてのCSSファイル

git add -n //追加されるファイルを調べる

git add -u //変更されたファイルを追加する

git rm --cached //addしてしまったファイルを除外
```

## git commitの使用例
```
git commit -a //変更のあったファイルすべて

git commit --amend //直前のコミットを取り消す

git commit -v //変更点を表示してコミット
```

## 参考
[https://qiita.com/konweb/items/621722f67fdd8f86a017](https://qiita.com/konweb/items/621722f67fdd8f86a017)
