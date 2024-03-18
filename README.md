# 課題9の提出
- Controller、Service、Mapperを利用してRead処理を作った
- 例外をハンドリングする処理を実装した

# 動作確認
## Getでリクエスト
- リクエスト[http://localhost:8080/users/1]したら、ID:1のユーザ情報を取得できた。ステータス200 OKであった。
![image](https://github.com/toshinarihonda/service/assets/154747585/4cf85fdb-b893-47d8-a282-6f34ade8460c)

- リクエスト[http://localhost:8080/users/100]したら、例外処理（UserNotFoundException）を発生させることができた。
![image](https://github.com/toshinarihonda/service/assets/154747585/8db591e0-7803-4fe9-8428-e611abb0f00a)



