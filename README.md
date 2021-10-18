# asm-training

Sandbox project for C and Assembly language

# how to compile

## C言語からアセンブリ言語へのコンパイル
gccコマンドで-Sオプションを指定する。  
これにより、アセンブリ言語に変換した状態でコンパイルが停止する。

ctoasm.shの内部ではgcc -Sを使って対象のソースをコンパイルする。
```
./ctoasm.sh
```

## アセンブリ言語プログラムから機械語へアセンブルする
add.sがアセンブリ言語プログラムとして、下記のasコマンドを実行する

```
as -o add.o add.s

```