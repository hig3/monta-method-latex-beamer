monta-method-latex-beamer
=========================

sample of Monta (Gradually Uncovering) Method with LaTeX Beamer slides


LaTeXでPowerPointのようなスライドを作るためのdocument classである[LaTeX Beamer](https://bitbucket.org/rivanvx/beamer/wiki/Home) で, 空欄穴埋め式の handout と slide を簡単に作るためのマクロです. 空欄(後から見せる部分)を
```TeX
\hiddenbox{something}
```
でマークするだけで, 前の空欄から順に内容が表示されていきます.

LaTeX macro to create slides where important words are uncovered one by one and handouts with blanks to be filled.

言ってみれば, LaTeXで[もんたメソッド](http://d.hatena.ne.jp/keyword/もんたメソッド) (+穴あき配布資料)をやるためのマクロです.</p>

ただし, もんたメソッドと言っても, 片側からめくるアニメーションや効果音はPDFにはいってません. PDF Viewer の設定で, ページトランジションをワイプ, 効果音付きにすれば多少はそんな感じがするかも. っていうかページトランジションを3Dとかスライドとかの複雑なものにすると紙とポストイットのメタファーが完全に消え去りそう.

Demo http://www.a.math.ryukoku.ac.jp/~hig/eproj/latex-beamer-monta/
