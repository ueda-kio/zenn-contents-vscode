# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

## cli

### 新規記事作成
```shell
npx zenn new:article

# 以下でも可
npm start
```

### 画像貼り付けコマンド
```
ctrl + opt + v
```
拡張機能の設定からコマンドは変更可能。

![](/images/README/ss.png)

## zenn マークダウン記法

[参考記事 - zenn](https://zenn.dev/zenn/articles/markdown-guide)

### 画像
```
# サイズ指定
![altテキスト](https://画像のURL =250x)

# キャプション指定
![](https://画像のURL)
*キャプション*
```

### メッセージ
```
:::message
メッセージをここに
:::

:::message alert
警告メッセージをここに
:::
```

### アコーディオン
```
:::details タイトル
表示したい内容
:::
```

### CodePen
```
@[codepen](ページのURL)
```

