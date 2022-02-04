# 🧑🏻‍💻Criando o projeto

## 📌Organizando o site

    🔹Ferramenta MOCKFLOW (montar o formato do site)

    🔹ADOBE COLOR (paleta de cores)

    🔹Fontes (baixar as fontes usadas - src: url('fontes/idroid.otf') format('opentype')

    🔹Escrever todo o conteúdo dentro das tags e com os devidos significados!


## 📌Estrutura Principal!


    <html>
        <head>
        </head>
        <body>
            <header>
            </header>
            <nav>
            </nav> 
            <main>
                </article>
                    <aside>
                    </aside>s
                </article>
            </main>
            <footer>
            </footer>
        </body>
    </html>

## 📌Tags utilizadas:
    🔹 &lt; header &gt;

    🔹 &lt; nav &gt;

    🔹 &lt; main &gt;

    🔹 &lt; article &gt;

    🔹 &lt; aside &gt;

    🔹 &lt; footer &gt;

    🔹 &lt; html &gt;

    🔹 &lt; h1 &gt;

    🔹 &lt; h2 &gt;

    🔹 &lt; h3 &gt;

    🔹 &lt; html &gt;

    🔹 &lt; p &gt;

    🔹 &lt; strong &gt;

    🔹 &lt; ul &gt;

    🔹 &lt; li &gt;

    🔹 &lt; html &gt;

    🔹 &lt; abbr &gt;

    🔹 &lt; a &gt;

    🔹 &lt; picture &gt;

    🔹 &lt; img &gt;

    🔹 &lt; link &gt;


# 🔰CSS:

- Regra:

    🔹@charset "UTF-8" 

        Especifica a codificação de caracteres utilizada da folha de estilo, onde "UTF-8" significa  Unicode Transformation Format.
- Imports:

    🔹@import url();

        Aqui foi importada a fonte do Google fonts

- Fonte baixada:

        @font-face {
        font-family: 'Android';
        src: url('fontes/idroid.otf') format('opentype');
        }

- Variáveis no CSS:

        São entidades definidas por desenvolvedores, contendo valores específicos para serem reutilizados ao longo do documento. Variáveis CSS permite um valor ser guardado em um lugar, então ser referenciado em muitos outros lugares.

        Ex.:

        🔹Definindo variaveis

        :root{
        --cor1: #c5ebd6;   (Definindo variável de cor)
        --font-android: 'Android', cursive;   (Definindo variável de fonte)
        }

        🔹Usando variaveis

        seletor {
            color: var(--cor1);
        }

- Seletores universais:
        Esta ferramenta faz a seleção de todos os elementos e aplica as propriedades de estilo!

        Ex.:
        * {
            margin: 5px;
        }

- pseudo elementos utilizados:

        ::after{}

- pseudo classes utilizadas:

        :hover;

- Demais recursos:
        Também foram utilizadas para a seleção: tags filhas, class, id

- Propriedades de estilos mais usadas:

        🔹margin
        🔹padding
        🔹font-family
        🔹font-size
        🔹font-weight
        🔹border
        🔹text-align
        🔹text-decoration
        🔹text-shadow
        🔹background-color
        🔹background-image
        🔹color
        🔹box-shadow
        🔹display

- Propriedades ou tags para EU estudar:

        🔹content (A propriedade CSS content é usada com os pseudoelementos ::before e ::after para gerar conteúdo  em um elemento.)
        🔹line-height (permite controlar o espaçamento entre as linhas de um texto.)
        🔹transition-duration 
        🔹max-heigt (altura máxima de um elemento)
        🔹min-height (altura mínima de um elemento)
        🔹min-width (largura mínima do elemento)
        🔹max-width (largura máxima do elemento)
        🔹list-style-type (define o tipo de marcador a ser usado)
        🔹list-style-position (Especifica a posição dos marcadores de item de lista - inside ou outside)
        🔹columns (coloca colunas no texto)
        🔹picture (usada para agrupar outras opções de imagens junto a tag source)


Estas são **anotações pessoais** realizadas durante o desafio e podem conter **erros!**😉