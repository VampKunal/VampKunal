<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>README Preview - Kunal Rai</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.5.1/github-markdown-dark.min.css">
  <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
  <style>
    body {
      box-sizing: border-box;
      min-width: 200px;
      max-width: 980px;
      margin: 0 auto;
      padding: 45px;
      background-color: #0d1117;
      color: #c9d1d9;
      font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif;
    }
    .markdown-body {
      background-color: #0d1117;
    }
  </style>
</head>
<body>
  <article class="markdown-body" id="content">
    Loading preview...
  </article>
  <script>
    fetch('readme.md')
      .then(response => response.text())
      .then(text => {
        document.getElementById('content').innerHTML = marked.parse(text);
      });
  </script>
</body>
</html>
