# vue-practice

コマンドの実行は`Git Bash` or `コマンドプロンプト`を用いて行う。  
1. windowsボタンを押して`Git Bash`と入力
1. GitBashを実行
1. 下記コマンドを任意のフォルダで実行
1. 

## プロジェクトの開発環境構築
1. Node.jsをインストール（[ダウンロードリンク](https://nodejs.org/ja/)）
1. `xx.xx.x LTS 推奨版`をダウンロード
1. ダウンロードしたインストーラーを実行（全部OKで進める）
1. エクスプローラーでvue-practiceフォルダを開く
1. フォルダアイコンが置いてある辺りを右クリック
1. `GitBashで開く`を選択
1. 下記コマンドを実行
```
git clone https://github.com/taiga533/vue-practice.git && cd vue-practice && pwd && echo "↑のフォルダをエクスプ
ローラーで開いてください"
```

### エディタをインストール
1. Visual Studio Codeをインストール（[ダウンロードリンク](https://code.visualstudio.com/)）
1. Download for Windowsを選択
1. ダウンロードしたインストーラーを実行（全部OKで進める）
1. 日本語化拡張機能を入れる[ダウンロードリンク](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ja)
1. Installボタンをクリック
1. Vue編集用拡張機能を入れる[ダウンロードリンク](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
1. Installボタンをクリック

基本的にVueはVisual Studio Codeで編集すると楽  
なので、VisualStudioCodeで vue-practice(このフォルダ)を開いておきましょう。
1. VisualStudioCodeを開く
1. 右上の`ファイル(F)`をクリック
1. `フォルダを開く`をクリック
1. `vue-practice(このフォルダ)`を開く

---
拡張機能を入れておくと`.vue`ファイルを色付けしてくれたり、  
jsの書き方がイケてないところを協調表示してくれる。



### 開発のためのコンパイルとホットリロードの実行
1. 下記コマンドを実行
```
npm run serve
```

(コマンド実行後の最後に出てくるURLの`Local: `をコピーしてブラウザに貼り付けると、開発してるページが開ける)
↑のコマンドを実行している間は`.vue`ファイルに加えた変更が、  
ページのリロードなしで反映される。

### 本番環境用の設定を利用したコンパイル
1. 下記コマンドを実行
```
npm run build
```

↑のコマンドを実行すると、成果物(サーバーに置くためのフォルダ)が`./dist`フォルダに生成されます。

### テストコードを実行
1. 下記コマンドを実行
```
npm run test
```

### jsファイルのLintと書き方がイケてない部分の自動修正
1. 下記コマンドを実行
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
