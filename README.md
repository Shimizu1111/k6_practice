# k6メモ

## 負荷テストコマンド
* 負荷テストの実行
```sh
k6 run main.js
```

* 各オプション
  * -vus: APIへの同時接続人数
    * --vus 5
  * -duration: APIへのリクエストの実行時間
    * --duration 5s
  * --iteration: シナリオを繰り返す回数
    * --iterations 10