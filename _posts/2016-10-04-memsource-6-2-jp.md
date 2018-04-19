---
id: 9074
title: Memsource 6.2：Googleドキュメントの翻訳、翻訳フローの完全自動化が可能になりました。
date: 2016-10-04T01:32:42+00:00
author: admin
layout: post
guid: http://blog.memsource.com/ja/?p=9074
permalink: /2016/10/04/memsource-6-2-jp/
slide_template:
  - ""
  - ""
  - ""
  - ""
categories:
  - バージョンアップ
  - 高度な機能
---
<div style="font-family: 'メイリオ', Meiryo, 'ヒラギノ角ゴ Pro W3'; font-size: medium;">
  <p>
    先日の大型アップデート<a href="/ja/memsource-6-0-jp/">Memsource 6.0</a>に続き、さらなる改善と新機能を盛り込んだMemsource6.2が発表されました。今回のアップデートにより、Googleドキュメントの翻訳や、プロジェクトの自動マネジメント、Memsourceの翻訳メモリを他のCATツールで使用することなどが可能になりました。<br /> <!--more-->
  </p>
  
  <h2>
    Googleドキュメントの翻訳
  </h2>
  
  <p>
    <a href="/wp-content/uploads/2016/09/google-doc.png"><img class="alignnone size-large wp-image-9017" src="/wp-content/uploads/2016/09/google-doc-1024x731.png" alt="google-doc" width="750" height="535" data-id="9017" /></a>
  </p>
  
  <p>
    <em>参考画面：Googleドキュメントのファイルからジョブを作成する</em>
  </p>
  
  <p>
    新しいMemsourceではGoogle Driveから直接Googleドキュメントのファイルを読み込んで、ジョブを作成することができるようになりました。サポート対象は下記のファイルです。
  </p>
  
  <ul>
    <li>
      Google ドキュメント
    </li>
    <li>
      Google スプレッドシート
    </li>
    <li>
      Google スライド
    </li>
  </ul>
  
  <div style="font-size:9pt;">
    *Googleドライブなどのオンラインストレージと接続するコネクター機能を利用できるのはチームスタートエディション以上となります。<br /> パーソナルエディション・フリーランサーエディションではご利用頂けません。
  </div>
  
  <p>
    Googleドライブ上で共有しているドキュメントもマイドライブに追加することで翻訳が可能です。 この方法を用いれば、例えばクライアントと共有しているGoogleスプレッドシートからジョブを作成することもできます。
  </p>
  
  <p>
    Memsource Cloudで翻訳が完了したら、Googleドキュメントの形式に再変換されます。
  </p>
  
  <p>
    <strong>翻訳が完了したら･･･</strong>
  </p>
  
  <p>
    <img class="alignnone wp-image-9018" src="/wp-content/uploads/2016/09/export.png" alt="export" width="750" height="195" data-id="9018" />
  </p>
  
  <ul>
    <li>
      手動アップロード：翻訳済みのファイルをGoogleドライブに保存するには[ダウンロード]の[オンラインストレージにエクスポートする]を選択してください。
    </li>
    <li>
      自動アップロード：Googleドライブからジョブの自動作成機能で作成されたジョブは、原稿と同じ場所に翻訳済みファイルが自動で保存されます。
    </li>
  </ul>
  
  <h2>
    Googleドライブ, Dropbox、FTPと連携して自動でインポート、エクスポート
  </h2>
  
  <p>
    <a href="/wp-content/uploads/2016/09/Configure_Automated_Project_Creation.png"><img class="alignnone wp-image-9022" src="/wp-content/uploads/2016/09/Configure_Automated_Project_Creation.png" alt="configure_automated_project_creation" width="750" height="666" data-id="9022" /></a>
  </p>
  
  <p>
    オンラインストレージをMemsourceと接続すれば、プロジェクトの自動作成機能をご利用頂けます。任意のGoogleドライブ上のフォルダなどを定期的にチェックし、新しいファイルがあればジョブが作成され、翻訳が完了したら同じフォルダに自動的に保存されます。
  </p>
  
  <p>
    例えばWebサイトのコンテンツマネジメントシステム(CMS)からオンラインストレージのフォルダにコンテンツをエクスポートするように設定し、<a href="/ja/5-0-jp/">複数の登録翻訳者やベンダー</a>をプロジェクトに紐付けておけば、プロジェクトの作成と同時に割り当てのメールが送信されます。更新頻度の高いWebサイトのコンテンツなどの翻訳フローを大幅に自動化できます。
  </p>
  
  <p>
    プロジェクトの自動作成はセットアップの<strong>Automated Project Creation</strong>から設定できます。
  </p>
  
  <p>
    詳細は<a href="http://wiki.memsource.com/wiki/Automated_Project_Creation">こちら</a>(英語Wiki)をご覧ください。
  </p>
  
  <h2>
    Memsourceの翻訳メモリを他のCATツールで使用することが可能に
  </h2>
  
  <p>
    今回のアップデートにより、Memsourceの翻訳メモリをエクスポートすると<bpt>、<ept>、<ph>などの標準的なTMXフォーマットに変換されるようになりました。CATツールと一口に言ってもそれぞれ仕様が異なるため、現段階で100%の互換性を保証するものではありませんが、SDL TradosやKilgray memoQなどのTMXファイルをサポートするCATツールでMemsourceの翻訳メモリが使えるようになりました。
  </p>
  
  <p>
    翻訳作業者もジョブの[ダウンロード]→[TMX]から翻訳メモリのTMXをダウンロードすることができますが、プロジェクトマネージャーが設定で翻訳メモリのダウンロードを許可していることが条件です。
  </p>
  
  <p>
    <a href="/wp-content/uploads/2016/09/Download-TMX.png"><img class="alignnone size-full wp-image-9029" src="/wp-content/uploads/2016/09/Download-TMX.png" alt="download-tmx" width="750" height="252" data-id="9029" /></a>
  </p>
  
  <p>
    Memsource上で作業を行った方が最新の翻訳メモリと用語ベースを常に参照できるので、外部CATツールを使用するのはワークフローとしては理想的とは言えません。それでも、慣れ親しんできたツールを使いたいという翻訳作業者の希望にも応えることが可能になったことは大きな意味を持つでしょう。
  </p>
  
  <h2>
    ワークフローの完全自動化が実現しました
  </h2>
  
  <p>
    今回のアップデートにより、案件の受注からプロジェクトの作成、解析、訳者の割り当て、翻訳済みファイルの納品までを完全自動化することができるようになりました。プロジェクトマネージャーが手を加える必要が一切ないので、営業時間外の受注、納品も可能です。
  </p>
  
  <p>
    ワークフローの完全自動化はオートメーションウィジェット(英語の説明動画は<a href="https://www.youtube.com/watch?v=uTTDOksuvlI">こちら</a>)とAutomated Project Creationの機能を使うことで実現できます。<br /> オートメーションウィジェットを利用してジョブの作成から作業者への通知までを自動化することはこれまでも可能でしたが、これからは事前に設定したルールに応じて翻訳が完了したファイルの納品まで全てを自動化できます。
  </p>
  
  <p>
    設定についての詳細は<a href="http://wiki.memsource.com/wiki/Memsource_Cloud_User_Manual#Project_Status_Automation">こちら</a>(英語Wiki)をご覧ください。
  </p>
  
  <h2>
    その他のアップデート
  </h2>
  
  <ul>
    <li>
      <strong>電子メールテンプレートで使えるマクロが増えました</strong><br /> 新しいマクロ{job.wordCount}を使えば、進捗度を示すパーセンテージの上にマウスを置くことで文字カウントを表示できます。
    </li>
    <li>
      <strong>APIの非同期処理リクエストの保管期間</strong><br /> 翻訳メモリなどの非同期処理のAPIからの非同期リクエストは14日間保管されます。この期間が経過すると、リクエストは削除されますのでご注意ください。 </ul> <p>
      </p>
      
      <div style="font-size:9pt;">
        *Automated Project Creation　（プロジェクトの自動作成機能）については、10月4日現在、Googleドライブにて、一部ご利用いただけない報告を頂いております。早急に修正を進めております。ご迷惑おかけいたしますが、今しばらくお待ちくださいますよう、お願い申し上げます。<br /> *バージョンアップ・本記事について、ご意見・ご不明点などございましたら、こちらよりお気軽にご連絡ください。
      </div></div>