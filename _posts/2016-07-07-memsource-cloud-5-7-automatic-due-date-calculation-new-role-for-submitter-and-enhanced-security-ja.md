---
id: 7782
title: 'Memsource Cloud 5.7 : 納期の自動設定機能とセキュリティの強化'
date: 2016-07-07T00:25:57+00:00
author: admin
layout: post
guid: http://blog.memsource.com/ja/?p=7782
permalink: /2016/07/07/memsource-cloud-5-7-automatic-due-date-calculation-new-role-for-submitter-and-enhanced-security-ja/
slide_template:
  - ""
  - ""
  - ""
  - ""
categories:
  - バージョンアップ
---
2016年6月26日にMemsource Cloud 5.7が公開されました。今回のアップデートによっていくつかのバグの修正とパフォーマンスの改善に加え新たに便利な機能が追加されています。その一つが納期を自動設定する機能です。ユーザーが設定したアルゴリズムに応じて、オートメーションウィジェット上の納期が自動的に算出されます。また、OAuth 2.0プロトコルが実装され、Memsourceの[API](http://wiki.memsource.com/wiki/Memsource_API)をよりセキュアにご利用いただけるようになりました。

<!--more-->

### 納期の自動設定機能

オートメーションウィジェット上で納期を設定する時、これまではカレンダーを表示して任意の日付と時間を選択していました。この従来の方法に加え、セットアップの「納期スキーム」にあらかじめ入力した作業量とルールに応じて自動的に納期を算出することが可能になりました。「納期スキーム」で作成したルールを、セットアップの「提供するサービス」に設定することで、翻訳用ファイルをアップロードした際にファイルの分量に応じた納品日時が表示されるようになります。

  * 納期スキームの設定画面

[<img class="aligncenter wp-image-7705" src="/wp-content/uploads/2016/06/Image1.png" alt="Image1" width="537" height="397" data-id="7705" />](/wp-content/uploads/2016/06/Image1.png)

  * 自動的に算出された納品日時が下記のように表示されます。

[<img class="aligncenter wp-image-7706" src="/wp-content/uploads/2016/06/Image2-1024x488.png" alt="Image2" width="527" height="251" data-id="7706" />](/wp-content/uploads/2016/06/Image2.png)

&nbsp;

納期スキームが未設定の場合は今まで通りカレンダーが表示されます。
  
&nbsp;

### 

### OAuth 2.0をサポート

OAuthとは、アプリ間の認証のための標準的なプロトコルであり、オンラインサービスを提供する大手企業(Google、Facebook、Twitter、アマゾン、マイクロソフト、ヤフー、Salesforce、Paypal等)がこぞって採用していることからもその信頼性の高さが伺えます。この度MemsourceにそのOAuth 2.0が実装されたことにより、サードパーティアプリケーションとの接続がこれまでになく容易になりました。OAuthプロトコルによる認証を用いると、他のアプリケーションにMemsourceアカウントのパスワードを知らせる必要がなく、各アプリケーション毎にアクセス権の付与と管理が可能です。これはセキュリティの観点上とても重要なことです。
  
&nbsp;

### API

今回のアップデートではAPIにもいくつかの変更が加えられました。

  * ページングセクションを含む応答を行う新API要求「api/v8/job/listByProject」
  * ジョブの新規作成のためのAPIが[前回のアップデート](/ja/memsource-cloud-5-6-new-definition-of-tm-context-and-business-units_jp/)で導入されたコンテキストタイプの最適化をサポート
  * セキュリティの強化を目的として、新しいパラメーター「uid(値の例：1O1hLcK8w1cXL8lMhzYz42)」 をJSONレスポンスに導入
  
    (これまでのフォーマットも引き続き有効であり、API要求ではどちらも使用可能ですが、新しいフォーマットの利用を推奨します)

&nbsp;

### その他

クルド語に新たに三つの地域毎の設定が加わりました。

  * クルド語(中央)
  * クルド語(北部)
  * クルド語(南部)