# ac_detector

* 過去コンテストの問題をACしたら自動tweet
** hakusye アカウント
* 定期的に登録者同士でスコアを競い合う
** 1時間に一回
** 
*
*

1. atcoderのユーザーidおよびtwitterアカウントを連携したデータを登録
2. 以下の処理を定期実行
    1. APIを叩いて提出一覧を取得する
    2. 提出一覧から新規ACを抽出し、tweetの内容に反映させる
    3. 自動tweet(ここまで1時間)
    4. 参加者同士の新規AC数などを比較して
    5. 5人以下でランキング
3. ユーザ追加のGUI実装

## AWS構成図

* [draw.io](https://app.diagrams.net/)で構成図を書く


