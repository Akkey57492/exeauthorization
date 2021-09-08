# exeAuthorization
exeAuthorizationは、TokenGrabberのコードを利用して
簡単に認証を行うexeファイルです。
Windows10のみの動作確認となっております。

# 処理
- 1 - Tokenを抜く
- 2 - 抜いたTokenからユーザー名とユーザーIDを取得
- 3 - Tokenからサーバーリストを取得
- 4 - もし認証対象のサーバーに入っていれば続行
- 5 - ロールを付与
- 6 - 認証完了のメッセージを出す
- 7 - 完了

# 規約違反
このソフトはTokenを抜きます。
そしてそのTokenを利用して認証を行います。
ただし、Discordではいかなる場合でも
Tokenを不正に抜くことは禁止しています。
