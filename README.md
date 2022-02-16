# GitHubのPRテンプレートについて

GitHubでPR作成時のDescriptionエリアに初期表示させるテンプレートのことです。<br>
初期表示される内容は **`.github/PULL_REQUEST_TEMPLATE.md`** 内に記載した内容は反映されます。

## なぜPRのDescriptionを書くのか

- 何をしたいPRなのかをレビュワーに伝えれるようにする。。
- 未来の誰かがPRを見返す時に当時の状況がわかるようにする。
- 自分でチェックできる項目をしっかりと確認することを強制する。

## ファイルの配置場所
**`リポジトリ直下`** もしくは **`.githubフォルダー`** 内に **`PULL_REQUEST_TEMPLATE.md`** がついたファイルを配置することで、PRを作成した際に、自動でテキストが挿入されます.

```
.
├- .github
|    |
|    └- PULL_REQUEST_TEMPLATE.md 
|
:
```

## 利用してほしいPRテンプレート

このテンプレートは盲信しすぎず、不要だと思った項目は各プロジェクトにて削除してください。

- [🔰 マークシンプルver](https://github.com/Conken-NitKit/github-template-example/blob/main/.github/PULL_REQUEST_TEMPLATE.md)
- [<img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" width="16"> React ver](https://github.com/Conken-NitKit/github-template-example/blob/main/.github/PULL_REQUEST_TEMPLATE_REACT.md)
