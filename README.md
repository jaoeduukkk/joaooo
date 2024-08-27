body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 2em;
}

h1 {
    font-size: 2.5em;
    margin-bottom: 0.5em;
}

h2 {
    font-size: 2em;
    margin-top: 1.5em;
}

img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
}

video {
    display: block;
    margin: 1em auto;
    max-width: 100%;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 1em;
}

.gallery img {
    width: calc(33% - 1em);
    flex-grow: 1;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
