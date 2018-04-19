---
id: 10341
title: 二段階認証を利用してアカウントのセキュリティを強化する
date: 2016-12-18T14:42:58+00:00
author: admin
layout: post
guid: http://memsource.elcaptain.cz/ja/?p=10341
permalink: /2016/12/18/enhancing-account-security-with-two-factor-authentication-jp/
slide_template:
  - ""
  - ""
  - ""
  - ""
categories:
  - カテゴリーなし
  - バージョンアップ
  - 高度な機能
tags:
  - セキュリティ
---
<div style="font-family: 'メイリオ', Meiryo, 'ヒラギノ角ゴ Pro W3';">
  <p>
    <a href="http://www.memsource.com/wp-content/uploads/2016/11/2-factor-authentication.png"><img class="alignnone size-full wp-image-9972" src="http://www.memsource.com/wp-content/uploads/2016/11/2-factor-authentication.png" alt="2-factor-authentication" width="1547" height="618" data-id="9972" /></a>皆さまの機密情報である翻訳データをお預かりするMemsourceにとって、プライバシーとセキュリティの強化は最優先の課題です。安心して使えるツールであり続けるためにこれまで様々な安全対策に取り組んできましたが、先日のアップデートによりここに新しい機能が追加されました。それがMemsourceアカウントのセキュリティをさらに高めることができる二段階認証です。この記事ではその機能と使い方をご紹介します。<!--more-->
  </p>
  
  <p>
    二段階認証とは、アカウントにログインする際に通常のユーザー名とパスワードに加えて、もう一つ別の認証コードを必要とする仕組みです。万が一パスワードが漏洩した場合でもアカウントを安全に保てる機能であり、GoogleやAmazonなど様々なサービスで導入されています。
  </p>
  
  <p>
    この二段階認証をMemsourceでもオプションとして利用できるようになりました。タイムベースワンタイムパスワード(TOTP)と呼ばれるテクノロジーを用いており、毎回のログイン時に事前に登録したスマートフォンなどのアプリで生成されるコードの入力が必要になります。コードの生成には、「Google Authenticator」や「Authy」などの任意の認証アプリをお使い頂けます。
  </p>
  
  <p>
    この機能を設定すると、Memsourceクラウドだけでなく、デスクトップエディターを開いた際にもコードの入力が求められます(バージョン6.200.0以降)。
  </p>
  
  <p>
    <a href="http://wiki.memsource.com/wiki/Authentication_API_v3" target="_blank">ログインAPI</a>にもオプションのcodeパラメータが追加されています。
  </p>
  
  <p>
    なお、紛失や故障などの原因で認証用のアプリを利用できなくなった際は、アカウントの管理者が二段階認証を無効にする必要がありますが、念のために複数のデバイスを登録しておくこともできます。
  </p>
  
  <h2>
    二段階認証の設定方法
  </h2>
  
  <ol>
    <li>
      Google Authenticatorもしくは同様の認証アプリをスマートフォンなどのデバイスにダウンロードしてください。
    </li>
    <li>
      Memsourceの「セットアップ」の一番下にある「ユーザー設定」の「Two-factor Authentication」を開いてください。
    </li>
    <li>
      認証アプリでQRコードをスキャンしてください。QRコードの代わりに秘密鍵が表示される場合があります。その際はアプリに秘密鍵を手入力してください。
    </li>
    <li>
      アプリが生成した数字のコードを「Code」欄に入力して「Verify」をクリックしてください。
    </li>
  </ol>
  
  <p>
    以上の手順により、お使いのMemsourceアカウントがデバイスの認証アプリと接続されます。これ以降、ログインする度にアプリが自動生成するコードの入力が必要になります。アカウントのセキュリティを高める追加機能としてご活用ください。<br /> 本機能やその他Memsourceについてのご質問は<a href="mailto:japan@memsource.com">こちら</a>までお気軽にお寄せください。
  </p>
</div>