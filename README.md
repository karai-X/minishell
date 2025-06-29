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
git clone https://github.com/karai-X/minishell.git
```
```
cd minishell
```
```
make
```
```
./minishell
```
プログラム実行後は通常のshellと同じように操作可能
# デモンストレーション
https://github.com/user-attachments/assets/f0f2040a-944e-49de-aac4-07fec895184c
