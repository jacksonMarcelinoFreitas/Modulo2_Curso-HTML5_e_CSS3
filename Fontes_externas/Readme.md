## Formas de Inserir fontes internas:

🟢Fonte pre definida
- 1-> @import
ex.: @import url('');

🟢Definindo fonte
- 2-> @font-face
ex.: @font-face {
            font-family: 'Samantha'; -> nome que atribuimos
            src: url(Font/samantha.ttf) format('truetype'); -> local do aqrquivo e format
            font-weight: normal; -> configurações adicionais
            font-style: normal;
        }