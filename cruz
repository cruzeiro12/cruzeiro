<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog de Discussão sobre Atualidades</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77a6b1 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        #main {
            padding: 20px;
            background: #fff;
        }
        .post {
            border-bottom: 1px solid #ccc;
            padding-bottom: 20px;
            margin-bottom: 20px;
        }
        .post h2 {
            margin: 0;
        }
        .post p {
            line-height: 1.6em;
        }
        #comment-form {
            margin-top: 30px;
        }
        #comment-form input, #comment-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
        }
        #comment-form button {
            background: #333;
            color: #fff;
            border: 0;
            padding: 10px 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Blog de Discussão sobre Atualidades</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container" id="main">
        <article class="post">
            <h2>Título do Post sobre Atualidade</h2>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce ac ligula quam. Nullam at enim nec eros auctor vehicula. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae.
            </p>
        </article>

        <section id="comments">
            <h3>Comentários</h3>
            <!-- Comentários aparecerão aqui -->
        </section>

        <section id="comment-form">
            <h3>Adicione um Comentário</h3>
            <form id="form">
                <input type="text" id="name" placeholder="Seu nome" required>
                <textarea id="comment" placeholder="Seu comentário" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>

    <script>
        document.getElementById('form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const comment = document.getElementById('comment').value;

            const commentSection = document.getElementById('comments');
            const newComment = document.createElement('div');
            newComment.classList.add('comment');

            const commentName = document.createElement('h4');
            commentName.textContent = name;

            const commentText = document.createElement('p');
            commentText.textContent = comment;

            newComment.appendChild(commentName);
            newComment.appendChild(commentText);

            commentSection.appendChild(newComment);

            document.getElementById('form').reset();
        });
    </script>
</body>
</html>
