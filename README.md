# Projeto Pré-Admissão

## Índice

* [1. Resumo do projeto](#2-resumo-do-projeto)
* [2. Objetivos de aprendizagem](#3-objetivos-de-aprendizagem)
* [3. Critérios de aceitação mínima do
  projeto](#5-critérios-de-aceitação-mínima-do-projeto)
* [4. Hacker edition](#6-hacker-edition)
* [5. Considerações técnicas](#7-considerações-técnicas)
* [6. Guias, dicas e leituras
  complementares](#8-guias-dicas-e-leituras-complementares)

***

## 1. Resumo do projeto

O que tenho que fazer exatamente? Neste projeto você desenvolverá uma aplicações web de perguntas e respostas. Sua aplicação deve permitir que o usuário responda uma perguntas e escolha as respostas, a partir de uma lista de alternativas.

O tema é livre. Você deve criar a melhor aplicações web possível.

## 2. Objetivos de aprendizagem

O objetivo principal deste projeto é ter uma primeira experiência desenvolvendo
aplicações web (WebApp) que interajam com o usuário através do navegador e
desenvolver a lógica, utilizando HTML, CSS e JavaScript como ferramentas.

Pense nos passos que o usuário tem que percorrer, repasse o fluxograma e se organize com sua dupla/trio.

### HTML e CSS

* [ ] [Uso de HTML semântico.](https://developer.mozilla.org/pt-BR/docs/Glossario/Semantica#Sem%C3%A2ntica_em_HTML)
* [ ] Uso de selectores de CSS.

### JavaScript

* [ ] Uso de condicionais
* [ ] Uso de funções
* [ ] Declaração correta de variáveis (const & let)

### Estrutura de código e guia de estilo

* [ ] Uso identificadores descritivos (Nomenclatura | Semântica).

## 3. Critérios mínimos de aceitação do projeto

Os critérios que você deverá considerar para saber se completou o projeto são:

### Implementação da Interface de Usuário (HTML/CSS/JS)

1. Mostrar uma tela de boas-vindas na qual se peça, através de prompt, o nome do usuário antes de começar a prova.
2. Mostrar uma tela na qual o usuário pode escolher se quer mesmo dar início a prova ou não. Caso ele não deseje iniciar, o fluxo deve ser encerrado. Caso ele queira, seguirá para a próxima etapa, descrita no item 3.
3. Mostrar, através de prompt,  a pergunta 1 com alternativas. O usuário responde e depois é apresentada a pergunta 2 e depois a 3.
4. Mostrar uma tela de resultados (respostas corretas e incorretas).

Seguem exemplos de tela. Você pode usar as cores e fontes que quiser e acrescentar detalhes, porém os seguintes aspectos do leiaute modelo devem ser mantidos:
- O nome da pessoa deve ser impresso na tela;
- As respostas corretas e erradas devem ser impressas na tela em caixas separadas, exibidas lado a lado.

![tela 1](https://user-images.githubusercontent.com/39506102/74755660-3c425f00-5252-11ea-953d-2681aa3a9a17.png)

![tela 2](https://user-images.githubusercontent.com/39506102/74755700-47958a80-5252-11ea-8028-42540b43f8cd.png)

![tela 3](https://user-images.githubusercontent.com/39506102/74755741-58de9700-5252-11ea-8028-07457b24f16b.png)


![tela 4](https://user-images.githubusercontent.com/39506102/74755765-6267ff00-5252-11ea-892a-20e85d7fa099.png)

### Entrega

A entrega será feita através do GitHub e sua prova deve ser publicada no GitHub Pages.

## 4. Hacker edition

Se **terminou** tudo que foi listado anteriormente e ainda te sobrou tempo,
tente explorar e completar o seguinte:

* Adicionar no fluxo, uma condicional que permita ao usuário decidir qual prova quer realizar:
    Exemplo: 
    - Tipo A: Prova de Geografia
    - Tipo B: Prova de Matemática

## 5. Considerações técnicas

A lógica do projeto deve estar implementada completamente em JS, HTML e CSS.
Neste projeto não é permitido usar bibliotecas ou frameworks, somente [vanilla
JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e).

Não deve ser usada a _pseudo-variável_ `this`.

### `index.html`

Aqui vai a página que será mostrada para o usuário. Também nos serve para
indicar que script será usado e unir tudo que fizemos.

### `style.css`

Este arquivo deve conter as regras de estilo. Queremos que escreva suas próprias
regras, por isso NÃO está permitido o uso de frameworks de CSS (Bootstrap,
materialize, etc).

### `main.js`

Aqui você escreverá todo o código que tenha a ver com a lógica.

## 6. Guias, dicas e leituras complementares

### Recursos e temas relacionados

* [GitHub](https://github.com/)
* [GitHub Pages](https://pages.github.com/)
* [Tutorial - GitHub e GitHub Pages](https://youtu.be/p36l8QR4-g8)
