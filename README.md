# Mandelbrot - マンデルブロー集合

mandelbrot.cの`#define`の  
`r0`,`i0` ：描画中心  
`range`   ：描画範囲（幅）
`nmax`    ：nの最大値  
`step`    ：ステップ数  
それぞれを調整することで、任意の位置でのマンデルブロー集合の座標情報を得られる。  
出力先は`data.txt`とすること。  
最後にgnuplotを用いて  
`$gnuplot png.gnuplot`  
で図を得られる。
