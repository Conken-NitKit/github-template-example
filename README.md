# GitHubのPRテンプレートについて

GitHubでPR作成時のDescriptionエリアに初期表示させるテンプレートのことです。<br>
初期表示される内容は **`.github/PULL_REQUEST_TEMPLATE.md`** 内に記載した内容は反映されます。

▼ デフォルトで以下のような入力がされます。

<img src="https://user-images.githubusercontent.com/41711771/154782746-4ddb14ff-9631-490b-8e53-2a74a6a6d5d0.gif" width="960">


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

このテンプレートは盲信しすぎず、不要だと思った項目は各プロジェクトにて削除してください。<br>

> ディレクトリ名/ファイル名は必ず `.github/PULL_REQUEST_TEMPLATE.md` である必要があります。
> `.github/PULL_REQUEST_TEMPLATE_XXX.md` とした場合はうまく動作しないので、必ず `_XXX` の部分は削除するようにしてください。

- [🔰 マークシンプルver](https://github.com/Conken-NitKit/github-template-example/blob/main/.github/PULL_REQUEST_TEMPLATE.md)
- [<img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" width="16"> React ver](https://github.com/Conken-NitKit/github-template-example/blob/main/.github/PULL_REQUEST_TEMPLATE_REACT.md)
- [<img src="https://unity.com/themes/contrib/unity_base/images/favicons/favicon.ico" width="16"> Unity ver](https://github.com/Conken-NitKit/github-template-example/blob/main/.github/PULL_REQUEST_TEMPLATE_UNITY.md)
