# 課題① 課題番号-プロダクト名
- 課題番号：js03_firebase活用川柳チャットアプリ.
- プロダクト名：「エンジニア向け学習中の人川柳」

## ②課題内容（どんな作品か）
- 初学者が、プログラミング学習の苦しみや喜びを、川柳（五・七・五）で吐露してストレス解消するチャットアプリ

## ③DEMO
- https://drive.google.com/file/d/1oqKlNEkoLsqQp69ZviKqrH3iDszY6ADZ/view?usp=sharing

## ④工夫した点・こだわった点
- 【工夫した点】
- 装飾を、管理画面に模して、背景をマトリックス風、文字や枠線をネオンサイン風にした。
- 川柳（五・七・五）を、「上五」「中七」「下五」の３つの欄に分け、各フレーズごとに考えながら打てるようにした。
- 数々の用語に慣れ親しむため、送信ボタン名は「デプロイ」にした。

## ⑤難しかった点・次回トライしたいこと（又は機能）
- 【難しかった点（未解決）】
- LINEスタンプのように選んだ画像を表示させたかったができなかった。
- 対処：当初は送信ボタンを押すと、chat画面上に「img01」とliのidが表示されていた。そこで、firebaseが「img01」を画像認識するためには、firebaseのstorageに「img01」の画像データ自体を格納すればよいのではと考え実際試したがダメだった。そもそもchromeのローカルストレージに画像認識されていない様子で、そうなると、画像はどの時点でアップロードするものなのか、混乱し思考停止した。
- 【次回トライしたいこと】
- ① スタンプのchat表示をできるようにする。
- ② レイアウトを整えて入力しやすくする。
- ③ ハンバーガーメニューで簡単なルール説明をつける。
- ④ 下書き保存機能を付ける。

## ⑥質問・疑問・感想、シェアしたいこと等なんでも
- 【感想】
- headや、bodyタグの冒頭は、ネオンサインやマトリックス風のサンプルコードのコピペなのですが、見づらいので、cssのことはcssファイルに移そうかどうか迷いました。時間的に、それをやると総崩れのリスクが高いと判断したため、今回はそのままにしました。すっきり見分けがつくような整理されたコードにするにはどうしたら良いのでしょうか…。
## 以上
