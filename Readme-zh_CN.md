# Tampermonkey-i18n 项目

本库包含 Tampermonkey 的本地化文件。

## 获取

你可以从 <http://tampermonkey.net> 获取 TramperMonkey

## 贡献

若你想做出贡献，这个[脚本](https://gist.github.com/derjanb/5592ff3b7cdc4feabba5/raw/tampermonkey_translation_support.user.js)可以帮助你:

安装脚本后，你将会在每个 message.json 文件的编辑界面中的按钮栏上看到一个“Adjust to English translation”的按钮。
点击这个按钮后，页面将会被加上了所有缺少翻译的当前本地化文件所替换。 缺少的翻译将会用尖括号包住，类似这样:

```json
 "Dont_ask_again": {
     "message": ">>>Don't ask again<<<"
  },
```

在翻译缺少的内容后，你可以创建一个 pull request 或只是给[作者](mailto:kontakt@tampermonkey.net)发送翻译.
