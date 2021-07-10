# webpack_note
how to use Webpack Introductioon

<!-- webpackの起動 -->
<!-- まずはnpmを起動 -->
npm init -y /  yarn init -y


<!-- webpackのローカル　　webpack-cliも　　　インストール -->　
npm install webpack  webpack-cli --save-dev / yarn add webpack webpack-cli --dev

これからnpx webpackで処理が実行されるようになる


webpack.config.jsを用意する/これが、webpackの設定ファイルになる（ゲキ難)

[webpack.config.js]
  const path = require('path');
  
  module.exports= {
<!--     モードの指定をすることができる。developmentだと見やすい状態に、productionがデフォルトで圧縮して処理されているもの -->
  　　　　mode: 'development',
      
      
    context: __dirname + "/src" ,
    entry:
  }
