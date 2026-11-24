# Vestir Consciente

Site de moda sustentável e inclusiva, com 10 páginas interligadas, desenvolvido em HTML5 e CSS3 para a Atividade A06 – Conclusão e Apresentação de Projeto de Site, da disciplina de Desenvolvimento Web do curso de Análise e Desenvolvimento de Sistemas da Fatec São Caetano do Sul.

- **Site publicado (HTTPS):** https://vestirconsciente.up.railway.app
- **Repositório:** https://github.com/AnandaMoya/F-SCS-DESWEB-ADS-M-02-2026-VESTIRCONSCIENTE
- **Autora:** Ananda Alves Moya
- **Professor:** Paulo Fratta
- **Instituição:** Fatec São Caetano do Sul

## Tema

Sustentabilidade e impacto social, com foco em moda. O site mostra os impactos da moda de produção em massa (resíduos têxteis, consumo de água, contaminação por corantes e microplásticos, precarização do trabalho) e apresenta alternativas: moda circular, slow fashion, materiais ecológicos e upcycling. Pessoas com deficiência (PCD) são o público prioritário, por isso acessibilidade orienta as decisões de código e de design.

## Objetivos

1. Entregar um site completo de 10 páginas interligadas, em HTML5 semântico e CSS3, com layout responsivo para celular, tablet e desktop.
2. Divulgar moda circular, slow fashion e materiais de menor impacto, com dados e fontes citados.
3. Garantir acessibilidade: texto alternativo, contraste, navegação por teclado, ARIA quando necessário e atalho para o conteúdo principal.
4. Oferecer um formulário de contato com validação HTML5 e confirmação.
5. Publicar o site no Railway, com HTTPS.

## Páginas

| Nº | Arquivo | Conteúdo |
|---|---|---|
| 1 | `index.html` | Apresentação, pilares e atalhos |
| 2 | `sobre.html` | Missão, visão, valores e compromisso de inclusão |
| 3 | `modacircular.html` | Brechó e peças de segunda mão, com filtros em CSS |
| 4 | `slowfashion.html` | Produção local, artesãos e marcas independentes |
| 5 | `materiais.html` | Materiais ecológicos e upcycling, com tabela comparativa |
| 6 | `galeria.html` | Imagens com legendas e fontes |
| 7 | `noticias.html` | Notícias e artigos sobre moda sustentável |
| 8 | `midia.html` | Vídeo, áudio e mapa incorporado (iframe) |
| 9 | `orcamento_hospedagem.html` | Comparativo de 3 hospedagens e 3 domínios, com a escolha justificada |
| 10 | `contato.html` | Formulário validado, dados de contato, autoria, acessibilidade e privacidade |

## Correspondência com os nomes do enunciado

O enunciado da A06 sugere os nomes `projetos`, `impacto` e `acessibilidade`. O conteúdo foi organizado em páginas com nomes mais específicos ao tema. A tabela mostra onde cada item sugerido está no site.

| Nome sugerido no enunciado | Onde está no site |
|---|---|
| `index` | `index.html` |
| `sobre` | `sobre.html` |
| `projetos` | `modacircular.html` e `slowfashion.html` (as alternativas apresentadas pelo projeto) |
| `impacto` | `materiais.html` (dados com fonte e materiais de menor impacto) e `noticias.html` |
| `acessibilidade` | `contato.html#acessibilidade` (suporte PCD) e `sobre.html` (compromisso de inclusão); a acessibilidade também está em todas as páginas |
| `galeria` | `galeria.html` |
| `midia` | `midia.html` |
| `noticias` | `noticias.html` |
| `contato` | `contato.html` |
| `orcamento_hospedagem` | `orcamento_hospedagem.html` |

Pastas: `img/` do enunciado corresponde a `images/`; `assets/` corresponde a `media/` (vídeo e legendas); não há pasta `js/`, porque o projeto não usa JavaScript.

## Estrutura de pastas

/
├── index.html
├── sobre.html
├── modacircular.html
├── slowfashion.html
├── materiais.html
├── galeria.html
├── noticias.html
├── midia.html
├── orcamento_hospedagem.html
├── contato.html
├── favicon.ico
├── css/
│   └── style.css          
├── images/                
├── media/
│   ├── costura.mp4        
│   └── costura.pt-BR.vtt  
└── docs/                 

## Documentação (pasta `docs/`)

| Arquivo | Conteúdo |
|---|---|
| `README.md` | Este arquivo: visão geral, páginas, estrutura e tecnologias |
| `Escopo do Projeto.docx` | Escopo do site |
| `orcamento-hospedagem.docx` | Comparativo de hospedagens e domínios, com cálculos e a escolha justificada |
| `Evidencias de Testes.docx` | Resultados e prints do W3C, axe DevTools, Lighthouse, teclado e responsividade |
| `Relatório de Melhorias.docx` | Do MVP ao site final: o que mudou e por quê |

## Tecnologias

- **HTML5 semântico** (`header`, `nav`, `main`, `section`, `article`, `figure`, `details`, `footer`), com atalho para o conteúdo principal e `aria-current` no menu.
- **CSS3** em um único arquivo: variáveis, Flexbox, Grid, `@media` (um ponto de quebra em 768/769 px), `:has()` nos filtros, `:target` na confirmação do formulário e `:user-invalid` na validação.
- **Sem JavaScript**: filtros, confirmação do formulário e blocos de descrição funcionam só com HTML e CSS.
- **Mídia:** vídeo HTML5 com legendas (`<track>`), player do YouTube incorporado (youtube-nocookie), áudio HTML5 e mapa do OpenStreetMap em `iframe`.
- **Fontes:** Montserrat e Playfair Display (Google Fonts).
- **Hospedagem:** Railway, com HTTPS e endereço `vestirconsciente.up.railway.app`.
- **Testes:** W3C Nu HTML Checker, W3C CSS Validator, Lighthouse, axe DevTools, teclado e testes em celular.

## Divisão de funções

O trabalho é individual. Todas as funções foram da autora: planejamento e escopo, pesquisa de conteúdo, design e identidade visual, HTML, CSS, testes de acessibilidade e responsividade, publicação e documentação.