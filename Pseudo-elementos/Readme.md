## Pseudo-elementos

- Um pseudo-elemento CSS é uma palavra-chave adicionada a um seletor que permite que você estilize uma parte específica do elemento selecionado.

- Ele é representado pelos dois pontos "::"
ex.:

Neste exemplo o seletor class recebe somente depois do link a seta !
.especial::after{ 
    content: '←';  
}

Neste exemplo o seletor class recebe somente antes do link a seta !
.especial::before{
    content: '→';
}
