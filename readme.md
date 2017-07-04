## 背景
overwatchを起動したら，手動でLINEに「堕天降臨」スタンプを送ってお知らせしてた．
けど，3回くらいしたら面倒くさくなる，けど堕天スタンプは使いたいので，これらを解消するために開発

## アプリ名
overPLIN(overwacth playstaion LINE)

## 使用言語
Ruby(予定)

## 完成時の動作
PS4でoverwatch起動したら，堕天スタンプが自動で送信される

## 必要機能
- [ ] PSNにログイン
- [ ] 起動しているゲーム名の取得
- [ ] 指定したゲーム名(overwatch)になったらLINEAPI起動
- [ ] 指定したLINEルームにスタンプ送信(まずは文字列送信?)

## その他
- 悲しいことに[これベース](https://github.com/pintowar/psn_api_ar)で開発していたら，APIのURLが見つからない事態に．
早くも方向転換の余地がある?
- PSNのAPIが思いの外扱えないので，一旦更新をストップします(API扱えるようになってきたら，舞い戻ってきます)
代わりにLINEBOTを作る技術は手に入れたので，それを利活用してみます
