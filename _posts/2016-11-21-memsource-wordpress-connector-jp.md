---
id: 9765
title: Memsource 6.4:WordPressと接続してブログコンテンツの翻訳ワークフローを自動化
date: 2016-11-21T10:58:09+00:00
author: admin
layout: post
guid: http://memsource.elcaptain.cz/ja/?p=9765
permalink: /2016/11/21/memsource-wordpress-connector-jp/
slide_template:
  - ""
  - ""
  - ""
  - ""
categories:
  - カテゴリーなし
  - バージョンアップ
  - 高度な機能
---
<div style="font-family: 'メイリオ', Meiryo, 'ヒラギノ角ゴ Pro W3'; font-size: medium;">
  <a href="/wp-content/uploads/2016/10/Blog-post_-WordPress-Connector_600.png"><img class="size-full wp-image-9283 aligncenter" src="/wp-content/uploads/2016/10/Blog-post_-WordPress-Connector_600.png" alt="blog-post_-wordpress-connector_600" width="600" height="300" data-id="9283" /></a>Memsource 6.4の新機能をお知らせいたします。今回のアップデートにより、WordPressとの連携、通知メールのアドレスをカスタマイズすることが可能になった他、オートメーションウィジェットとQAチェックが強化され、さらにMemsourceの新機能の概要を紹介するページが登場しました。</p> 
  
  <p>
    <!--more-->
    
    <br /> 高い頻度で更新されるブログやコーポレートサイトを多言語にローカライズするのは簡単な作業ではありません。ミスを最小限に抑えながら効率よく翻訳フローを回すためにはプロジェクトマネージャーの努力と工夫が不可欠ですが、細かい更新に伴うファイルの版数管理や、CMSからの原稿抽出作業など人為的ミスの落とし穴は多く存在します。
  </p>
  
  <p>
    今回のアップデートによりMemsourceにWordPressとの<a href="/ja/memsource-6-0-jp/" target="_blank">コネクター</a>が搭載され、<a href="http://wiki.memsource.com/wiki/WordPress_Plugin">WordPressのMemsourceプラグイン</a>と組み合わせることでWordPressコンテンツの翻訳フローを大幅に自動化することが可能になりました。この機能は人為的ミスを防ぐのに役立つだけでなく、上手に活用すれば営業時間外でもプロジェクトを自動で進行させることができます。
  </p>
  
  <div style="font-size: small;">
    注：<br /> この機能の対象となるのはWordPressのWPMLプラグインによって多言語化されているウェブサイトで、さらにプラグインの言語の設定をMemsourceのプロジェクトの言語設定と一致させる必要があります。<br /> Memsourceの<a href="http://wiki.memsource.com/wiki/Connectors" target="_blank">コネクター</a>をご利用頂けるのは下記のエディションです。<br /> チームスタート、チーム、アルティメット、Bizスタート、Bizチーム、Bizアルティメット
  </div>
  
  <h3>
    設定手順
  </h3>
  
  <ol>
    <li>
      まずはWordPressにMemsourceのプラグインを追加しましょう。ダッシュボードにログインしたら、「Plugins」の「Add New」をクリックしてください。<br /> <a href="/wp-content/uploads/2016/10/Plugins.png"><img class="alignnone size-full wp-image-9218" src="/wp-content/uploads/2016/10/Plugins.png" alt="plugins" width="143" height="118" data-id="9218" /></a>
    </li>
    <li>
      プラグインのページに移動したら「Memsource Connector」を検索し、インストールを開始しましょう。<br /> <a href="/wp-content/uploads/2016/10/Memsource-WP-2.jpg"><img class="alignnone size-full wp-image-9220" src="/wp-content/uploads/2016/10/Memsource-WP-2.jpg" alt="memsource-wp-2" width="639" height="244" data-id="9220" /></a>
    </li>
    <li>
      インストールが完了したら、ダッシュボードに戻り新しく追加されたMemsourceという項目を選択すると、トークンが表示されます。.
    </li>
    <li>
      次にMemsource Cloudの[セットアップ]→[コネクター]でWordPressを設定しましょう。その際に上記のトークンが必要になります。
    </li>
  </ol>
  
  <p>
    以上でMemsourceアカウントとWordPressの連携は完了です。
  </p>
  
  <p>
    &nbsp;
  </p>
  
  <p>
    <a href="/wp-content/uploads/2016/10/Blog_connector-1.png"><img class="alignnone wp-image-9215" src="/wp-content/uploads/2016/10/Blog_connector-1.png" width="750" height="563" data-id="9214" /></a>
  </p>
  
  <p>
    <em>参考画面：Memsourceのコネクターを利用して公開されたブログの記事から翻訳対象を選ぶ</em>
  </p>
  
  <p>
    ウェブサイトのファイルを翻訳する際は「オンラインストレージから追加する」の機能を使用してジョブを作成します。翻訳が完了したら「ダウンロード」→「オンラインストレージにエクスポート」を選択すると、WordPressに直接にアップロードすることができます。これによりWordPressのサイトで別言語の翻訳記事が自動的に作成されPublishされます。<br /> 翻訳記事のURLはWPMLプラグインの設定に応じ自動的に付与されますが、WordPressのダッシュボードから変更することも可能です。
  </p>
  
  <h3>
    新しい記事が公開されたら自動的に翻訳ジョブを作成
  </h3>
  
  <div style="font-size: small;">
    対象エディション：チーム、アルティメット、Bizチーム、Bizアルティメット、アカデミックエディション
  </div>
  
  <p>
    プロジェクトの自動作成機能を使用することで、ウェブサイトで記事が公開されたら自動的に翻訳プロジェクトが作成されるように設定することもできます。例えば一日一回朝9時や毎日15分毎にウェブサイトをチェックし、新しいファイルがあったら事前に設定したプロジェクトテンプレートやワークフロー、価格表に応じてプロジェクトを作成し、翻訳者や校正者へメールを送信するといった一連の作業を全て自動化することができます。
  </p>
  
  <p>
    プロジェクトの自動作成機能の詳細については<a href="http://wiki.memsource.com/wiki/Automated_Project_Creation" target="_blank">こちら</a>をご覧ください。
  </p>
  
  <h3>
    記事が更新されたら変更箇所だけを抽出して翻訳
  </h3>
  
  <p>
    多言語展開するブログページでは、元記事が公開後に修正されても訳文の方にまで手が回らないというケースが多くあります。今回のMemsourceとWordPressの連携機能は、頻繁に更新されるブログの翻訳において特に大きな効果を発揮します。
  </p>
  
  <ul>
    <li>
      オンラインストレージとの連携機能(コネクター)を利用しWordPressで公開されているページが更新されたら、自動的にプロジェクトが作成されるようにします。
    </li>
    <li>
      プロジェクトテンプレートに元の記事の翻訳で使用したTMを設定し、下記の通り設定します。
    </li>
  </ul>
  
  <p style="padding-left: 60px;">
    <strong>以下のセグメントをConfirmする</strong><br /> + Non-translatables<br /> + 100% matches<br /> + 101% matches
  </p>
  
  <p style="padding-left: 60px;">
    <strong>以下のセグメントをLockする</strong><br /> + Non-translatables<br /> + 100% matches<br /> + 101% matches
  </p>
  
  <p>
    上記により、アップデートされた記事の翻訳ジョブが作成されたときに、前回のTMと一致する部分(既訳箇所)は自動的にConfirmされ、ロックされます。後はフィルタ機能でUnconfirmedのセグメントを抽出すれば、変更された部分だけを翻訳することができます。<br /> 翻訳が完了したら、Memsource上から直接WordPressにアップロードされ、公開済みの記事が更新されます。
  </p>
  
  <h2>
    Memsourceの新機能をお知らせするページが公開
  </h2>
  
  <p>
    /new
  </p>
  
  <p>
    Memsourceは皆様のご要望とご期待に応えるべく定期的なアップデートを行っております。アップデート内容の詳細は今まで通り当ブログや英語のサポートサイトでお伝えしていきますが、次々と登場する新機能の概要を一覧でご紹介するページ(英語)を<a href="/new/" target="_blank">こちら</a>にご用意しました。ぜひお気に入りに追加、もしくはRSSで購読し、ますます便利になるMemsourceをご活用ください。
  </p>
  
  <h2>
    Memsourceの通知メールを任意のアドレスから送信
  </h2>
  
  <div>
    <div style="font-size: small;">
      対象エディション：BIZアルティメット、アルティメット
    </div>
    
    <p>
      PMや翻訳者宛ての通知メールはこれまで一様にsystem@memsource.comから送信されていましたが、この送信アドレスをカスタマイズできるようになりました。事前にドメインを取得していれば自ドメインのアドレスからメールを送信できるので、Memsourceを利用する法人様はブランディングの一助としてぜひご活用ください。<br /> 本機能の設定についてはこちらをご覧ください。（本機能はアルティメット版またはBIZアルティメット版ご利用のお客様のみご利用頂けます）
    </p>
  </div>
  
  <h2>
    オートメーションウィジェットの納期がリンギストにも通知されるようになりました。
  </h2>
  
  <div>
    <p>
      翻訳の発注を自動化できる便利な機能<a href="https://www.youtube.com/watch?v=uTTDOksuvlI" target="_blank">「オートメーションウィジェット」</a>にも改善が見られました。今まではクライアントが発注した翻訳の分量に応じた納期がPMにだけ通知されていましたが、アサインされているリンギストにも納期が通知されるようになりました。これにより営業時間外や連休中などPMが手をつけられない時でも翻訳者や校正者は作業の予定を立てることができます。
    </p>
    
    <p>
      この機能は、定期的に翻訳を受発注する翻訳会社とバイヤーの関係において高い効果を発揮します。事前に翻訳者を指定しておけば、ほとんどの工程を自動化できます。
    </p>
    
    <div style="font-size: small;">
      注：<br /> リンギストに通知されるのはプロジェクト全体の納期です。ワークフローステップを複数にわけている場合は、納期を手動設定にして、ワークフローのステップ毎に適切な納期を定めましょう。注：<br /> オートメーションウィジェットの納期を設定するには、<br /> (1) セットアップの「納期スキーム」で任意のルールを設定し、<br /> (2) セットアップの「提供するサービス」に新規作成した納期スキームを設定し、<br /> (3) オートメーションウィジェットで使用する「提供するサービス」を選択します。</p>
    </div>
    
    <p>
      <img class="alignnone size-full wp-image-9247" src="/wp-content/uploads/2016/10/due-date-scheme.png" alt="due-date-scheme" width="716" height="828" data-id="9247" />
    </p>
    
    <h2>
      QAチェックにも新機能
    </h2>
    
    <p>
      QAチェック機能に新しい項目が追加され、作業者があいまい一致のセグメントを編集せずにそのまま確定すると、注意を促すフラグが立つようになりました。
    </p>
    
    <p>
      あいまい一致とは原文がTMと類似しているが100%一致しているわけではない状態を指します。実際には修正が必要なところをTMとの差異を見落としてそのまま確定してしまうというミスを防ぎます。
    </p>
    
    <h2>
      API
    </h2>
    
    <div>
      <p>
        用語ベースのエントリを取得するのにterm IDだけでなくconcept IDも使用できるようになりました。これには下記のコールを使用します。
      </p>
      
      <p>
        api/v2/termBase/listTermsOfConcept
      </p>
    </div>
  </div>
</div>