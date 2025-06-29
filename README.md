# プロジェクト概要
C言語でshellを再実装した。
# 実装機能
・リダイレクト(`<`, `>` , `>>`)  
・heredoc(`<<`)  
・パイプライン(`|`)  
・shell組み込みコマンドの実装  
  - `cd`  
  - `echo`  
  - `env`  
  - `exit`  
  - `export`  
  - `unset`  
  - `pwd`  
・シグナル処理（Ctrl+C, Ctrl+D, Ctrl+\）  

# 実行方法
```
git clone https://github.com/karai-X/pusw_swap.git
```
```
make
```
```
./push_swap 5 4 1 3 9
```
## 入力
./push_swap (正の整数)  
## 出力
並び替えるための操作が出力される。
## 実行例
```
./push_swap 5 4 1 3 9
```
出力
```
pb  
ra  
ra  
ra  
pb  
ra  
sb  
pa  
ra  
pa  
ra  
```
# Visualizer
https://github.com/user-attachments/assets/86ae43b5-371b-46be-95aa-6ab595fa1bdb


