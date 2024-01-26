# flask-todo
# 概要
これはPythonのFlaskの練習のために作ったリポジトリです。

参考にしたページは下記です。
https://tech-diary.net/flask-introduction/


# 作成フロー
base.htmlを用いて、遷移ページを複製し、それぞれについてBootStrapを用いて見た目を整えました。
またボタンを押したとき各ページに遷移するようにルーティングを実装しました。

またSQliteを用いて、簡単なデータベースを用意し、タスクを保存できるように実装しました。

# 使用方法
### 起動方法
vscodeなどでターミナルを開いて
下記コマンドを入力し、その後表示される"http://~"から始まるサイトにアクセスするとホーム画面が表示されます。
```
python app.py
```

### 画面
ホーム画面
CREATE NEW　TASKを押すとタスクを作成できる。
![スクリーンショット (95)](https://github.com/nara-tatsuki/flask-todo/assets/108511141/f6a6182d-9268-460f-bb74-a97ef08ca156)

必要項目を入力し、Createを押下するとタスク作成完了
![スクリーンショット (94)](https://github.com/nara-tatsuki/flask-todo/assets/108511141/f0756c6b-dfd6-467d-9e82-b275edc63317)

タスク作成後の画面
Updateで編集、Deleteでジョブの削除ができる
![スクリーンショット (93)](https://github.com/nara-tatsuki/flask-todo/assets/108511141/8fe946d3-e61d-4d8e-a75d-cf2b812347f6)


# 今後の展望
・ログイン機能
・Deleteの際に確認のタブを出すこと
・アラート機能