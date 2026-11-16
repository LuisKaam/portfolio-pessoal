# Portfólio Pessoal

## Descrição do portfólio

Portfólio pessoal feito para a atividade de Desenvolvimento de Sistemas, o site me apresenta, mostra alguns projetos que fiz durante o curso, e as tecnologias que estou aprendendo e meus contatos.

**Tecnologias utilizadas:** HTML, CSS, Bootstrap e JavaScript

![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5)

![CSS](https://img.shields.io/badge/CSS-3-blue?logo=css3)

![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?logo=bootstrap)

![GitHub](https://img.shields.io/badge/GitHub-Reposit%C3%B3rio-black?logo=github)

O JavaScript que foi usado é apenas para o que já vem no Bootstrap, para o menu funcionar pra quem usa celular

## Site publicado
[![Site](https://img.shields.io/badge/Site-Publicado-green?logo=github)](https://luiskaam.github.io/portfolio-pessoal/)

Acesse em: [luiskaam.github.io/portfolio-pessoal](https://luiskaam.github.io/portfolio-pessoal/)

## Como funciona

O site é só uma página, sendo dividida em quatro seções: Perfil, Projetos, Habilidades e Contato.

No topo tem um menu de navegação (navbar do Bootstrap). que ao clicar em cada item, a página rola até a seção correspondente, em algumas telas pequenas o menu vira um botão que abre e fecha

Na seção de Projetos temos cinco cards, cada um com uma descrição curta e um link para o repositório do projeto no GitHub, os cards ficam em colunas usando o grid do Bootstrap, então o site se ajusta ao tamanho da tela

A seção de Contato tem o meu email, GitHub e LinkedIn

## Recurso novo

- **Animações de hover**: o card do projeto sobe e ganha sombra quando o mouse passa por cima, e a habilidade aumenta um pouco de tamanho

## Como o recurso foi implementado

As animações foram feitas só com CSS, no arquivo `style.css`:

- `transition: 0.3s` deixa a mudança suave
- `transform: translateY(-5px)` faz o card subir
- `transform: scale(1.05)` faz a habilidade aumentar
- `box-shadow` cria a sombra no card

Esses efeitos só acontecem com o mouse em cima, usando `:hover`.

Também usei `scroll-behavior: smooth` para a rolagem do menu ficar mais suave.
