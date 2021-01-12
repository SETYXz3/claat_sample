# claat_sample
#### 導入方法(Mac)

##### 1. Go言語のインストール
###### インストール
```bash
$ brew install go
```

###### 環境変数の設定
```bash
$ export GOPATH=$HOME/Go
$ export GOROOT=/usr/local/opt/go/libexec
$ export PATH=$PATH:$GOPATH/bin
$ export PATH=$PATH:$GOROOT/bin
```

##### 2. claatのインストール
###### インストール
```bash
$ go get -u -v -x github.com/googlecodelabs/tools/claat
```
###### 確認
```bash
$ claat -h
```

##### 3. Googleドキュメントを使って作成
...省略

##### 4. GoogleドキュメントをMarkdownに変換
```bash
$ claat export {GOOGLE_DOCS_ID}

(初回はGoogleの認証が必要です。)
```
