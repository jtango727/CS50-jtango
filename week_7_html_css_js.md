HTML, CSS, JavaScript

URL - Uniform Resource Locators

https://www.example.com/  

  - trailing slash indicates default home page

fully qualified domain name - example.com
www - server name
TLD - Top Level Domain - .com - commercial, .gov - government, etc.

http:// or https:// - dictates the protocol

******************************************************
<!DOCTYPE html>

<html lang="en">
  <head>
    <title>home</title>
  </head>
  <body style="text-align: center;">
    <header style="font-size: large;">
      John Harvard
    </header>
    <main style="font-size: medium;">
      Welcome to my home page!
    </main>
    <footer style="font-size: small;">
      Copyright &#169; John Harvard
    </footer>
  </body>
</html>

**********************************************************
<!DOCTYPE html>

<html lang="en">
  <head>
    <link href="styles.css" rel="stylesheet">
    <title>home</title>
  </head>
  <body class="centered">
    <header class="large">
      John Harvard
    </header>
    <main class="medium">
      Welcome to my home page!
    </main>
    <footer class="small">
      Copyright &#169; John Harvard
    </footer>
  </body>
</html>

*******************************************************
styles.css

.centered
{
	text-align: center;
}

.large
{
	font-size: large;
}

.medium
{
	font-size: medium;
}

.small
{
	font-size: small;
}

