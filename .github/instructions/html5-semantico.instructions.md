---
description: HTML5 semântico e acessível para as páginas do Vestir Consciente
globs: "**/*.html"
alwaysApply: false
---

# HTML5 semântico — Vestir Consciente

## Objetivo e contexto

Crie páginas HTML semânticas, acessíveis e consistentes com a página inicial em `index.html`. O projeto é um MVP em HTML5 e CSS3, sem frameworks; mantenha a estrutura e os caminhos de arquivos existentes no repositório.

Use `docs/Escopo do Projeto.docx` como referência para o propósito, o conteúdo, as páginas previstas, a navegação e os requisitos de acessibilidade do projeto. O público com deficiência é prioritário.

## Estrutura e consistência

- Reutilize o cabeçalho, o menu de navegação e o rodapé de `index.html` nas demais páginas. Preserve os links e a estrutura compartilhada; marque o link da página atual com `aria-current="page"` e ajuste os caminhos relativos quando necessário.
- Mantenha o link de salto para `#main-content`, um `<header>`, um `<nav aria-label="Navegação Principal">`, um `<main id="main-content">` e um `<footer>`.
- Use elementos semânticos conforme o conteúdo: `<article>` para conteúdo independente e `<figure>` com `<figcaption>` para imagens ou mídias que precisem de legenda ou crédito. Use `<div>` apenas como contêiner de layout, nunca como substituto de elementos semânticos.
- Cada página deve ter exatamente um `<h1>`, com os demais títulos em hierarquia lógica, sem pular níveis.
- Toda `<section>` deve ter `aria-labelledby` apontando para o `id` único de seu título. Exemplo: `<section aria-labelledby="projeto-title"><h2 id="projeto-title">Sobre o projeto</h2>`.

## Acessibilidade e metadados

- Declare `<html lang="pt-BR">` em todas as páginas.
- Toda `<img>` deve ter `alt` descritivo e útil; use `alt=""` somente quando a imagem for puramente decorativa.
- Associe cada campo de formulário a um `<label>` e mantenha controles e links utilizáveis por teclado, com foco visível.
- Use ARIA quando necessário para complementar a semântica, sem duplicar informações já fornecidas por elementos HTML nativos.
- Inclua metadados viewport, um `<title>` exclusivo e descritivo e uma `<meta name="description">` adequada ao conteúdo de cada página.

## Estilos e implementação

- Use CSS externo, seguindo os estilos e caminhos já existentes no projeto (atualmente `css/style.css`).
- Não use estilos inline nem frameworks.
- Preserve a identidade visual e os padrões de layout responsivo e contraste do projeto.

## Em caso de dúvida

Se o conteúdo ou a estrutura de uma página não estiver definido no escopo do projeto, pergunte antes de inventar requisitos ou conteúdo.
