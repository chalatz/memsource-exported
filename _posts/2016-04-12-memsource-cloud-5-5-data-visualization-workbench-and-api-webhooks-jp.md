---
id: 6800
title: 'Memsource クラウド 5.5: データ可視化ワークベンチ＆ API Webhooks'
date: 2016-04-12T05:13:38+00:00
author: admin
layout: post
guid: http://blog.memsource.com/ja/?p=6800
permalink: /2016/04/12/memsource-cloud-5-5-data-visualization-workbench-and-api-webhooks-jp/
slide_template:
  - default
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
  <p>
    <a href="/wp-content/uploads/2016/04/release5.5.png"><img class=" size-full wp-image-6733 alignnone" src="/wp-content/uploads/2016/04/release5.5.png" alt="release5.5" width="800" height="390" data-id="6733" /></a>
  </p>
  
  <p>
    Memsource クラウド5.5が2016年4月10日（日）にリリースしました。
  </p>
  
  <p>
    今回もバージョンアップ中のダウンタイムゼロを実現しました。
  </p>
  
  <p>
    今回のバージョンアップにより、次の機能が追加されました。
  </p>
  
  <ol>
    <li>
      無料のデータ可視化ツール Kibanaを使用したデータのカスタマイズ
    </li>
    <li>
      API改良：　Webhooksの採用・リンギストユーザーもAPIをご利用可能に（以前まではプロジェクトマネージャーまたは管理者以外APIを使えませんでした）
    </li>
  </ol>
  
  <p>
    <!--more-->
  </p>
  
  <h3>
    Kibana &#8211; データ可視化ワークベンチ
  </h3>
  
  <p>
    <strong>Memsource BIZ アルティメット版のユーザーは、Kibanaによって、アカウントから得たデータをを可視化することができるようになります。Kibanaは、オープンソースのデータ可視化用のワークベンチです。</strong>
  </p>
  
  <p>
    Kibanaを使うことで、Memsourceのデータを可視化・検証することができます。利用できるデータは、ユーザーの皆様の各アカウント内のデータのみとなります。現在すべてのプロジェクトに関するデータはインデックスをつけられています。Kibanaを使うことで、多くのクエリを可視化することができます。
  </p>
  
  <p>
    &nbsp;
  </p>
  
  <p>
    <strong>データ可視化のサンプル</strong>
  </p>
  
  <p>
    Kibanaを使って可視化できるクエリには次のようなものがあります。
  </p>
  
  <ul>
    <li>
      プロジェクトマネージャーごとのプロジェクト/ジョブ
    </li>
    <li>
      使用された機械翻訳エンジンごとのプロジェクト
    </li>
    <li>
      納期をすぎたジョブを含むリンギスト・ベンダーごとのジョブ
    </li>
    <li>
      ファイルタイプ別のジョブ
    </li>
    <li>
      トップ言語ペア　など
    </li>
  </ul><figure id="attachment_6743" style="width: 719px" class="wp-caption aligncenter">
  
  <a href="/wp-content/uploads/2016/04/top-10-language-pairs1.png"><img class="wp-image-6743" src="/wp-content/uploads/2016/04/top-10-language-pairs1.png" alt="top 10 language pairs" width="719" height="339" data-id="6743" /></a><figcaption class="wp-caption-text">（Memsourceのデモアカウントから得られたトップ10言語ペア）</figcaption></figure> 
  
  <p>
    <strong> </strong>
  </p>
  
  <p>
    <strong>プロジェクトレベルデータ</strong>
  </p>
  
  <p>
    このようにプロジェクトに関するすべてのデータを指数化することができます。
  </p>
  
  <p>
    データには下記のようなものがあげられます。
  </p>
  
  <ul>
    <li>
      プロジェクト <ul>
        <li>
          プロジェクト作成日・最終更新日・作成者・最終更新者・原文言語・訳文言語・プロジェクト設定・クライアント・ドメイン・サブドメイン・ビジネスユニット・プロジェクトステータス・納期　など
        </li>
      </ul>
    </li>
    
    <li>
      ジョブ <ul>
        <li>
          ジョブ作成日・最終更新日・作成者・最終更新者・原文言語・訳文言語・アサインされたリンギスト/ベンダー・納期・ワークフローステップ・ファイルタイプ　など
        </li>
      </ul>
    </li>
    
    <li>
      解析 <ul>
        <li>
          総ワード数・課金率適用後ワード数・翻訳メモリ一致率・機械翻訳一致率　など
        </li>
      </ul>
    </li>
  </ul>
  
  <p>
    &nbsp;
  </p>
  
  <p>
    <strong>セグメントレベルデータ</strong>
  </p>
  
  <p>
    今後、セグメントレベルデータ（翻訳データ）の指数化も予定しています。これによって、翻訳の生産性について独自の考察を行うことができますし、次のようなデータを視覚化することができます。
  </p>
  
  <ul>
    <li>
      お客様ごとの翻訳メモリの流用率
    </li>
    <li>
      機械翻訳エンジンごとの翻訳生産性
    </li>
    <li>
      翻訳時間　対　翻訳メモリ/機械翻訳の流用率比較
    </li>
  </ul>
  
  <p>
    Kibanaを使うことで、作成日・作成者・所有者・削除した人など、ユーザーのアカウント内の各ジョブ/ファイルごとの詳細がわかります。
  </p>
  
  <h3>
    API
  </h3>
  
  <p>
    Memsource APIは今回のリリースにより、大きく変わりました。
  </p>
  
  <p>
    <strong>Webhooks</strong>
  </p>
  
  <ul>
    <li>
      Webhooks（コールバック）は、ステータスの変更を確認するために導入されました。以前は、ユーザーはステータス変更に関する情報が含まれているかどうかを確認するために、GetJobを呼び出す必要がありました。今後、ジョブのステータスが変更されるとすぐに、ユーザーのインテグレーションに直接コールを送ります。
    </li>
  </ul>
  
  <p>
    <strong>リンギストユーザーもAPIを使えるように</strong>
  </p>
  
  <ul>
    <li>
      APIは先日からすべての有料エディションのユーザーに使えるようになりましたが、今後さらに、リンギストユーザーも使うことができます。これによって、たとえば、MemsourceとXbenchを連携させることができます。
    </li>
  </ul>
  
  <p>
  </p>
  
  <p>
    <strong>そのほか</strong>
  </p>
  
  <ul>
    <li>
      APIを使ってプロジェクトを作成した際、プロジェクトのテンプレートに基づいてリンギストをアサインすることができます。
    </li>
    <li>
      多言語MS ExcelファイルもAPIを使ってインポートすることできます。
    </li>
    <li>
      APIを使ってクライアント・ドメイン・サブドメイン（メタデータ）を削除することが可能です。
    </li>
  </ul>
  
  <h3>
    XLIFF 2.0
  </h3>
  
  <p>
    XLIFF1.2とXLIFF2.0で、ファイルインポート設定を別々に行うことができます。ともにインポート・エクスポートする属性マッピングを設定できます。
  </p>
  
  <p>
    <a href="/wp-content/uploads/2016/03/xliff.png"><img class="aligncenter wp-image-6726" src="/wp-content/uploads/2016/03/xliff.png" alt="xliff" width="419" height="242" data-id="6726" /></a>
  </p>
  
  <p>
    <strong>InDesign </strong><strong>ファイルのインデックス</strong>
  </p>
  
  <p>
    Adobe InDesignファイルにおいて、後処理を行う必要なく、InDesignファイルのインデックスを翻訳することが可能になりました。
  </p>
  
  <p>
    &nbsp;
  </p>
  
  <p>
    <strong>新たなユーザーインターフェース言語</strong>
  </p>
  
  <p>
    新たに３つのユーザーインターフェース言語が加わりました:
  </p>
  
  <ul>
    <li>
      フランス語 (<a href="http://www.semantix.eu">Semantix</a>による翻訳）
    </li>
    <li>
      フィンランド語 (<a href="http://www.semantix.eu">Semantix</a>による翻訳）
    </li>
    <li>
      オランダ語 (ProLinguoによる翻訳)
    </li>
  </ul>
  
  <p>
    ご協力いただいたパートナーの皆様、ありがとうございました。
  </p>
  
  <p>
    &nbsp;
  </p>
  
  <h3>
    機械翻訳
  </h3>
  
  <p>
    <strong>TildeMT</strong>
  </p>
  
  <ul>
    <li>
      Memsourceからのログイン方法を改良しました。
    </li>
  </ul>
  
  <p>
    &nbsp;
  </p>
  
  <h3>
    新言語
  </h3>
  
  <p>
    新たに次の言語をサポートします。
  </p>
  
  <ul>
    <li>
      英語 –香港
    </li>
    <li>
      英語– インドネシア
    </li>
    <li>
      英語– マレーシア
    </li>
    <li>
      ブリヤート語
    </li>
  </ul>
</div>