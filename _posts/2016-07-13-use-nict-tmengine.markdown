---
author: Akira.Popal
comments: true
date: 2016-07-13 04:36:38+00:00
layout: post
link: https://www.memsource.com/ja/blog/2016/07/13/use-nict-tmengine/
slug: use-nict-tmengine
title: 「みんなの自動翻訳」をMemsource Cloudで利用する
wordpress_id: 7892
categories:
- 機械翻訳
---

Memsourceには「Microsoft with Feedback」という機械翻訳エンジンがデフォルトで備わっており、ユーザーはMemsource Cloud上で自動翻訳結果を利用することが可能です。しかしこの他にもGoogleを初めとする多くの企業・団体が様々な自動翻訳エンジンを公開しており、Memsourceではそのような一般公開されている機械翻訳エンジンをAPIを通して簡単に利用することが可能です。
「みんなの自動翻訳＠TexTra®」はNICT(情報通信研究機構)が開発した自動翻訳サイトであり、特に特許分野で高い精度の多言語翻訳を行うことで知られていますが、その他の分野の翻訳においても評判の高い優秀なエンジンです。今回は「みんなの自動翻訳」をMemsource Cloudで使用する手順を解説いたします。
<!-- more -->


## 設定手順


１．
まずは「みんなの自動翻訳」のサイトでアカウントを開設します。
https://mt-auto-minhon-mlt.ucri.jgn-x.jp/にアクセスして「新規登録」から自分のアカウントを作成しましょう。
[![CreateAccount](/wp-content/uploads/2016/07/CreateAccount-1-300x129.png)](/wp-content/uploads/2016/07/CreateAccount-1.png)
2．
アカウントにログインしたら、画面下部「Web APIを使ってみよう！」の「GO!!!」をクリックし、次に出てくる画面で「自動翻訳リクエスト」の「一覧」をクリックします。
[![GoToAPI](/wp-content/uploads/2016/07/GoToAPI-1-300x168.png)](/wp-content/uploads/2016/07/GoToAPI-1.png)
3.
使用可能な翻訳エンジンの一覧が表示されます。ここでは例として「汎用【英語－日本語】」を選択します。
[![ENGtoJPN](/wp-content/uploads/2016/07/ENGtoJPN-1-300x158.png)](/wp-content/uploads/2016/07/ENGtoJPN-1.png)
4．
APIを利用するための情報が表示されますので、そのまま画面を残してMemsource Cloudの設定に移ります。
[![APIinfo](/wp-content/uploads/2016/07/APIinfo-1-300x225.png)](/wp-content/uploads/2016/07/APIinfo-1.png)
5．
Memsource Cloudの「セットアップ」→「機械翻訳エンジン」を開き、「作成」をクリックしたらプルダウンから「NICT」を選択します。
[![ChooseEngine](/wp-content/uploads/2016/07/ChooseEngine-1-300x138.png)](/wp-content/uploads/2016/07/ChooseEngine-1.png)
6．
下記画面にAPI情報を入力します。
[![EnterAPI](/wp-content/uploads/2016/07/EnterAPI-1-300x180.png)](/wp-content/uploads/2016/07/EnterAPI-1.png)
名称：任意の名前をつけてください
ユーザー名：「みんなの自動翻訳」にログインするユーザー名です。
エンジン：先ほどのAPI情報の画面の「リクエストURL」のうち、「https://mt-auto-minhon-mlt.ucri.jgn-x.jp/api/mt/」以下の部分をを入力します。今回の例でいうと「general_en_ja」となります。
キー：API Keyを入力します。
シークレット：API secretを入力します。
通常にチェックを入れると、この機械翻訳エンジンがデフォルトに設定されます。

7．
保存を押したら設定完了です。必要に応じてプロジェクトの「編集」から機械翻訳エンジンを変更しましょう。
[![ProjectSetting](/wp-content/uploads/2016/07/ProjectSetting-1-300x251.png)](/wp-content/uploads/2016/07/ProjectSetting-1.png)
設定手順は以上となります。「みんなの自動翻訳」のエンジンは一括翻訳には対応していませんが、エディタのCATパネルから各セグメント毎に自動翻訳の結果を利用できます。


## 注意事項


NICTが提供する「みんなの自動翻訳」エンジンはどなたでも無料で利用できますが、使用に際していくつかの注意点があります。まず用途が非商用に限られているということです。商用利用のためには別途NICTとの有償契約が必要となります。また、入力データはNICTサーバーに保存され、機械翻訳の技術向上に利用されるということにも留意しましょう。
詳しくは下記URLから利用規約をご確認下さい。
https://mt-auto-minhon-mlt.ucri.jgn-x.jp/content/policy/
