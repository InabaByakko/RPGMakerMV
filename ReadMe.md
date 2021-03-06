#RPGツクールMV対応プラグイン

RPGツクールMVで動作するプラグイン(JavaScript)を置いています。どうぞご自由にお使いください。  
一部のプラグインは、[ブログ](http://triacontane.blogspot.jp/)にて詳細な紹介を行っています。  
また、新しいプラグインを[ツイッター](https://twitter.com/triacontane)で告知する場合があります。  
These plugins(JavaScript) are for RPG Maker MV.  

##更新履歴 Update record

###2016/02/14 : 時刻と天候プラグイン[Chronus.js](https://raw.githubusercontent.com/triacontane/RPGMakerMV/master/Chronus.js)を修正しました。  
1. アナログ時計を表示する機能を追加しました。  
2. 現実の時間をゲーム内に反映させる機能を追加しました。  

###2016/02/14 : 起動オプション調整プラグイン[SetupOptionCustomize.js](https://raw.githubusercontent.com/triacontane/RPGMakerMV/master/SetupOptionCustomize.js)を追加しました。  
1. MVの起動オプション（URLクエリパラメータ）を制作者側で制御できます。  

###2016/02/14 : Web実行のテストプレー防止プラグイン[BugFixWebPlayTest.js](https://raw.githubusercontent.com/triacontane/RPGMakerMV/master/BugFixWebPlayTest.js)を追加しました。  
1. Web実行時にURLに?testと入力して実行することで誰でもテストプレーできてしまう問題を修正。  

###2016/02/13 : 戦闘中顔グラフィック表示プラグイン[BattleActorFaceVisibility.js](https://raw.githubusercontent.com/triacontane/RPGMakerMV/master/BattleActorFaceVisibility.js)を修正しました。  
1. 他のプラグインと併用できるように、ウィンドウの表示位置を調整する機能を追加。  

###2016/02/13 : フキダシウィンドウプラグイン[MessageWindowPopup.js](https://raw.githubusercontent.com/triacontane/RPGMakerMV/master/MessageWindowPopup.js)を修正しました。  
1. 並列処理のイベントが存在するときにポップアップ設定がクリアされてしまう問題の修正。  
2. ウィンドウの表示位置を下に表示できる設定を追加。  

###2016/02/11 : ステート自動付与プラグイン[AutomaticState.js](https://raw.githubusercontent.com/triacontane/RPGMakerMV/master/AutomaticState.js)を追加しました。  
1. 条件を満たしている間、指定したステートを付与します。  

これより以前の履歴は[こちら](./UpdateRecord.md)をご参照ください。  

##プラグイン一覧 Plugin list
[こちら](./PluginList.md)で公開しています。  

##使い方 How to use

###ダウンロード方法
まとめてダウンロードするには、[トップページ](https://github.com/triacontane/RPGMakerMV)の「Download ZIP」ボタンからZipファイルをダウンロードできます。  
個別にダウンロードするには、[こちら](./PluginList.md)からファイルを選択して「右クリック」→「名前を付けてリンク先を保存」です。*ファイル名は変更しないでください。*  

###プロジェクトへ適用するには
プロジェクトフォルダの「\js\plugins」以下にJSファイルを配置して、RPGツクールMVのプラグイン管理（F10）から有効化してください。  
使用前に「ヘルプ」ボタンから使い方を確認してください。  
イベントテストから実行するプラグインを使う場合は、実行前に「プロジェクトの保存」を行ってください。  

###制御文字について
全てのプラグインにおいて「プラグインコマンド」および「メモ欄への記述」のパラメータには*制御文字*が利用できます。  
制御文字の書式は文章の表示と同じです。変数やアクターの名前などを動的に設定できるのでぜひご活用ください。  

###問題が発生した場合
バグや予想外の動作を発見した場合、以下の手順で再確認してください。  

1. プラグインを再ダウンロードして確認する。  
2. 新規プロジェクトに当該プラグインのみを有効にして確認する。  

それでも問題が解決しない場合、下記の作者連絡先までご一報ください。  
差し支えなければ、プロジェクト一式をどこかにアップロードして頂けると、原因の特定が早まります。  
ただし、解決をお約束することはできません。  

##リクエストや要望について About request
随時、受け付けています。ツイッターやブログのコメント、GithubのIssues等を通じてご一報ください。  
ただし、対応可否や対応時期については一切お約束できません。  
要望を出すことも、それを断ることもお互いの自由であり、余計な気遣いは不要と認識しています。  

##作者連絡先 Contact information
トリアコンタン(triacontane)  
[Blog]    : <http://triacontane.blogspot.jp/>  
[Twitter] : <https://twitter.com/triacontane>  
[GitHub]  : <https://github.com/triacontane/>  

