 # MAC(M1)の初期化

  全てのデータを移行するだけならこの作業は必要ありません。[こちら](https://support.apple.com/ja-jp/HT204350)

 ---

 参考動画

 [M1 Macは初期化＆再インストール方法が違う](https://www.youtube.com/watch?v=VsYi4W7hkpY)

 初期化する間にやっておくべきこと

 [アップル公式](https://support.apple.com/ja-jp/HT201065)

 [【保存版】正しいMacの完全初期化方法 Macを売る前にやること](https://macgarage.jp/mac-initialize/)

 ---

1. 自分のパソコンを整理整頓する
  
   - [不必要なアプリケーションのアンインストール](https://www.lifehacker.jp/article/206045remember-to-delete-and-unlink-your-accounts-before-dele/)
   - 画像、動画はハードディスクに保存しよう(TOSHIBA External USB 3.0 MediaのHDDを使用しているが現在のmacでは使用不可😭不便)
   他の人も同じことが起きているM1チップのせいではないのかも。[こちら](https://www.buffalo.jp/support/faq/detail/1199.html)
   ついでにmacの悪口。iphoneの遠隔操作ができるツールが全然M1に対応してないからやりたいことができない。最近対応してないツール多すぎて辛い。nreal airもアップル製品の対応が微妙やし、外部ストレージ使えんし、
   次はwindows買います。
   - デスクトップを整理(必要なプロジェクトをgithubなどで管理してデスクトップからは削除)

2. バックアップを作成
   
   - [いざという時、元に戻せるように別のハードディスクにtime machineでバックアップ](https://support.apple.com/ja-jp/mac-backup)

3. 機密情報管理
   
   - パスワード類は全てアナログで管理できるようにしておく(暗号化またはhash化したzipファイルをgoogledriveに保存でもいいかも)[メモ帳](https://news.allabout.co.jp/articles/o/27889/)

   - [safariのパス](https://br.atsit.in/ja/?p=66244)、[google chromeのパス](https://yoshitechblog.com/google-chrome-password-information-confirmation)、[braveのパス](https://lv73.net/brave-password-control-where/)、[パソコンで管理しているパス(キーチェーン)](https://support.apple.com/ja-jp/HT211145#:~:text=Safari%20%E3%81%A7%E4%BF%9D%E5%AD%98%E6%B8%88%E3%81%BF%E3%81%AE%E3%83%91%E3%82%B9%E3%83%AF%E3%83%BC%E3%83%89%E3%82%92%E8%A1%A8%E7%A4%BA%E3%81%99%E3%82%8B&text=%E3%80%8CSafari%E3%80%8D%E3%83%A1%E3%83%8B%E3%83%A5%E3%83%BC%E3%81%8B%E3%82%89%E3%80%8C%E7%92%B0%E5%A2%83,%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%82%82%E3%81%A7%E3%81%8D%E3%81%BE%E3%81%99%E3%80%82)

   - [保存されたパスワードを一括エクスポートする方法](https://atmarkit.itmedia.co.jp/ait/articles/2006/03/news021.html#:~:text=%E3%83%91%E3%82%B9%E3%83%AF%E3%83%BC%E3%83%89%E3%82%92CSV%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%81%AB%E4%BF%9D%E5%AD%98%EF%BC%88%E3%82%A8%E3%82%AF%E3%82%B9%E3%83%9D%E3%83%BC%E3%83%88%EF%BC%89%E3%81%99%E3%82%8B%E3%81%AB%E3%81%AF,-Chrome%E3%81%AB%E4%BF%9D%E5%AD%98&text=%E3%81%82%E3%82%8B%E3%81%84%E3%81%AFURL%E3%81%A8%E3%81%97%E3%81%A6%E3%80%8Cchrome%3A%2F%2F,%E3%82%A8%E3%82%AF%E3%82%B9%E3%83%9D%E3%83%BC%E3%83%88%EF%BC%BD%E3%82%92%E3%82%AF%E3%83%AA%E3%83%83%E3%82%AF%E3%81%97%E3%81%BE%E3%81%99%E3%80%82)

  ※ エクスポートしたCSVファイルは googleとbraveは共通のフォーマット,safariは少しフォーマットが違うので注意(エクスポートしたCSVファイルはインポートもできる)

4. 必要なアプリケーションはスクショとっておくと良いかも(不必要なアプリケーションもあるので新しい環境では必要なものだけ再度インストールする方がいい)
  
  - 設定の確認（マウスなどのカスタム設定）の設定画面をスクショしておくと良いかも

  - 接続解除 (初期化したパソコンを再度自分で使用する場合は必要ない)

    iTunesからサインアウト

    iCloudからサインアウト

    iMessageからサインアウト

    Bluetoothデバイスの解除

1. macOSの再インストール（初期化）
  
  - M1マックは初期化手順が違うので注意！バグの原因になる
