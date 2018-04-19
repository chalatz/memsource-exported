---
id: 5601
title: 多言語XML:Memsource Cloud 5.2
date: 2015-12-11T01:45:32+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=5601
permalink: '/2015/12/11/%e5%a4%9a%e8%a8%80%e8%aa%9exmlmemsource-cloud-5-2/'
slide_template:
  - ""
  - ""
  - ""
  - ""
categories:
  - カテゴリーなし
  - バージョンアップ
---
Memsource Cloud5.2が、2015年11月29日日曜日20時（11時GMT)にリリースしました。

今回のバージョンアップで、次の機能が加わりました。

<!--more-->

  * **多言語****XML**

  * 多言語XMLファイルは、1つの原文言語に対し、複数の訳文言語を含むファイルのことです。以前は、たとえば原文言語が英語で、訳文言語がドイツ語・スペイン語・韓国語である 
    多言語XMLファイルをMemsourceにインポートするときは、バイリンガルXMLフィルタを使うことができました。ただ、各言語ペア（この場合だと、英語-ドイツ語、英語-スペイン語、英語-韓国語）ごとに手入力で別々のジョブを作る必要がありました。
    
    **今後は、新機能の****[多言語XMLフィルタ](http://wiki.memsource.com/wiki/Multilingual_XML)を使って、ひとつのファイルで作業することができます。**
    
    必要なことは、ファイルインポート設定で対応する訳文言語の要素を割り当てるだけです。
    
    これにより、各言語ペアごとに別々のジョブが自動的に作成されます。実際にはファイルは１つのままなので、翻訳後、訳文生成ファイルをダウンロードすると、すべての言語を含むひとつのXMLファイルが手に入ります。
    
    &nbsp;</li> </ul> </ul> </ul> 
    
    [<img class="aligncenter size-full wp-image-5517" src="/wp-content/uploads/2015/11/multilingual-xml.png" alt="multilingual xml" width="677" height="589" data-id="5517" />](/wp-content/uploads/2015/11/multilingual-xml.png)
    
    **サイトコア、****AEM、WordPressなどのコンテンツマネジメントシステム(CMS)は、iLangLによってMemsourceと接続可能となりました。**
    
      * コンテンツマネジメントシステムと翻訳管理システムの統合のためのサービスプロバイダーである[iLangL](http://ilangl.com/)は、Memsourceをサポートしています。iLangLとMemsourceによって、簡単に以下のCMSと接続ができるようになります。 
        また、CMSとMemsourceの間に生じるファイル管理の自動化が可能となります。
        
          * Adobe Experience Manager
          * Sitecore
          * DNN Evoq
          * Drupal
          * EPiServer
          * Umbraco
          * WordPress
        
        詳しくは、[こちらまで](mailto:support@memsource.com)お問合せください。または、もうしばらくお待ちください。
        
        間もなく、この統合についての情報をお伝えします。</li> </ul> </ul> </ul> </ul> 
        
        [<img class="aligncenter wp-image-5536" src="/wp-content/uploads/2015/11/iLangL-CMS-Integration.png" alt="iLangL CMS Integration" width="480" height="243" data-id="5536" />](http://ilangl.com/)
        
        **プロジェクトマネージャー用のジョブ関連情報**
        
          * **ジョブステータスの変更や他のジョブに関連するメタデータについての情報が、プロジェクトマネージャーによって参照できるようになりました。** 
            これまでプロジェクト内のひとつのジョブ上にマウスを合わせるとポップアップ画面がでてきた青色の情報アイコンを取り外し、この情報をふたつのツールチップ上で表示させるようにしました。また、さらに詳細な情報を追加しました。
            
            プロジェクトマネージャーはジョブごとに各ジョブステータス変更の詳細を表示させることができます。
            
            [<img class="aligncenter size-full wp-image-5518" src="/wp-content/uploads/2015/11/job-activity.png" alt="job activity" width="629" height="310" data-id="5518" />](/wp-content/uploads/2015/11/job-activity.png)
            
              * また、プロジェクトマネージャーは完成後のパーセンテージ上にマウスを合わせると表示されるツールチップ上で、ジョブに関連するさらなる情報を表示させることができます。 
                <img class="aligncenter size-large wp-image-5519" src="/wp-content/uploads/2015/11/job-statistics.png" alt="job statistics" width="354" height="280" data-id="5519" /></li> </ul> </li> </ul> </ul> </ul> </ul> 
                
                **プロジェクトマネージャーは登録翻訳者のタイムゾーンをセットすることができます。**
                
                  * **タイムゾーン設定は新しいものではありませんが、プロジェクトマネージャーが翻訳者ユーザーの設定を行うことができるようになりました。** 
                    タイムゾーン設定は決して新しいものではありません。すべてのユーザーは、Memsource Cloud上のユーザー設定-セットアップから設定することができます。このようにして日付と時間は、各ユーザーのローカルタイムゾーンを元に完全に変換することができます。（特に納期のために大事なことです）
                    
                    今後、プロジェクトマネージャーは翻訳者ユーザーの作成時または編集時に、翻訳者ユーザーのタイムゾーンを設定することができるようになりました。
                    
                    [<img class=" size-full wp-image-5520 alignnone" src="/wp-content/uploads/2015/11/Time-Zone.png" alt="Time Zone" width="610" height="496" data-id="5520" />](/wp-content/uploads/2015/11/Time-Zone.png)</li> </ul> </ul> </ul> 
                    
                    **CSVファイルとExcelファイルのコンテキスト**
                    
                    ** **
                    
                    **複数列のコンテキスト情報がバイリンガル****Excelファイルからインポートできるようになりました。**
                    
                    &nbsp;
                    
                    翻訳者へコンテキスト情報を含む複数列を表示させるためには、ファイルインポート設定で選択できます。
                    
                    各列のコンテキスト情報は別々の行に表示されます。
                    
                      *   * [<img class="  wp-image-5522 alignnone" src="/wp-content/uploads/2015/11/context.png" alt="context" width="694" height="412" data-id="5522" />](/wp-content/uploads/2015/11/context.png)**新言語** 
                            次の言語を追加しました：
                            
                              * アラビア語（アルジェリア）
                              * 英語（レバノン）
                              * 英語（サウジアラビア）
                              * グリーンランド語
                            
                            &nbsp;
                            
                            &nbsp;
                            
                            **Eメールテンプレートのための新マクロ：{project.internalId}**
                            
                            [マクロリスト](http://wiki.memsource.com/wiki/Template_macros)に新マクロが追加されました。Eメールテンプレートで使うことができます。
                            
                            {project.internalId}により、プロジェクトの上部に表示される内部用プロジェクト番号を表示させることができます。[<img class="aligncenter size-full wp-image-5523" src="/wp-content/uploads/2015/11/project-id.png" alt="project id" width="491" height="136" data-id="5523" />](/wp-content/uploads/2015/11/project-id.png)</li> </ul> </li> </ul> </ul> 
                            
                            **ヘブライ語とアラビア語の用語認識を改良**
                            
                            アラビア語とヘブライ語の代表的な接頭辞をもつ単語の用語ベースの認識が改良されました。
                            
                            &nbsp;
                            
                            **API**
                            
                            新たなAPIが追加されました。
                            
                              * transMemory/getRelatedProjects
                            
                            特定のTMが使用されているプロジェクトの一覧取得
                            
                              * splitFileBySpecificRange
                            
                            特定の文節の後でジョブを分割
                            
                            TASK APIによって、あらたな選択パラメーターがSearch Segmentに追加されました。
                            
                            maxSegments
                            
                            maxSubSegments