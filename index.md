<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
</head>
<body>
  <h1>Hello World</h1>
<script id="jsbin-javascript">
document.querySelector('h1').addEventListener('click', (ev)=> {
  ev.target.innerText = Math.random();
})
</script>



<script id="jsbin-source-javascript" type="text/javascript">document.querySelector('h1').addEventListener('click', (ev)=> {
  ev.target.innerText = Math.random();
})</script></body>
</html>
