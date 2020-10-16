# Typography CSS library
**Author:** *Ondřej Neduchal*
## Demo site
(http://OndrejNeduchal.github.io/typography1)** site for previews
## Dependecies
* https://fonts.google.com/specimen/Montserrat
* https://fonts.google.com/specimen/Lora?query=lora
## Implementation
```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">
    <link href="
        https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,500;&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;1,400;1,500&display=swap"
        rel="stylesheet">
</head>
```
## Usage
This is CSS typography stylesheet for online blog with images, navigation through all your blogs is included.
* ul/ol
* strong
* pre
* blockquote
* cite
* q
* mark
* a
* m
* p
* h2, h3, h4, h5, h6 (**h1** is part of tag header, other use of **h2** need to be part of tag aside)
## Components
### Body
```
<body>
    <div>
        <header></header>
        <main></main>
    </div>
    <footer></footer>
</body>
```
### Header
```
<Header>
        <figure>
            <img src="./.../your_header.img" alt="Description of image">
        </figure>
        <time>date of your article</time>
        <H1>Header of your article</H1>
        <p>Short description of your article</p>
</Header>
```
### Main
```
<main>
    <article>
        <h2>Header</h2>
        <p>Paragraph text</p>
        <h3>Other header</h3>
        <p>Paragraph text</p>
        </article>
    </main>
```
### Aside
```
<aside class="extended">
    ...
</aside>
```
### nav
```
<nav class="navigation">
    <ul>
         <li><a href="">other content</a></li>
         <li><a href="">other content</a></li>
         <li><a href="">other content</a></li>
         <li><a href="">other content</a></li>
         <li><a href="">other content</a></li>
    </ul>
</nav>
```
### figure
```
<figure class="picture">
       <img src="./TRIP_06_GOPR7522.jpg" alt="image">
      <figcaption>This is image caption</figcaption>
</figure>
```
### Footer
```
<footer class="contact">
    <span>Autor name</span>
    <span>Contact info</span>
</footer>
```

