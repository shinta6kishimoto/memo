## 変更前
独自ベクトルプロセッサ向けLLVMバックエンドの開発  
->ベクトルプロセッサではない、バックエンドが何をするのか不明瞭、キーワード:自動ベクトル化

## キーワード
RISC-V　LLVM　自動ベクトル化　独自プロセッサ　アセンブリコード生成　バックエンド　

## タイトル案
独自プロセッサのためのLLVMによる自動ベクトル化を用いたアセンブリコード生成バックエンドの開発

LLVMによる自動ベクトル化を用いた独自プロセッサのためのアセンブリコード生成バックエンドの開発

独自プロセッサ向けアセンブリコード生成のためのLLVMによる自動ベクトル化を用いたバックエンドの開発

独自ベクトル処理機能を備えたプロセッサ向け自動ベクトル化コンパイラの開発

## 英題
Development of backend using auto vectorization by LLVM to generating assembly code to [独自の英訳をどうするか] processors.

Development of automatic vectorization compiler for processors with original vector processing function.

## 要旨
組込み向けに独自にベクトル拡張したRISC-Vのアセンブリコードを生成するコンパイラの開発を目的として、コンパイラ基盤であるLLVMを用いた開発を行なう。  
LLVMはフロントエンド、バックエンドに分かれておりそれぞれソースコードの中間表現への変換、中間表現からアセンブリコードの生成を行っている。  
LLVMにはすでにRISC-Vのアセンブリコードを生成するためのバックエンドがあるためこれを改良し、独自のベクトル拡張命令を生成を実現する。  
