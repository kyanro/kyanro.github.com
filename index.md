# 自己紹介
+ android アプリ開発者
+ スタンス
  + ローリスク(できればノーリスク)でローリターンを狙っていく
+ https://github.com/kyanro

# 作ったもの
## [折り返し翻訳辞書 ~日本語から日本語へ~ ](http://orikaeshi.com/%E8%81%9E%E3%81%8F%E3%81%AF%E4%B8%80%E6%99%82%E3%81%AE%E6%81%A5%E3%80%81%E8%81%9E%E3%81%8B%E3%81%AC%E3%81%AF%E4%B8%80%E7%94%9F%E3%81%AE%E6%81%A5)
+ 日 -> 英 -> 蘭 -> 伊 -> 日 と連続で翻訳をかけることで面白い言葉に翻訳するサイト
+ マッシュアップアワード11への応募作品
  + android アプリによるプロトタイプの作成と、Webサービス化時のサーバ側Apiを担当
  + Devices & Cloud 賞 (日本マイクロソフト株式会社)受賞
+ まさかのTwitterトレンド1位獲得！
+ NHKのつぶやきビッグデータにちょろっと取り上げられた！
+ 他各種媒体による紹介多数

#### 使った技術
+ .NET MVC, Entity Framework, Azure Web Sites



## にゃんこスターター
+ 朝一番で猫の画像がみたかったので作成
  + [猫の動画を見るとやる気が出る](http://news.indiana.edu/releases/iu/2015/06/internet-cat-video-research.shtml) らしいのであやかりたかった
+ 公開しないだろうと思って作っていたこともあり色々とあれなのでコード非公開
+ 実際の画面は[こんな感じ](img/nyanco_starter.png)

#### 使った技術
+ 通常のandroidアプリ
+ 犬はないの？といわれたときに、「僕は猫派なので」と、はっきり言い返すための心構え


## ステルスミニ四駆
+ [自衛隊のステルス機ネタ](https://www.google.co.jp/search?q=%E7%99%BE%E9%87%8C%E5%9F%BA%E5%9C%B0%E8%88%AA%E7%A9%BA%E7%A5%AD+%E3%82%B9%E3%83%86%E3%83%AB%E3%82%B9&espv=2&biw=1863&bih=1054&source=lnms&tbm=isch&sa=X&ved=0ahUKEwijv4HtpqDJAhWIlJQKHUQGDlkQ_AUICCgD#tbm=isch&q=%E7%99%BE%E9%87%8C%E5%9F%BA%E5%9C%B0%E8%88%AA%E7%A9%BA%E7%A5%AD+fx+%E3%82%B9%E3%83%86%E3%83%AB%E3%82%B9+)にインスパイアされて開発
+ コンデレ時はタイヤのみを展示
+ ステルス看破アプリを通してみることで、ステルスを見破るというコンセプト
+ [実際のコンデレ出展時](https://twitter.com/mini4wd/status/639287365370970112/photo/1)
+ [これ](img/stealth_1.png)が[こうなる](img/stealth_2.png)
+ Vuforia のライセンスをちゃんと調べてないのと、Vuforiaのキーが埋め込んであるのでコード非公開

#### 使った技術
+ Unity, Vuforia, ステルスネタに気づいてもらう力



## 浮かび上がるユニティちゃんと夕立
+ ARアプリの練習として作成
+ [unityちゃんを召喚したかった](img/AR_unity-chan.png)
+ [夕立を召喚したかった](img/AR_yudachi.png)
+ [偶然ローソンで4枚のクリアファイルを手に入れた](https://www.google.co.jp/search?q=%E8%89%A6%E3%81%93%E3%82%8C+%E3%83%AD%E3%83%BC%E3%82%BD%E3%83%B3+%E3%82%AF%E3%83%AA%E3%82%A2%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB&espv=2&biw=1863&bih=1054&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjGw6nNq6DJAhXBKJQKHbkIDWgQ_AUIBigB)ので何かしようと思ったっぽい？
+ Vuforia のライセンスをちゃんと調べてないのと、Vuforiaのキーが埋め込んであるのでコード非公開

#### 使った技術
+ Unity, Vuforia, 偶然を装う演技力



## [ツイッターリスト Reader](https://github.com/kyanro/TwitterListReader)
+ ツイッターの公式クライアントではリストが奥に追いやられていたので、リストを使いやすくしたかった
+ RxJavaとRxAndroid、およびandroid のセンサーを利用したアプリ制作の練習として作成
  + 傾きセンサーを利用して、傾けるとリストが流れるようにした

#### 使った技術
+ RxJava, RxAndroid
+ androidのセンサー類
+ スクロールさえ面倒なのかと思われても折れない心の持ち方



## [ミニッツリピーターアラーム](https://github.com/kyanro/minute_repeater_alarm)
+ 電子的なミニッツリピーターが作りたかった
+ 通常のタイマーアプリだが、[ミニッツリピーター](https://ja.wikipedia.org/wiki/%E3%83%AA%E3%83%94%E3%83%BC%E3%82%BF%E3%83%BC_%28%E6%99%82%E8%A8%88%29)のように、バイブレーションのパターンで時間がわかるようにした
+ android のAlarmManager と NotificationManager 利用の練習として作成

#### 使った技術
+ AlarmManager, NotificationManager
+ ミニッツリピーターを電子的に再現してなにかいいことあるの？といわれても折れない心の持ち方



## [電子郵便将棋](http://mailshogi.azurewebsites.net/intro/)
+ サーバを介してメールの送受信を行い、一日一通にメールを制限することで、郵便将棋のいいところ(情緒があるところ)を再現した作品
+ マッシュアップアワード10への応募作品
  + SendGrid賞受賞
+ サービス停止中

#### 使った技術
+ .NET MVC, Entity Framework, Azure Web Sites
+ SendGrid Api
