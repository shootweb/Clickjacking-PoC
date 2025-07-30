# Clickjacking PoC
Just replace the URL in the HTML file with the website you want to check for Clickjacking. <br>
If the website loads when you open the HTML file, then it's vulnerable to Clickjacking. <br>
<br>

## HTML Code in the file

\<html>
\<head><title>Totally-Legit-Website.com</title></head>
\<body>
\<h1><center>Clickjacking PoC!</center></h1>
\<div class="overlay"></div>
\<iframe src="https://example.com/login" width="100%" height="100%"></iframe>
\</body>
\</html>
