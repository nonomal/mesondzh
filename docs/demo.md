# 一个demo

## 结构

```shell
assets
.nojekyll
demo.md
docsify.md
index.html
plugin.md
README.md
_coverpage.md
_navbar.md
_sidebar.md
```

## index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>docsify 指南</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="description" content="Description">
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/lib/themes/vue.css">
</head>
<body>
  <div id="app"></div>
  <script>
    window.$docsify = {
      name: 'docsify 指南',
      repo: 'JoJo720/JoJo720',
      coverpage: true,
      loadSidebar: true,
      subMaxLevel: 3, //最大子标签级别
      maxLevel: 4, //最大标签级别

      loadNavbar: true,
      search: {maxAge: 86400000, paths: 'auto', placeholder: {'/': '搜索'}, noData: {'/': '找不到结果'}, depth: 4},
    }
  </script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
  <script src="//cdn.staticfile.org/docsify/4.11.3/plugins/search.min.js"></script>
  
</body>
</html>
```

