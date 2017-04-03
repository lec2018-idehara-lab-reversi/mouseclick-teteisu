# この章での課題

- [ ] 組み込み関数 mouseClicked の利用方法を理解する
- [ ] 組み込み変数 mouseX, mouseY の利用方法を理解する
- [ ] 画面座標系→論理座標系への変換を理解する
- [ ] 手番の変更方法を実装する

# mouseClicked 関数の記述
mouseClicked() 関数は、マウスがクリックされたときに呼び出される。この中で、組み込み変数 mouseX, mouseY を参照して、正しい場所の盤面を書き換えよ。

ヒント：画面座標系 (0-640, 0-640) から、論理座標系 (1-8, 1-8) への変換である。

# 手番の変更
手番は、黒（１）と白（−１）が入れ替わる。手番の変更をプログラム上で記述せよ。
