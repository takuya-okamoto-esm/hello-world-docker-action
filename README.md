# Hello world Docker アクション

このアクションは、"Hello World" または "Hello" と相手の名前をログに出力します。

## Inputs

### `who-to-greet`

**必須** 挨拶する相手の名前。 デフォルトは `"World"`。

## 出力

### `time`

挨拶した時間。

## 使用例

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'