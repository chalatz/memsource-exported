---
id: 20350
title: シングルサインオンでアカウント管理をよりセキュアに
date: 2017-12-27T11:56:09+00:00
author: admin
layout: post
guid: 'https://www.memsource.com/blog/2017/12/27/%e3%82%b7%e3%83%b3%e3%82%b0%e3%83%ab%e3%82%b5%e3%82%a4%e3%83%b3%e3%82%aa%e3%83%b3%e3%81%a7%e3%82%a2%e3%82%ab%e3%82%a6%e3%83%b3%e3%83%88%e7%ae%a1%e7%90%86%e3%82%92%e3%82%88%e3%82%8a%e3%82%bb%e3%82%ad/'
permalink: /2017/12/27/single-sign-on-in-memsource-cloud-2/
bottom_logo_heading:
  - ""
floating_logo_heading:
  - ""
main_logo_heading:
  - ""
transparent_logo_heading:
  - ""
fake_id:
  - ""
favicon_heading:
  - ""
categories:
  - カテゴリーなし
  - 新機能
  - 高度な機能
tags:
  - Memsource クラウド
  - 管理者アカウント
---
<div style="font-family: 'メイリオ', Meiryo, 'ヒラギノ角ゴ Pro W3'; line-height: 175%;">
  <p>
    <a class="dt-pswp-item" href="https://www.memsource.com/wp-content/uploads/2017/12/Blog-post_-single-sign-on-1.png" data-dt-img-description="" data-large_image_width="820" data-large_image_height="461"><img class="aligncenter wp-image-20115" src="https://www.memsource.com/wp-content/uploads/2017/12/Blog-post_-single-sign-on-1-300x169.png" alt="シングルサインオンに対応" width="550" height="309" /></a>
  </p>
  
  <p>
    クラウドサービスが当たり前のものとして普及している現在では、日々の業務を行うためにさまざまなオンラインサービスが利用されています。
  </p>
  
  <p>
    こうした企業にとって、複数のサービスを単一のログインシステムで利用する「シングルサインオン(Single Sign-on または SSO)」は、従業員の利便性を向上するだけでなく、セキュリティの観点からも大変のぞましいことです。
  </p>
  
  <p>
    複数のアカウントの管理に頭を悩ますユーザー様に、朗報をお届けします。先日のアップデートにより、Memsourceは<a href="https://www.onelogin.com/"><span style="font-weight: 400;">OneLogin</span></a><span style="font-weight: 400;">のサービスを介したSSOをサポートするようになりました。対象エディション(アルティメット)の管理者は、この新機能によりMemsource クラウドのユーザーをより簡単に、そしてセキュアに管理できるようになります。</span>
  </p>
  
  <p>
    <!--more-->
  </p>
  
  <h3>
    SSOって？
  </h3>
  
  <p>
    <span style="font-weight: 400;">シングルサインオンと一口にいってもいくつかの方式がありますが、この度Memsourceがサポートするのはもっとも一般的な「フェデレーション方式」とよばれるものです。</span>
  </p>
  
  <p>
    これはアイデンティティプロバイダー(IdP)にログインするだけで、そこを経由してIdPと連携する種々のアプリケーションに自動的にログインできる仕組みです。今回のSSO対応により、OneLoginにログインすればMemsource上でのユーザー名・パスワードの入力の手間を省いてMemsource クラウドを利用できるようになります。
  </p>
  
  <h3>
    SSOの利点は？
  </h3>
  
  <ul>
    <li style="font-weight: 400;">
      <b>セキュリティの向上：</b><br /> 多くの企業では、実に多様なアプリケーションを業務で使用しています。アプリケーションごとに異なるIDやパスワードを使用している状態では、それらすべてを安全に管理することは難しく、企業のネットワークやデータが危険にさらされます。SSOを利用して従業員が利用する認証情報を減らすことで、より厳格なパスワードポリシーのもとでの運用が可能になります。逆にいえば、1つのIDとパスワードが漏洩するだけで複数のアカウントが危険にさらされるという事態にもつながりかねませんが、これを防ぐために<a href="https://www.memsource.com/ja/blog/2016/12/18/enhancing-account-security-with-two-factor-authentication-jp/">2段階認証</a>などの補強対策を併用することで、アカウントのセキュリティは劇的に向上します。
    </li>
    <li style="font-weight: 400;">
      <b>ユーザー管理の手間を削減：</b><br /> 管理者にとっては、会社で利用するさまざまなアプリケーションへのアクセスを一カ所で管理できるようになります。各ユーザーのMemsourceへのアクセス権は、Memsource上ではなくSSOのシステム上で管理できるようになります。
    </li>
    <li style="font-weight: 400;">
      <b>利便性の向上：</b><br /> 複数のIDとパスワードを管理するのは、ユーザーにとっても負担です。SSOによって、管理すべき認証情報を減らすことで、「パスワードをリセット」という不要な作業に手間をとられることもなくなります。
    </li>
  </ul>
  
  <h3>
    MemsourceでSSOを設定するには？
  </h3>
  
  <p>
    <span style="font-weight: 400;">管理者アカウントからMemsourceのSSO機能を設定するのは難しい作業ではありません。構成はMemsourceアカウントの「設定」から行います。詳しい手順については</span><a href="https://wiki.memsource.com/wiki/Memsource_Cloud_User_Manual#Single_Sign-On" target="_blank" rel="noopener"><span style="font-weight: 400;">こちら(英文)</span></a>をご参照ください。
  </p>
  
  <p>
    <span style="font-weight: 400;">今回のアップデートにより、SAML 2.0に対応するアイデンティティプロバイダーのSSOサービスをMemsourceで利用できるようになっていますが、現時点でフルサポートしているのはOneLoginのみです。OneLoginの設定に関しての詳細は</span><a href="https://support.onelogin.com/hc/en-us/articles/115003638343-Configuring-SSO-for-SAML-Enabled-Apps" target="_blank" rel="noopener"><span style="font-weight: 400;">OneLoginのこちらのページ(英文)</span></a>をご覧ください。
  </p>
  
  <p>
    <span style="font-size: 75%;">＊SSO機能の対象エディションは「アルティメット」と「Bizアルティメット」です。また、SSOの設定を行うには管理者アカウントでログインしている必要があります。</span>
  </p>
  
  <p>
    <span style="font-weight: 400;">&#8212; </span>
  </p>
  
  <p>
    今回はセキュリティを大幅に向上させる新機能のご紹介でした。こちらの内容についてご不明な点は、japan@memsource.comまでお問い合わせください。
  </p>
</div>