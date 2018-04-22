---
author: Katie
comments: true
date: 2017-12-27 09:56:09+00:00
layout: post
link: https://www.memsource.com/ja/blog/2017/12/27/single-sign-on-in-memsource-cloud/
slug: single-sign-on-in-memsource-cloud
title: シングルサインオンでアカウント管理をよりセキュアに
wordpress_id: 20350
categories:
- カテゴリーなし
- 新機能
- 高度な機能
tags:
- Memsource クラウド
- 管理者アカウント
---



[![シングルサインオンに対応](https://www.memsource.com/wp-content/uploads/2017/12/Blog-post_-single-sign-on-1-300x169.png)](https://www.memsource.com/wp-content/uploads/2017/12/Blog-post_-single-sign-on-1.png)

クラウドサービスが当たり前のものとして普及している現在では、日々の業務を行うためにさまざまなオンラインサービスが利用されています。

こうした企業にとって、複数のサービスを単一のログインシステムで利用する「シングルサインオン(Single Sign-on または SSO)」は、従業員の利便性を向上するだけでなく、セキュリティの観点からも大変のぞましいことです。

複数のアカウントの管理に頭を悩ますユーザー様に、朗報をお届けします。先日のアップデートにより、Memsourceは[OneLogin](https://www.onelogin.com/)のサービスを介したSSOをサポートするようになりました。対象エディション(アルティメット)の管理者は、この新機能によりMemsource クラウドのユーザーをより簡単に、そしてセキュアに管理できるようになります。

<!-- more -->


### SSOって？


シングルサインオンと一口にいってもいくつかの方式がありますが、この度Memsourceがサポートするのはもっとも一般的な「フェデレーション方式」とよばれるものです。

これはアイデンティティプロバイダー(IdP)にログインするだけで、そこを経由してIdPと連携する種々のアプリケーションに自動的にログインできる仕組みです。今回のSSO対応により、OneLoginにログインすればMemsource上でのユーザー名・パスワードの入力の手間を省いてMemsource クラウドを利用できるようになります。


### SSOの利点は？





 	
  * **セキュリティの向上：**
多くの企業では、実に多様なアプリケーションを業務で使用しています。アプリケーションごとに異なるIDやパスワードを使用している状態では、それらすべてを安全に管理することは難しく、企業のネットワークやデータが危険にさらされます。SSOを利用して従業員が利用する認証情報を減らすことで、より厳格なパスワードポリシーのもとでの運用が可能になります。逆にいえば、1つのIDとパスワードが漏洩するだけで複数のアカウントが危険にさらされるという事態にもつながりかねませんが、これを防ぐために[2段階認証](https://www.memsource.com/ja/blog/2016/12/18/enhancing-account-security-with-two-factor-authentication-jp/)などの補強対策を併用することで、アカウントのセキュリティは劇的に向上します。

 	
  * **ユーザー管理の手間を削減：**
管理者にとっては、会社で利用するさまざまなアプリケーションへのアクセスを一カ所で管理できるようになります。各ユーザーのMemsourceへのアクセス権は、Memsource上ではなくSSOのシステム上で管理できるようになります。

 	
  * **利便性の向上：**
複数のIDとパスワードを管理するのは、ユーザーにとっても負担です。SSOによって、管理すべき認証情報を減らすことで、「パスワードをリセット」という不要な作業に手間をとられることもなくなります。




### MemsourceでSSOを設定するには？


管理者アカウントからMemsourceのSSO機能を設定するのは難しい作業ではありません。構成はMemsourceアカウントの「設定」から行います。詳しい手順については[こちら(英文)](https://wiki.memsource.com/wiki/Memsource_Cloud_User_Manual#Single_Sign-On)をご参照ください。

今回のアップデートにより、SAML 2.0に対応するアイデンティティプロバイダーのSSOサービスをMemsourceで利用できるようになっていますが、現時点でフルサポートしているのはOneLoginのみです。OneLoginの設定に関しての詳細は[OneLoginのこちらのページ(英文)](https://support.onelogin.com/hc/en-us/articles/115003638343-Configuring-SSO-for-SAML-Enabled-Apps)をご覧ください。

＊SSO機能の対象エディションは「アルティメット」と「Bizアルティメット」です。また、SSOの設定を行うには管理者アカウントでログインしている必要があります。

--- 

今回はセキュリティを大幅に向上させる新機能のご紹介でした。こちらの内容についてご不明な点は、japan@memsource.comまでお問い合わせください。


