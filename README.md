# Prog2kakushin
# work1
## 概要
csvファイルを用いることで、広島市内のAEDのある場所、施設が分かるプログラム。普段生活していてAEDを見かけても特に気に留めることもないため、使いたいと思った時にどこを探せばよいのか分からないと思う。いざという時にパッと検索出来たり、どういった施設にあるのか（児童館、大学等）あらかじめ予習出来たらいいなと思い、プログラムした。
## 入力と出力
広島市内で、AEDを見つけたい場所、または施設名を入力する。
入力された場所周辺でAEDのある場所の名称と住所を返す。また、グラフを地図に見立てることによって、今回は広島市役所との位置関係を返す。
## 工夫点
AEDを探したいときに名称・住所で返されてもいまいち分かりにくいため、簡易地図で返すことを考えた。今回は広島市役所のみ簡易地図上に表示させたが、より多くの場所の緯度と経度さえ分かってプログラムしておけば、より分かりやすい地図になる。もともとは緯線と経線が書かれた地図があれば、それをグラフと重ねて表示させたかったが、使っても良い地図が見つけられなかった。

## work2
## 概要
絶対音感があるのかチェックするプログラム。昔音楽教室に通っていた時に、どの和音を引いているのか当てさせられるゲームをよくさせられており、あまりの難しさにかなり戸惑った。それを練習できるようなものがあればいいのに、と思っていたためこのプログラムを作った。
## 入力と出力
ランダムで生成された正弦波でできた単音、または和音が流れるため、自分が聴こえたと思った音階名を打ち込むことで正誤が返される。複数音の場合は、いくつの音が正解しているのか返す。
## 工夫点
７音での正弦波・音の生成は授業で行ったため、＃のつく音を加えた１２音の周波数を知らべ追加した。ランダムで生成された数字から辞書内の"A"~"G"の周波数までの変換はlistを使った。どこを発展させていいのか分からず単調なプログラムになった気がするので、もう少し機能を追加したかった。
