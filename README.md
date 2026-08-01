# 退職給付金シミュレーター

4つの質問で、退職後に確認できる公的給付の目安をチェックできるシミュレーターです。

公開URL: https://ponchiinu44-del.github.io/taishoku-kyufukin/

## ファイル構成

| ファイル | 内容 |
| --- | --- |
| `index.html` | 診断ページ（結果画面のCTAから公式LINEへ遷移） |
| `tokushoho.html` | 特定商取引法に基づく表記 |
| `privacy.html` | プライバシーポリシー |

## 公式LINEのリンクを変更するには

`index.html` の `LINE_URL` を書き換えてください。

```js
const LINE_URL = "https://s.lmes.jp/landing-qr/...";
```

結果画面のCTAボタン（`id="line-cta"`）の遷移先は、この1箇所だけで決まります。
空文字にするとボタンは無効化されます。
