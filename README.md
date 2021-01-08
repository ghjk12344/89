<!doctype html>
<html>
<head>
<title>WEB1 - JAVASCRIPT</title>
<meta charset="utf-8">
<link rel="stylesheet" href="style.css">
<script>
function nightDayHandler(self){
var target = document.querySelector('body');
if(self.value === 'night'){
target.style.backgroundColor = 'black';
target.style.color = 'white';
self.value = 'day';

var alist = document.querySelectorAll('a');
var i = 0;
while(i < alist.length){
alist[i].style.color = 'powderblue';
i = i + 1;
}
} else {
target.style.backgroundColor = 'white';
target.style.color = 'black';
self.value = 'night';

var alist = document.querySelectorAll('a');
var i = 0;
while(i < alist.length){
alist[i].style.color = 'blue';
i = i + 1;
}
}
}
</script>
</head>
<body>
<h1><a href="index.html">WEB</a></h1>
<input id="night_day" type="button" value="night" onclick="
nightDayHandler(this);
">
<input id="night_day" type="button" value="night" onclick="
nightDayHandler(this);
">


  <div id="grid">
<ol>
  <li><a href="1.html">HTML</a></li>
  <li><a href="2.html">CSS</a></li>
  <li><a href="3.html">JAVASCRIPT</a></li>
</ol>
  <div id="article">
<h2>JAVASCRIPT</h2>
<p><a href="https://en.wikipedia.org/wiki/JavaScript">JavaScript (/ˈdʒɑːvəˌskrɪpt/)</a>,[6] often abbreviated as JS, is a programming language that conforms to the ECMAScript specification.[7] JavaScript is high-level, often just-in-time compiled, and multi-paradigm. It has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions.

Alongside HTML and CSS, JavaScript is one of the core technologies of the World Wide Web.[8] JavaScript enables interactive web pages and is an essential part of web applications. The vast majority of websites use it for client-side page behavior,[9] and all major web browsers have a dedicated JavaScript engine to execute it.

As a multi-paradigm language, JavaScript supports event-driven, functional, and imperative programming styles. It has application programming interfaces (APIs) for working with text, dates, regular expressions, standard data structures, and the Document Object Model (DOM). However, the language itself does not include any input/output (I/O), such as networking, storage, or graphics facilities, as the host environment (usually a web browser) provides those APIs.

JavaScript engines were originally used only in web browsers, but they are now embedded in some servers, usually via Node.js. They are also embedded in a variety of applications created with frameworks such as Electron and Cordova.

Although there are similarities between JavaScript and Java, including language name, syntax, and respective standard libraries, the two languages are distinct and differ greatly in design.
</p>
</body>
</html>
