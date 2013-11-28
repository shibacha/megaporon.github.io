---
layout: post
title:  "todoアプリをつくってみる -jQuery導入編-"
date:   2013-11-24 00:43:10
categories: todoApp
---


jsの勉強にtodoアプリを作っているのですが、そこでつまづいたりしたときのメモ。  
  
そもそもJavaScriptっていまいちよく分からない、なのでjQueryももっとよく分からない、な状態でした。  
なんとか動くものを作れているので色々メモしときます。


【作成するtodoアプリ】  
・todoを記入できる  
・終わったものにチェックをつけれる  
・終わったtodoを消すことができる  
・この３つをローカルストレージに保存する  
  
  
  
この４つの機能があるtodoアプリをHTML5とJavaScriot（jQuery）で作っていきます。 
todoアプリと言っても、chromeで動くwebページです。
    
  

<br>
まず**jQuery**を使う準備。    

【使い方】  
（１）jQueryのHPからダウンロードする。  
![](images/1124/01.png)  
右にある「Download jQuery」のボタンからダウンロードページにいきます。  
<br>
<br>
![](images/1124/02.png)   
*jQuery 1.x*と*jQuery2.x*があります。  
違いは**対応しているブラウザ**です。  
jQuery2.xはIE8以下はサポートされていないバージョンで、古いブラウザにも対応させたい場合はjQuery 1.xを使う必要があります。    
  
  
<br>
![](images/1124/03.png)   
今回はjQuery2.xを使うので、*Download the compressed, production jQuery 2.0.3*を使います。
  
コードいっぱいの画面が出てきます。  
![](images/1124/04.png)  
[cmd] + [s]で*jquery-2.0.3.min.js*を保存します。  
これでjQueryの準備はOKです。


<br>
（２）jsフォルダに入れ、htmlにパスを記述する。  
![](images/1124/05.png)  
パスさえ合っていればどこでも大丈夫です。　　

![](images/1124/06.png)  

これでjQueryを使う準備はできました。  
早速todoアプリを作っていきます。  
