# Atom設定メモ
自分のAtom設定をどのPCでも再現するためのメモ。
## 初期設定
#### ユーザとメールアドレスの設定
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
#### Push時のパスワードの入力省略
C:\Users\自分のユーザー名フォルダに_netrcというファイル(.netrcではないので注意)を作成
```
machine ホスト名1
login ログイン名1
password パスワード1
machine ホスト名2
login ログイン名2
password パスワード2
```

## install package
### git関連
99. git-plus

### vim関連
99. vim-mode-plus

### python関連

### markdown関連
99. markdown-scroll-sync

### 見た目関連
99. file-icons
99. auto-encoding

### パッケージインストールコピペ用リスト
```
apm install git-plus
apm install file-icons
apm install markdown-scroll-sync
apm install vim-mode-plus
apm install auto-encoding
```
## install themes

## カスタマイズ
99. proxy設定  
http://qiita.com/dskst/items/6153915b658433b02cd3
99. markdownプレビュー画面のフォント設定  
http://qiita.com/syoukoosu/items/3b6e7ad24659d93a4e8c
