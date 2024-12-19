# tampermonkey-i18n

このリポジトリには、Tampermonkey のロケールファイルが含まれています。

## 入手方法

Tampermonkey は以下から入手できます: [http://tampermonkey.net](http://tampermonkey.net)

## 貢献方法

貢献したい場合は、この[ユーザースクリプト](https://gist.github.com/derjanb/5592ff3b7cdc4feabba5/raw/tampermonkey_translation_support.user.js)が役立つかもしれません。

スクリプトをインストールした後、各 `message.json` ファイルのボタンバーに <kbd>Adjust to English translation</kbd> ボタンが表示されます。このボタンをクリックすると、現在のロケールファイルに加え、欠落している翻訳が含まれたページが表示されます。欠落している翻訳は次のように山括弧で囲まれます:

```json
  "Dont_ask_again": {
     "message": ">>>Don't ask again<<<"
  },
```

不足している内容を翻訳した後、プルリクエストを作成するか、翻訳を kontakt@tampermonkey.net に送ることで貢献できます。
