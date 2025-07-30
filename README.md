# CAMPUS-VOICE
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Campus Voice</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Campus Voice <span class="ml">ക്യാമ്പസ് വോയ്സ്</span></h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Posts</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <main>
    <section class="intro">
      <h2>Welcome to Campus Voice</h2>
      <p>A bilingual student magazine sharing voices from campuses across Kerala and beyond.</p>
    </section>

    <section class="posts">
      <h2>Latest Posts / പുതിയ ലേഖനങ്ങൾ</h2>
      <article>
        <h3>Campus Politics Today / ക്യാമ്പസ് രാഷ്ട്രീയത്തിന്റെ ഇന്നലെയും ഇന്നും</h3>
        <p>A critical look at how student politics shape society and education.</p>
        <a href="#">Read More</a>
      </article>

      <article>
        <h3>Voices of Freedom / സ്വാതന്ത്ര്യത്തിന്റെ ശബ്ദങ്ങൾ</h3>
        <p>Stories of protest, unity, and hope from university campuses.</p>
        <a href="#">Read More</a>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Campus Voice | Powered by Students</p>
  </footer>
</body>
</html>


body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f4f4f4;
  color: #333;
}

header {
  background: #003366;
  color: white;
  padding: 1rem;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2rem;
}

header .ml {
  font-size: 1.2rem;
  font-weight: normal;
  display: block;
}

nav {
  margin-top: 10px;
}

nav a {
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

main {
  padding: 2rem;
}

.intro {
  background: red;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  border-radius: 5px;
}

.posts article {
  background: white;
  padding: 1rem;
  margin-bottom: 1rem;
  border-left: 5px solid #003366;
  border-radius: 5px;
}

.posts a {
  text-decoration: none;
  color: #003366;
  font-weight: bold;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #003366;
  color: white;
}
