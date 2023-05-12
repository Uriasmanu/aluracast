# Curso de CSS Grid na Alura

Este curso oferecido pela Alura tem como objetivo ensinar aos alunos como utilizar o CSS Grid para construir páginas responsivas de forma mais eficiente.

## Sobre o CSS Grid

O CSS Grid é uma tecnologia relativamente nova no mundo do desenvolvimento web, mas que vem ganhando espaço devido à sua capacidade de permitir layouts complexos e altamente personalizáveis, além de ser uma solução mais eficiente do que os métodos de layout mais antigos.

## Conteúdo do curso

O curso aborda desde os conceitos básicos do CSS Grid, até a construção de layouts mais complexos. Algumas das principais áreas abordadas no curso incluem:

- Introdução ao CSS Grid
- Entendendo o conceito de grid
- Definindo áreas no grid
- Trabalhando com grid lines
- Utilizando o grid-template-columns e grid-template-rows
- Trabalhando com grid-gap
- Posicionando elementos no grid
- Construindo um layout responsivo com CSS Grid

## Pré-requisitos

Para participar deste curso, é necessário ter conhecimento prévio de HTML e CSS básicos.

## Exemplo de código

Aqui está um exemplo de código que pode ser utilizado para criar um layout básico de duas colunas e duas linhas com um cabeçalho e um menu lateral:

```css
body {
  display: grid;
  grid-template-areas:
    "aside header"
    "aside main";
  grid-template-columns: auto 1fr;
}

.cabecalho {
  grid-area: header;
}

.menu-lateral {
  grid-area: aside;
}

.principal {
  grid-area: main;
}
```

## Conclusão

Este curso oferece uma excelente oportunidade para os alunos aprenderem a utilizar o CSS Grid para criar layouts complexos e altamente personalizáveis de forma mais eficiente. Se você está procurando uma maneira de melhorar suas habilidades em desenvolvimento web, este curso é definitivamente uma excelente opção.