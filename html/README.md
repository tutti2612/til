## メタデータ: <meta>要素

>注: 多くの <meta> 機能はもう使われていません。例えば、 keyword の <meta> 要素 (<meta name="keywords" content="fill, in, your, keywords, here">) — 検索エンジンが色々な検索用語と関連するページを決めるためのキーワードを与えると考えられています — は、スパマーが結果にバイアスをかける多数のキーワードを埋めるだけなので、検索エンジンから無視されます。

### メタデータの他の種類

>例えば、 Open Graph Data は Facebook が開発した、ウェブサイトに豊富なメタデータを与えるメタデータプロトコルです。 MDN Web Docs のソースコードでは、次のようなものがあります。

```html
<meta property="og:image" content="https://developer.cdn.mozilla.net/static/img/opengraph-logo.dc4e08e2f6af.png">
<meta property="og:description" content="The Mozilla Developer Network (MDN) provides
information about Open Web technologies including HTML, CSS, and APIs for both Web sites
and HTML5 Apps. It also documents Mozilla products, like Firefox OS.">
<meta property="og:title" content="Mozilla Developer Network">
```

>この効果として、 facebook で MDN Web Docs にリンクしたとき、リンクに画像と説明が表示されます。ユーザーにとってより便利になります。

>Twitter も同様のプロプラエタリなメタデータを持ちます。 URL が twitter.com で表示される時に同様な効果となります。例えば。

```html
<meta name="twitter:title" content="Mozilla Developer Network">

```

ref. https://developer.mozilla.org/ja/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML


## ダウンロードへのリンクは download 属性を使う

>ブラウザーで開くのではなくダウンロードするリソースにリンクしている場合は、download 属性を使用してデフォルトの保存ファイル名を指定できます。これは最新の Windows 版 Firefox へのダウンロードリンクの例です。

```html
<a href="https://download.mozilla.org/?product=firefox-latest-ssl&os=win64&lang=en-US"
   download="firefox-latest-64bit-installer.exe">
  Download Latest Firefox for Windows (64-bit) (English, US)
</a>
```

ref. https://developer.mozilla.org/ja/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks

## 高度な意味付け機能をマークアップするための、あまり知られていないHTML要素

https://developer.mozilla.org/ja/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting

## セマンティックタグを使用して文書を構造化する方法

https://developer.mozilla.org/ja/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure

## HTML バリデーション

https://validator.w3.org/
