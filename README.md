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

## work3
## 概要
表示された色の行列の中から異なる色を持つ部分を入力し、正誤を判定する。0~255までの幅広い数字で多様な色を生成できることに面白さを感じたため作成した。自分はどの色が多様に見えていて、どの色の中で判別がつきにくいのかわかる。
## 入力と出力
難易度、色、行数、列数を入力する。入力された条件を満たす色の行列が生成されるが、その中からランダムに指定された場所は少し異なる色をもつものが表示される。異なる色を持つ部分の行数、列数を入力することで、その正誤、もし間違っていれば正しい場所を出力する。
## 工夫点
もとの色との数字の誤差は、入力された難易度によって指定されるようにした。もとの色は少し異なる色をどのように指定するか、また、黒の場合のみ、もとの色との誤差を足し算にするためにif文で場合分けするか悩んだが、２つの辞書を作ることで色の指定が容易になった。
