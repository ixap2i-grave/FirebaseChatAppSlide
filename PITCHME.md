### AndroidでFirebase周辺の技術を使って遊ぼう

for shinhuku-mokumoku32 @ixap2i

---


### だれ？

![Author](self.JPG)

@size[1em](- ixap2i(yama)\)

@size[0.8em](- メドケアというヘルステック系のスタートアップで働いています)


@size[0.8em](- Kotlin, AndroidStudioなどを触ってます)


---

### 今作っているもの
@size[0.8em](- FirebaseのAuthentication, Firestoreなどの技術を使ったチャットアプリ)


@size[0.8em](- 進捗率　FirebaseAuthenticationのセットアップ 70%)
@size[0.8em](			FirebaseStore周辺の調査 0%)


---

### Authenticationの大雑把なダイジェスト

@size[0.8em](FirebaseのAuthenticationから任意のユーザーを作る)

@size[0.8em](Firebase Auth Instanceを取得、createUserWithEmailAndPasswordなるものを使ってユーザー照合をする。)
@size[0.2em](DBからデータ取ったり整形作業などもないのでとてもラク)


![Code](code1.png)
---

### つまづきポイント

@size[0.8em](- 開発環境特有の依存性の解消(Firebaseのアプリを作る時に必要な部品をインポートする感じ Railsでいうgemfileに似ているかも)

@size[0.8em](- ViewとLogicを結びつけるためにxmlファイルにわちゃわちゃ記述をする, それぞれのタグの意味をわからずに実装していくと危険)

@size[0.8em](- 認証が通ったかと思いきや、メインロジックが起動しなくなったので内心半泣きになっていますww)
---

### ゆるーくがんばります

@size[0.8em](- 次回参加時に作っていきます)

@size[0.8em](- 個人開発とはいえ、そろそろ実装のロードマップを起こしたい)

@size[0.8em](- 質問や補足などありましたら下記にissueくださいー)
@size[0.8em](https://github.com/ixap2i/FirebaseChatApp)

