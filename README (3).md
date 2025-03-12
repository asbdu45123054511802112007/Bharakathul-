<!DOCTYPE html>
<html>
<head>
	<title>Page Title</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>Page Header</h1>
		<nav>
			<ul>
				<li><a href="#home">Home</a></li>
				<li><a href="#about">About</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="home">
			<h2>Welcome to Our Page</h2>
			<p>This is a sample page.</p>
		</section>
		<section id="about">
			<h2>About Us</h2>
			<p>We are a team of developers.</p>
		</section>
		<section id="contact">
			<h2>Contact Us</h2>
			<p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
		</section>
	</main>
	<footer>
		<p>&copy; 2023 Example</p>
	</footer>
</body>
</html>
```

CSS (in style.css file):

```
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #333;
	color: #fff;
	padding: 20px;
	text-align: center;
}

header nav ul {
	list-style: none;
	margin: 0;
	padding: 0;
	display: flex;
	justify-content: space-between;
}

header nav ul li {
	margin-right: 20px;
}

header nav a {
	color: #fff;
	text-decoration: none;
}

main {
	display: flex;
	flex-direction: column;
	align-items: center;
	padding: 20px;
}

section {
	background-color: #fff;
	padding: 20px;
	margin-bottom: 20px;
	box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
	font-size: 36px;
	margin-bottom: 10px;
}

h2 {
	font-size: 24px;
	margin-bottom: 10px;
}

p {
	font-size: 18px;
	margin-bottom: 20px;
}

footer {
	background-color: #333;
	color: #fff;
	padding: 10px;
	text-align: center;
	clear: both;
}
```
