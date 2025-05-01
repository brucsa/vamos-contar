# Vamos Contar

Este é um projeto web simples que permite ao usuário inserir um valor inicial, um valor final e um passo, e então exibe a contagem resultante utilizando a estrutura de repetição `for` em JavaScript. Este projeto foi desenvolvido como prática durante o curso de JavaScript do Curso em Vídeo com Gustavo Guanabara.

## Demonstração

Você pode visualizar o projeto online [aqui](https://brucsa.github.io/vamos-contar/)

## Responsividade
O layout da página foi projetado para ser responsivo, utilizando Media Queries no arquivo estilo.css para se adaptar a diferentes tamanhos de tela, proporcionando uma melhor experiência em dispositivos móveis.

## Funcionalidades

* Permite ao usuário inserir um número inicial para a contagem.
* Permite ao usuário inserir um número final para a contagem.
* Permite ao usuário definir o passo (incremento ou decremento) da contagem.
* Realiza a contagem de forma crescente ou decrescente, dependendo dos valores inicial e final.
* Utiliza a estrutura de repetição `for` em JavaScript para gerar a sequência numérica.
* Exibe o resultado da contagem na tela.
* Valida a entrada de dados para garantir que todos os campos sejam preenchidos.
* Trata um passo inválido (menor ou igual a zero), considerando o passo como 1 nesse caso.
* Layout responsivo para diferentes tamanhos de tela (inclui Media Queries).

## Tecnologias Utilizadas

* HTML
* CSS
* JavaScript

## Estrutura de Arquivos

vamos-contar/

├── SVG/

│   └── fundo-imagem.svg

├── estilo.css

├── index.html

└── script.js