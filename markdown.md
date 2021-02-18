# 見出し1 h1
## 見出し2 h2
### 見出し3 h3

**太字strong**

*斜字italic*

~~打ち消し線line-through~~

***
↑線を引くhr↓

---

改行brは↓  
文末にスペースを2つ入れる

p要素は改行だけの行↑を入れる

---
* 箇条書き1
* 箇条書き2
  * 箇条書き3
  * 箇条書き4
    * 箇条書き5
    * 箇条書き6
* 箇条書き7
    * 箇条書き8

1. 数字付き1
1. 数字付き2
1. 数字付き3

---
> 引用
>> 二重引用
>
> 二重引用の後は1行おかないと途切れる
>

---
整形済みブロックになる＆言語を指定すれば認識して色分けもしてくれる
【CSS】
```css
#body{
    font-size:1rem;
}
.test-class{
    color:#1b1b1b;
    background-color:#fff;
}
```
【html】
```html
<html>
<head>
<title>test-page</title>
</head>
<body>
<div class="test-class">
<p>test</p>
</div>
</body>
</html>
```
【C言語】
```C
// コメント
#include<stdio.h>
int main(){
    printf("Hello World")
}
```


---

VScodeでリアルタイムプレビューを表示させる（サイドバー）  
Windows：［Ctrl］＋［K］→［V］  
macOS：［Command］＋［K］→［V］
（タブとしてプレビューを表示させるにはCtrl/Cmd+Shift+Vです）

---
リンクの書き方  
```[テキスト](URL)```

---

【拡張機能：HTMLやPDFに変換】  
markdown-pdf  
markdownで書いたファイル（プレビュー側）をpdfやhtmlで出力できる。最高。

【拡張機能：画像を貼り付ける】 
Paste image
クリップボードにコピーした画像を貼り付けることができる  
Windows：［Ctrl］＋［Alt］+［V］  
macOS：［Command］＋［Option］+［V］
貼り付けられた画像
![](![](2019-02-12-22-09-20.png)
は作成した.mdファイルと同じディレクトリに格納される