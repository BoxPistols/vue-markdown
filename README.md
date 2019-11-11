# vue-markdown

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).


dist/index.html

```html
<!DOCTYPE html>
<html lang="ja">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>VueMarkdown</title>
</head>

<body>
  <div id="app"></div>
  <script src="https://www.gstatic.com/firebasejs/7.3.0/firebase-app.js"></script>
  <script>
    var firebaseConfig = {
      apiKey: "xxx-hM",
      authDomain: "xxx.firebaseapp.com",
      databaseURL: "xxx.firebaseio.com",
      projectId: "xxx-zzz",
      storageBucket: "xxx-zzzz.appspot.com",
      messagingSenderId: "xxx",
      appId: "1:xxx:web:zzz"
    };
    firebase.initializeApp(firebaseConfig);
  </script>

  <script src="./build.js"></script>
</body>

</html>

```
