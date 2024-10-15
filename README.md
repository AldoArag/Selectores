<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors</title>
    <style>
        * {
            font-family: monospace !important;
        }
        body {
            font-size: 22px;
        }
        h1, h2 {
            color: blue;
        }
        p {
            color: red; 
            color: blue; 
            color: green; /* Solo este color se aplicará */
        }
        button, input, textarea, select {
            font: inherit;
        }
        .gray {
            color: gray;
        }
        #second {
            font-style: italic;
        }
        .highlight {
            text-transform: uppercase;
            background-color: gold;
        }
    </style>
</head>
<body>
    <header>
        <h1>CSS Selectors</h1>
    </header>
    <main>
        <article>
            <h2>Article 1</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Numquam cumque voluptatum tempore officiis deserunt officia, molestias tenetur tempora. Numquam assumenda eligendi ipsam ut quibusdam ex autem placeat deleniti hic optio?</p>
        </article>
        <article>
            <h2>Article 2</h2>
            <p id="second" class="gray">Iste, possimus, delectus blanditiis, in dolores voluptatem culpa officia quae eius consequatur suscipit optio cum hic. Architecto ipsum rem accusamus! Quaerat repellendus <span class="highlight">nihil</span> ratione tenetur voluptas veritatis, sunt nesciunt rem.</p>
        </article>
        <article>
            <h2>Article 3</h2>
            <p class="gray">Iste, possimus, delectus blanditiis, in dolores voluptatem culpa officia quae eius consequatur suscipit optio cum hic. Architecto <span class="highlight">ipsum</span> rem accusamus! Quaerat repellendus nihil ratione tenetur voluptas veritatis, sunt nesciunt rem.</p>
        </article>
    </main>
</body>
</html>

<style>
    p { color: red; 
    color: blue; 
    color: rgb(13, 231, 13); }
   </style>
