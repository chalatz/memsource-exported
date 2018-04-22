---
author: Akira.Popal
comments: true
date: 2016-12-18 13:42:58+00:00
layout: post
link: https://www.memsource.com/ja/blog/2016/12/18/enhancing-account-security-with-two-factor-authentication-jp/
slug: enhancing-account-security-with-two-factor-authentication-jp
title: 二段階認証を利用してアカウントのセキュリティを強化する
wordpress_id: 10341
categories:
- カテゴリーなし
- バージョンアップ
- 高度な機能
tags:
- セキュリティ
---



[![2-factor-authentication](http://www.memsource.com/wp-content/uploads/2016/11/2-factor-authentication.png)](http://www.memsource.com/wp-content/uploads/2016/11/2-factor-authentication.png)皆さまの機密情報である翻訳データをお預かりするMemsourceにとって、プライバシーとセキュリティの強化は最優先の課題です。安心して使えるツールであり続けるためにこれまで様々な安全対策に取り組んできましたが、先日のアップデートによりここに新しい機能が追加されました。それがMemsourceアカウントのセキュリティをさらに高めることができる二段階認証です。この記事ではその機能と使い方をご紹介します。<!-- more -->

二段階認証とは、アカウントにログインする際に通常のユーザー名とパスワードに加えて、もう一つ別の認証コードを必要とする仕組みです。万が一パスワードが漏洩した場合でもアカウントを安全に保てる機能であり、GoogleやAmazonなど様々なサービスで導入されています。

この二段階認証をMemsourceでもオプションとして利用できるようになりました。タイムベースワンタイムパスワード(TOTP)と呼ばれるテクノロジーを用いており、毎回のログイン時に事前に登録したスマートフォンなどのアプリで生成されるコードの入力が必要になります。コードの生成には、「Google Authenticator」や「Authy」などの任意の認証アプリをお使い頂けます。

この機能を設定すると、Memsourceクラウドだけでなく、デスクトップエディターを開いた際にもコードの入力が求められます(バージョン6.200.0以降)。

[ログインAPI](http://wiki.memsource.com/wiki/Authentication_API_v3)にもオプションのcodeパラメータが追加されています。

なお、紛失や故障などの原因で認証用のアプリを利用できなくなった際は、アカウントの管理者が二段階認証を無効にする必要がありますが、念のために複数のデバイスを登録しておくこともできます。


## 二段階認証の設定方法





 	
  1. Google Authenticatorもしくは同様の認証アプリをスマートフォンなどのデバイスにダウンロードしてください。

 	
  2. Memsourceの「セットアップ」の一番下にある「ユーザー設定」の「Two-factor Authentication」を開いてください。

 	
  3. 認証アプリでQRコードをスキャンしてください。QRコードの代わりに秘密鍵が表示される場合があります。その際はアプリに秘密鍵を手入力してください。

 	
  4. アプリが生成した数字のコードを「Code」欄に入力して「Verify」をクリックしてください。


以上の手順により、お使いのMemsourceアカウントがデバイスの認証アプリと接続されます。これ以降、ログインする度にアプリが自動生成するコードの入力が必要になります。アカウントのセキュリティを高める追加機能としてご活用ください。
本機能やその他Memsourceについてのご質問は[こちら](mailto:japan@memsource.com)までお気軽にお寄せください。


