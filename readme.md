# Fanuc-uframe-create

## 概要

与えられた 4 点の位置データからユーザ座標を計算します。

## 引数

位置レジスタ番号 4 つと出力用のユーザ座標番号で計 5 つの引数を使用します。

### 引数 1

arg[1] = (X start point) Position Reg No.  
(X 軸始点)

### 引数 2

arg[2] = (X-axis direction point) Position Reg No.  
(X 軸上座標)

### 引数 3

arg[3] = (Y-axis direction point) Position Reg No.  
(Y 軸上座標)

### 引数 4

arg[4] = (Origin) Position Reg No.  
(座標原点)

### 引数 5

arg[5] = Set UFRAME No.  
セットするユーザ座標番号

## 更新履歴

## License

Released under the Apache 2.0 License.
