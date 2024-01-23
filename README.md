# Pro2kakusin

プログラミング１について

概要

表計算の一部と記録ができるプログラミングです。データが複数ある時にエクセルなどではセルの移動などがあるが、for文を用いたことで、数値だけ打てばよいようにしました。

なぜ作ったのか

私生活で多くのデータに触れることがあり、毎度エクセルに打ち込むことがとても大変だったため、作りました。実際使ってみて、もう少し機能があるととても便利だと思いました。

入力と出力

入力は、データの個数やデータを入れます。入れたデータに対して知りたい情報を選び、入力します。出力はデータを表で表したものと知りたい値（一部）が分かります。

工夫した点

工夫した点は、多くのinput文でいろいろな処理をすることを可能にしたことです。



プログラミング２について

概要

ナンプレをnumpyで作成しました。ナンプレのルール同様に９＊９マスに１～９の数字を入れていくようにしました。また、３回間違えるとゲームオーバーになります。問題は、自分が考えたものや自分が解いてよいと思ったものを利用しています。

なぜ作ったのか

自分の私生活で少し時間にゆとりができたときに頭を動かすという意味で行っており、今回難しく作ることでより楽しさと頭の運動に良いと考えたからです。

入力と出力

まず問題が出てきます。空いている部分を0表現しています。そのため、数字を入れるのは0の部分です。input文で何行目かと何列目かを聞いてくるので、分かったところからその座標を書き、その数字を入れます。このときの座標は、indexの座標ではなく、純粋に上から何行目で、左から何列目かです。数字を入れていき、0がなくなったらゲームクリアです。合計3回間違えるとゲームーオーバーです。

工夫した点

プログラミング部分ではないが、ナンプレの問題を作ることです。とても大変で、とても時間がかかりました。工夫した点ではないのですが、最初の座標は指定したので、リストのindex量がとても多いことです。


プログラミング3について

概要

Open cv2で画像一致度調査を作りました。2枚の写真を選択することで、2枚の写真の一致度が分かります。2枚の写真のサイズを統一して、赤・青・黄いろの割合がその100＊100の画素一つ一つ比較し、だれだけ等しいかを割合にして表示します。もし、自分の写真を用いたい場合はzipファイルに圧縮して、google driveにアップロードします。つぎに、全体に公開を設定し、URLをコピーします。最後に、URLの最後から2番目の「/」で囲まれている部分を最初の「d=」のところに入れれば自分の好きなファイルでできます。最初に入っている写真はどれとどれを選んでも大体0％になります。

なぜ作ったのか

写真の比較をすることが面白そうと感じたからです。また、前期の時に同様にプログラミングを作成するような課題が出たときに調べて出てきたけれど、そのプログラミングが一つも理解できなかったため、あきらめてしまったので、今回は知識があるから作ろうと思ったからです。

入力と出力

3つの動作をするプログラミングがあります。１つ目は写真のアップロード用です。二つ目は写真を表示するプログラミングです。３つ目は２枚の写真の一致度の計算してくれるプログラミングです。2つ目のプログラミングの結果を見て、2枚の写真を選び、最後のプログラミングでファイル名を2つ書くことで比較された写真を2枚表示し、一致度が出ます。

工夫した点

2個目のプログラミングで表示を授業で下書き方で行ったことと多くのファイル追加したこと、統一するサイズを少し大きくすることでより詳しい一致度を出すことができたことです。
