<!DOCTYPE html>
<html>
<head>
<title>패턴1</title>
<meta name="viewport" content="user-scalable=no,initial-scale=1,maximum-scale=1">
<style>
* { margin:0; padding: 0;}
body {width: 960px; margin: 0 auto; overflow: hidden; }
#menu { width: 260px; float: left;}
#section { width: 700px; float: right; }
@media screen and (max-width: 767px) {
body { width: auto }
#menu { width: auto; float: none; }
#section { width: auto; float: none; }
}
</style>
</head>
<body>
<div id="menu">
<ul>
<li>메뉴A</li> <li>메뉴B</li> <li>메뉴C</li>
</ul>
</div>
<div id="section">
<h1>Lorem ipsum</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
</div>
</body>
</html>
