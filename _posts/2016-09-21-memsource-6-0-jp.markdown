---
author: Akira.Popal
comments: true
date: 2016-09-21 00:23:54+00:00
layout: post
link: https://www.memsource.com/ja/blog/2016/09/21/memsource-6-0-jp/
slug: memsource-6-0-jp
title: Memsource 6.0リリース：便利になったPDF翻訳、CMSとの連携、Webエディタの高速化
wordpress_id: 8897
categories:
- バージョンアップ
---


[![memsource-6-0_dropbox_pdf_salesforce_googledrive_ftp_globalese](/wp-content/uploads/2016/09/Memsource-6.0_Dropbox_PDF_Salesforce_GoogleDrive_FTP_GLobalese.png)](/wp-content/uploads/2016/09/Memsource-6.0_Dropbox_PDF_Salesforce_GoogleDrive_FTP_GLobalese.png)

Webエディタの高速化、Dropbox、Google Drive、FTPとの連携機能、TransPDFを経由したPDFファイル翻訳などを含む、Memsourceの大型バージョンアップが発表されました。今回新たに追加された機能をご紹介します。

<!-- more -->今年から開発とリリースの体制が大きく変わり、今までのようなアップデートに伴うメンテナンスやダウンタイムは発生しなくなりました。この記事でご紹介する機能は幾度ものバグ修正を経てすでに皆様のアカウントに実装されています。説明動画はこちら。（英語）







### Dropbox、Google Drive、FTP　との連携が可能に


![ftp-icon-3](/wp-content/uploads/2016/09/FTP-icon-3.png)[![](/wp-content/uploads/2016/09/Google-Drive-Logo.jpg)](/wp-content/uploads/2016/09/Google-Drive-Logo.jpg)![dropbox-logo](/wp-content/uploads/2016/09/dropbox-logo.png)

DropboxやGoogle Drive、FTPフォルダなどのオンラインストレージとMemsourceを同期できるようになりました。



*2017年5月31日追記：接続できる外部サービスが追加されています。各エディションでご利用可能なストレージは下記の通りです。
Team Start、Team、Ultimate、Biz Start、Biz Team、Biz Ultimate、Academic；
Google Drive、Dropbox、Box、WordPress、Drupal、GitHubのストレージと接続いただけます。
Ultimate、Biz Team、Biz Ultimate；
上記に加え、FTPおよびSFTPフォルダと接続できます。
1+FreelancerエディションではGoogle DriveおよびDropboxと連携することができます。




**特長**



 	
  * オンラインストレージに保存してあるファイルからジョブを作成

 	
  * 同期フォルダを定期的にチェックし、追加されたファイルがあればジョブを自動作成*

 	
  * 翻訳が完了したら別名でフォルダに保存




*ジョブの自動作成はTeam, Ultimate, Biz Team, Biz Ultimate, Academicエディションにて可能。［セットアップ］→［Automated Project Creation]より設定していただけます。詳細は[こちら](http://wiki.memsource.com/wiki/Automated_Project_Creation)



このコネクター機能により、ファイルを手動で取り扱う作業が削減できます。Memsourceと連携させたオンラインストレージで翻訳用ファイルの管理を行うようにCMSを設定すれば、大量のコンテンツや更新速度の速いコンテンツの翻訳フローが大きく簡略化されます。

オンラインストレージとMemsourceの連携は［セットアップ］→［インテグレーション］→［コネクター］から設定できます。


### より高速化したWebエディタ


Webエディタを導入して以来、私たちはユーザーにとってより使いやすいアプリケーションを目指してアップデートを繰り返して参りました。今回のリリースでは、スピードを大きく改善しました。

スペルチェッカーの最適化などのいくつかの改良により、全体的に処理速度が上がり、タイピングやスクロール時の動作がなめらかになりました。

オフラインや不十分な通信環境では今後もMemsourceエディタが活躍しますが、大きなファイルも扱いやすくなったWebエディタの満足度は大きく向上するでしょう。


### TransPDF経由でPDFを翻訳する


このアップデートにより、PDFファイルの翻訳が格段に便利になりました。ファイルのインポートから、翻訳、翻訳後のPDFファイルの作成まで、Memsourceで一貫して行えます。別のプログラムを起動してデスクトップパブリッシング(DTP)作業を行う必要はもはやありません(ファイルの形式によっては一部未対応です)。

[![](/wp-content/uploads/2016/09/transPDF-1-1024x361.png)](/wp-content/uploads/2016/09/transPDF-1.png)

本機能を使用するにはPDFファイルからXLIFFファイルへの相互変換を行うオンラインツール[Iceni TransPDF](http://www.iceni.com/transpdf.htm)を利用します。訳文を流し込んでPDFファイルを作成した後の品質チェックは依然として必要ですが、今回のバージョンアップによりPDFファイル翻訳のハードルが大きく下がったことはMemsourceユーザーにとって大きなメリットとなるでしょう。

MemsourceアカウントをTransPDFと連携すると



 	
  * PDFファイルを他のファイル形式と同様にインポートしてジョブの作成、翻訳ができます

 	
  * 翻訳後のファイルはMemsource CloudからPDFとしてダウンロードするか、Iceni TransPDFにログインしてRTFファイルをダウンロードしてレイアウトを修正することも可能です

 	
  * [Iceni Infix](http://www.iceni.com/infix.htm) のPDFエディタでPDFファイルを編集できます


**設定**

この機能を使用するにはTransPDFで自分のアカウントを作成し、クレジットを追加する必要があります。Iceni TransPDFのサービスは1ページ作成する毎に€0.12～€0.41の使用料がかかりますが、アカウントを作成したら50ページまで無料でPDFファイルを作成できます(インポートできるファイル数に制限はありません)。共同作業を行う翻訳者、校正者はMemsourceエディタから無料で直接プレビューを確認できます。

TransPDFを使用しなくても、 Memsourceにデフォルトで設定されているPDFフィルターで今まで通りPDFファイルのインポート、翻訳はできます。ただしこちらの手順ですと翻訳後にはテキストファイルが生成されるので、手動でPDFファイルを再作成する必要があります。


### ジョブボードのデザインが一新


今回のアップデートでジョブボードのデザインが大幅に変わり、募集状況が一目でわかるようになりました。

[![job-board](/wp-content/uploads/2016/09/job-board-1024x531.png)](/wp-content/uploads/2016/09/job-board.png)

**バイヤー:**



 	
  * ジョブを掲載する時にサンプル文章を添付できるようになりました

 	
  * 納期の設定が必須になり、納期を越えたジョブは自動的に募集を終了します

 	
  * プロジェクトタブではジョブボードに掲載したプロジェクトをフィルタリングできます

 	
  * 新しいジョブの募集通知を受けたベンダーの数が確認でき、マウスを当てると返答の数が表示されます


**ベンダー:**



 	
  * 公募中のジョブが常に一番上に表示されるようになりました

 	
  * 返答済みのジョブはグレーアウトします

 	
  * 募集プロジェクトにはバイヤーの名前も表示されます

 	
  * ジョブボードに掲載されているプロジェクトがMemsource Cloudから削除された場合は募集も終了します




### 機械翻訳エンジンGlobaleseが登場


ドキュメントの種類や分野に合わせてカスタマイズできるGlobalese MTエンジンをMemsourceで使用できるようになりました。プロジェクトに特化したエンジンの機械翻訳をMemsourceのエディタで参照することができます。
Globaleseはハンガリーの言語サービスプロバイダMorphoLogic Localisationが開発した機械翻訳エンジンでオープンソースの統計的機械翻訳エンジン「Moses」をベースにしています。オンラインサービスに加え、ご自身でサーバーを構築して運用することもでき、翻訳メモリを学習させてカスタマイズすることが可能です。

[![globalese_evaluation](/wp-content/uploads/2016/09/Globalese_evaluation-300x208.png)](/wp-content/uploads/2016/09/Globalese_evaluation.png) [![globalese_memsource](/wp-content/uploads/2016/09/globalese_memsource-300x208.png)](/wp-content/uploads/2016/09/globalese_memsource.png) [![globalese_stats](/wp-content/uploads/2016/09/globalese_stats-300x209.png)](/wp-content/uploads/2016/09/globalese_stats.png)

_Globalese MT操作画面例。クリックすると拡大します。_

**設定手順**

設定 -> インテグレーション -> 機械翻訳エンジンから新しい機械翻訳エンジンを作成します。この際にAPIキーとエンジンIDが必要になります。

「タグを含む」にチェックを入れると 原文のタグが自動的に訳文に反映されるので便利です。


### QuarkXPressファイルの形式TAGとXTGがサポート対象に


レイアウトの作成と編集を行うDTPソフトウェアQuarkXPressのファイルをMemsourceで扱えるようになりました。

QuarkXpressで保存できるファイル形式のうち、現在のところMemsourceが対応しているのはTAGとXTGの二つです。

QuarkXpressのファイルは設定でカーニングおよびトラッキングのタグを除去してインポートすることが可能です。

[![memsource-google-chrome-2016-09-09-10-36-18](/wp-content/uploads/2016/09/Memsource-Google-Chrome-2016-09-09-10.36.18-300x185.png)](/wp-content/uploads/2016/09/Memsource-Google-Chrome-2016-09-09-10.36.18.png)


### Salesforceの翻訳フローが簡略化


Salesforce.com上のコンテンツを翻訳する際に、リンクからジョブを作成できるようになりました。この新機能は顧客管理をSalesforceで行い、翻訳の管理をMemsourceで行う言語サービスプロバイダなどにとっては非常に役に立つでしょう。
他にもレポートを直接ダウンロードする機能が搭載され、個別の電子メールを大量に送信する際に作成が容易になりました。翻訳メモリを活用すれば、英語の宛名を全て日本語に訳すのもあっという間です。


### 既存のプロジェクトテンプレートのTMやTBを変更が可能に


既存のプロジェクトテンプレートに設定されている翻訳メモリや用語ベースの追加や削除ができるようになりました。このアップデートによりTMやTBを変更するために新しいプロジェクトテンプレートを作成する必要がなくなりました。

**設定手順**



 	
  * セットアップ -> プロジェクトテンプレートを開きます

 	
  * 変更を加えたいテンプレートを選択してください

 	
  * ページの下部からTMやTBを変更できます




### 文字情報を含むCSVのダウンロード


解析結果をダウンロードする際のフォーマットに、文字情報を含むCSVファイルが追加されました。

[![CSV with Characters](/wp-content/uploads/2016/09/MultiExcel-Memsource-Google-Chrome-2016-09-09-13.46.11-1-1024x182.png)](/wp-content/uploads/2016/09/MultiExcel-Memsource-Google-Chrome-2016-09-09-13.46.11-1.png)


### APIがさらに充実


MemsourceのAPIにもいくつかの重要な変更が加えられています。



 	
  * 新しい[File API](http://wiki.memsource.com/wiki/File_API_v2)は様々な方法でのファイルのアップロードを可能にします。ファイルがアップロードされるとハンドルが返り、ジョブ作成などの他APIに使用することができます。今回のアップデートにより以下のようなことが可能になりました。

 	
    * リクエストボディでファイルをアップロード

 	
    * マルチパートフォームデータでファイルをアップロード

 	
    * URLからファイルをアップロード

 	
    * ファイルを削除

 	
    * ファイルをダウンロード




 	
  * APIで駆動する人間翻訳エンジン
Gengo社が提供する翻訳サービスをAPIを通じ自動で利用できるようになりました。詳細については[API manual](http://wiki.memsource.com/wiki/Async_Translate_Settings_API_v2)(英語)をご確認ください。

 	
  * 新規ジョブが作成されたことを知らせるWebhook
新しいジョブが作成されると[webhooks](http://wiki.memsource.com/wiki/Memsource_API#Webhooks)を通じてURLを送信できます。

 	
  * ソースをターゲットにコピーする新しい[API](http://wiki.memsource.com/wiki/Project_API_v3#Copy_Source_to_Target)が登場。

 	
  * Get UserまたはList UsersのAPIコールに対するレスポンスに次のデータも含まれるようになりました。

 	
    * 作成日

 	
    * 最終ログイン日







### RESXファイルをMemsourceタグに変換する






「Memsourceタグに変換」オプションがRESXファイルに追加されました。このオプションは、文章の一部を翻訳対象から除外する際などに便利です。

以上駆け足でご説明させて頂きましたが、新しくなったMemsourceの機能をぜひ体感してください。





