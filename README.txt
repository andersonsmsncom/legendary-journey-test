cd C:\Github\andersonsmsncom\legendary-journey-test

git status

notepad index.html

git add index.html

git status

git commit -m "create index.html"

--

--------------------------------------------------
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
--------------------------------------------------

git config --global user.email "andersons@msn.com"
git config --global user.name "Scott Anderson"

git commit -m "create index.html"

[main 662ac2d] create index.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

--

git status
git log

--

notepad app.js
notepad styles.cs

--
https://www.w3schools.com/html/html_examples.asp
--

[index.html]

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Document</title>
</head>

<body>
    <h1>Git Demo Page</h1>
    <script src="app.js"></script>
</body>

</html>

[app.js]
alert('HELLO THERE!!!');

--
git status
--

git add index.html app.js
git status

git commit -m "add app logic"
git log



<!DOCTYPE html>
<html lang="en">

<head>
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <h1>Git Demo Page</h1>

    <script src="app.js"></script>
</body>

</html>



styles.css
body {
    background-color: aquamarine;
}

h1 {
    background-color: purple;
}


git status

git add styles.css

REM git add .

