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

