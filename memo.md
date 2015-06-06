## 実際のコード

https://github.com/qzwpq/45deg-sezemi-2015-readable-code/commit/83bb858c2a6b1e637f04f84047b999b7c0744c35#diff-0364f57fbff2fabbe941ed20c328ef1aR8

```javascript
var filename = process.argv[2]; // argv = ["node", "app.js", filename, [id, id, ....]]
```

一見、配列の添字がなぜ2なのかわからない・・・と思ったところに、argvの内容の例をコメントで書いてくれていて、
読みやすかった。

jsで行末にコメントを入れるスタイルはあまり見かけないが、今回に関しては読みやすかった。
argvの内容がきになって詰まった瞬間に、すぐ後にargvの説明がコメントされていたから。

## 実際のコード

https://github.com/qzwpq/45deg-sezemi-2015-readable-code/commit/08850d2af205455981788e005a2062f92f667382#diff-0364f57fbff2fabbe941ed20c328ef1aR7

```javascript
var filename = process.argv[2]; // argv = ["node", "app.js", filename]
var contents = fs.readFileSync(filename, 'utf-8');
console.log(contents);
```

無駄がなく、やりたいことがダイレクトに伝わってくる記述だと感じました。
nodeに慣れている人ならprocess、fs、consoleの存在と役割は知っているだろうという前提で、
あとは変数の内容や意図が伝わる命名がされているからだと思います。

## 実際のコード

https://github.com/Sesta/s1513114-sezemi-2015-readable-code/commit/64cb35827cfa473eae03325b4a3399218e557a68

```javascript
var recipes = [
  'オムライス',
  '親子丼',
  '杏仁豆腐'
];
```

レシピが複数入っている何か（配列でしょうね）ということがひと目でわかる命名ですね。

## 実際のコード

https://github.com/Sesta/s1513114-sezemi-2015-readable-code/commit/1534a10e41c31c652b88b92111adb8b7b6104a78

```
recipe-data.js というファイルで
recipeData という変数が宣言されている。
```

ファイル名と変数名の対応関係がわかりやすい命名がされていて、リーダブルだと感じました。

## 実際のコード

