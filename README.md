
## Objetivo do trabalho:

Vamos usar o Node para montar um código que vai receber uma lista de propriedades de CSS (ex: background-color, font-size, text-align) e vai devolver essa lista ordenada de A-Z. Ordenar o CSS ajuda a encontrar mais rápido a propriedade que precisamos alterar.

➔ O código deve rodar em um laço que vai receber propriedades até a pessoa digitar a palavra “SAIR”, quando isso acontecer vai ser impresso no terminal a lista das propriedades ordenadas de A-Z uma em cada linha.

## Resolução:

Segue imagem com exemplo da aplicação funcionando:

Inicialmente a aplicação retorna a seguinte mensagem:

![image](https://user-images.githubusercontent.com/83782674/224346761-5fef91e1-3fa9-465c-8bbc-162588a0f695.png)

O primeiro texto digitado no exemplo é "font-size":

![image](https://user-images.githubusercontent.com/83782674/224347026-44ae7b7f-c7f2-4634-9756-7c6fed20882f.png)

Recebemos a mensagem de confirmação "Propriedade adicionada" e percebemos que o texto foi incluído ao array.

Em seguida setamos o texto "background-color":

![image](https://user-images.githubusercontent.com/83782674/224347681-fbc40435-231a-4987-885d-d04c13a4fc86.png)

Percebemos que após receber o texto "background-color" o array já se reordenou de forma correta.

Seguimos assim até o usuário digitar "sair" quando acontece o fim da aplicação e a mesma finalmente apresenta todas as propriedades em ordem alfabética.

![image](https://user-images.githubusercontent.com/83782674/224348827-ad0670e0-1322-46a6-88ac-97192aa84d1e.png)

Caso o usuário digite "sair" no início da aplicação, a mesma retornará que a lista está vazia.

![image](https://user-images.githubusercontent.com/83782674/224371013-5d0b1ed3-6554-41d9-92c5-2470a99fb8e0.png)

## :wrench: Tecnologias utilizadas
* NodeJS

## :wrench: Dependências utilizadas
* Prompt-sync

## :handshake: Colaboradores
Trabalho autoral de <a href="https://github.com/carolrc">Carolina Rocha</a>

## :dart: Status do projeto
Projeto Finalizado
