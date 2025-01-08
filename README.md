# Aula de Logica programacao 
Logica de programação 
<br> break  (quebra linha)
<h1> highlite </h1>(realcar) <h1>
<a href="https://www.mozilla.org/">aqui</a>

#Aulas 1


O documento segue a estrutura básica de um arquivo HTML:
<!DOCTYPE html>: Informa ao navegador que este é um documento HTML5.
<html lang="en">: Define o elemento raiz do documento e especifica o idioma principal como inglês (lang="en").
2. Cabeçalho (<head>)
A seção <head> contém metadados e configurações que não são exibidas diretamente na página.
<meta charset="UTF-8">: Define a codificação de caracteres como UTF-8, garantindo suporte para a maioria dos caracteres, incluindo acentos e símbolos especiais.
<title>: Define o título da página, que aparece na aba do navegador. Neste caso, o título é "My First Web Page".
<style>: Contém regras CSS para estilizar a página.

3. Estilo CSS (<style>)
Estilos são aplicados para controlar a aparência da página:
html { font-size: 22px; }:
Define o tamanho da fonte base como 22 pixels para o elemento <html>, afetando todos os textos da página.
body { background-color: #333; color: whitesmoke; }:
background-color: #333;: Define a cor de fundo do corpo da página como um tom escuro (cinza quase preto).
color: whitesmoke;: Define a cor do texto como um branco acinzentado (um tom suave de branco).

4. Corpo do Documento (<body>)
A seção <body> contém o conteúdo visível da página:
<h1>Hello World!</h1>:
Um cabeçalho de nível 1 que exibe o texto "Hello World!" em destaque.
<p>This is my first web page.</p>:
Um parágrafo de texto que exibe "This is my first web page.".

# Aula 2
Estrutura Geral
A estrutura do documento segue o padrão de uma página HTML básica, com uma declaração <!DOCTYPE html> no início para indicar ao navegador que o documento usa HTML5.

1. <html lang="en">
Define o elemento raiz do documento HTML, e o atributo lang="en" especifica que o idioma principal da página é o inglês.

Cabeçalho (<head>)
A seção <head> contém metadados e informações que não são exibidas diretamente na página, mas são importantes para navegadores e mecanismos de busca.

<meta charset="UTF-8">
Especifica a codificação de caracteres usada pela página (UTF-8), que suporta a maioria dos caracteres em diferentes idiomas.

<meta name="author" content="Dave Gray">
Declara o autor da página como "Dave Gray".

<meta name="description" content="This page contains all the things I am learning how to create as I learn HTML.">
Fornece uma breve descrição da página. Este conteúdo pode ser usado por mecanismos de busca como um resumo da página.

<title>My First Web Page</title>
Define o título da página, que aparece na aba do navegador.

<link rel="icon" href="html5.png" type="image/x-icon">
Define o favicon da página (ícone que aparece na aba do navegador). Aqui, a imagem html5.png será usada.

<link rel="stylesheet" href="main.css" type="text/css">
Faz referência a um arquivo CSS externo chamado main.css, que será usado para estilizar a página.

Corpo (<body>)
A seção <body> contém o conteúdo principal da página que é exibido no navegador.

<h1>Hello World!</h1>
Exibe o cabeçalho principal com o texto "Hello World!". A tag <h1> é usada para títulos de maior importância.

<p>This is my first web page.</p>
Exibe um parágrafo com o texto "This is my first web page.".

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="author" content="Dave Gray">
    <meta name="description" content="This page contains all the things I am learning how to create as I learn HTML.">
    <title>My First Web Page</title>
    <link rel="icon" href="html5.png" type="image/x-icon">
    <link rel="stylesheet" href="main.css" type="text/css">
</head>

<body>
    <h1>Hello World!</h1>
    <p>This is my first web page.</p>
</body>

</html>

# Aula 3 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="author" content="Dave Gray">
    <meta name="description" content="This page contains all the things I am learning how to create as I learn HTML.">
    <title>My First Web Page</title>
    <link rel="icon" href="html5.png" type="image/x-icon">
    <link rel="stylesheet" href="main.css" type="text/css">
</head>

<body>
    <h1>Hello World!</h1>

    <hr>

    <h2>I'm Ready to Learn HTML</h2>
    <p>This is my first web page.</p>

    <h3>My Daily Schedule</h3>
    <p>Let me tell you how:
        <br>&nbsp;&nbsp;&nbsp;...I learn more about web dev.
        <br>&nbsp;&nbsp;&nbsp;...I plan out my schedule.
        <br>&nbsp;&nbsp;&nbsp;...I use resources from <abbr title="Mozilla Developer Network">MDN</abbr>.
    </p>

    <hr>

    <h2>I Am Also Planning a Vacation</h2>
    <p>I've been working hard and <em>really need a getaway</em>.</p>
    <p>I live in <abbr title="Kansas">KS</abbr> so I want visit a beach.</p>

    <h3>Place I'd Like to Visit</h3>
    <p>I've heard good things about the Caribbean.</p>
    <p>I've heard good things about going here:</p>
    <address>
        Margaritaville Island Reserve Riviera Cancún<br>
        Bahia Petempich Puerto Morelos, Mexico<br>
        Colonia Morelos, México 77580
    </address>

    <!-- TODO: Add more places -->
    <h3>Place I Want to Avoid</h3>
    <p>Anywhere cold. <strong>No way!</strong></p>

    <hr>
    &lt;&lt;&lt; &copy; Dave Gray &gt;&gt;&gt;
</body>

</html>

Finalização
O fechamento de cada tag (</html>, </head>, e </body>) garante que a estrutura do documento esteja completa e bem definida.


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="author" content="Dave Gray">
    <meta name="description" content="This page contains all the things I am learning how to create as I learn HTML.">
    <title>My First Web Page</title>
    <link rel="icon" href="html5.png" type="image/x-icon">
    <link rel="stylesheet" href="main.css" type="text/css">
</head>

<body>
    <h1>Hello World!</h1>

    <hr>

    <h2>I'm Ready to Learn HTML</h2>
    <p>This is my first web page.</p>

    <h3>My Daily Schedule</h3>
    <p>Let me tell you how:</p>
    <ol>
        <li>...I learn more about web dev.</li>
        <li>...I plan out my schedule.</li>
        <li>...I use resources from <abbr title="Mozilla Developer Network">MDN</abbr>.</li>
    </ol>

    <hr>

    <h2>I Am Also Planning a Vacation</h2>
    <p>I've been working hard and <em>really need a getaway</em>.</p>
    <p>I live in <abbr title="Kansas">KS</abbr> so I want visit a beach.</p>

    <h3>Place I'd Like to Visit</h3>
    <ul>
        <li>
            <p>I've heard good things about the Caribbean.</p>
        </li>
        <li>
            <p>I've heard good things about going here:</p>
            <address>
                Margaritaville Island Reserve Riviera Cancún<br>
                Bahia Petempich Puerto Morelos, Mexico<br>
                Colonia Morelos, México 77580
            </address>
        </li>
    </ul>
    <!-- TODO: Add more places -->
    <h3>Places I Want to Avoid</h3>
    <dl>
        <dt>North Pole</dt>
        <dd>I hear this is <strong>cold</strong>!</dd>

        <dt>South Pole</dt>
        <dd>This is also cold.</dd>

        <dt>Mountain Tops</dt>
        <dd>These are also cold.</dd>
    </dl>

    <hr>
    &lt;&lt;&lt; &copy; Dave Gray &gt;&gt;&gt;
</body>

</html> #aula 4





