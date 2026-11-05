# TripWay - Guia de Viagens

## Integrantes

Turma: **1TDSPT**

- Lucas Alves Pires - RM576621
- Daniel Platero - RM575084
- Rafael Girardi - RM575391

## Descrição

Projeto desenvolvido para a disciplina de Front-End da FIAP, com o objetivo de criar um site multipágina para a **TripWay**, uma empresa fictícia de viagens que apresenta destinos, pacotes e permite ao usuário simular uma reserva.

## Evolução do Projeto

No **Checkpoint 1**, o foco foi a estrutura HTML: páginas, navegação, formulário e colaboração com GitHub.

No **Checkpoint 2**, o projeto foi evoluído com CSS externo, identidade visual (cores e fontes definidas em variáveis), layout com Flexbox, cards estilizados, botões com `:hover` e responsividade para desktop, tablet e celular.

## Tecnologias Utilizadas

- HTML5
- CSS3
- Git
- GitHub

## Páginas

| Página | Arquivo | Conteúdo |
|---|---|---|
| Home | `index.html` | Apresentação, imagem de destaque e descrição da empresa |
| Destinos | `pages/destinos.html` | Kingston (Jamaica), Ilha Santorini (Grécia) e Jalapão (Brasil) |
| Pacotes | `pages/pacotes.html` | Serviços e pacotes oferecidos |
| Contato | `pages/contato.html` | Formulário de contato e simulação de reserva |

## Estrutura de pastas

```
Trip-way---Guia-de-Viagens/
├── index.html
├── pages/
│   ├── destinos.html
│   ├── pacotes.html
│   └── contato.html
├── images/
├── css/
│   └── style.css
└── README.md
```

## Conceitos aplicados

- Estrutura básica do HTML
- HTML semântico (`header`, `nav`, `main`, `section`, `footer`)
- Site multipágina com navegação entre páginas
- Caminhos relativos para links e imagens
- Formulário com `form`, `label`, `input`, `select`, `textarea` e `button`
- Imagens com atributo `alt`
- CSS externo (`css/style.css`)
- Reset básico com `box-sizing: border-box`
- Variáveis CSS no `:root` (cores, fonte e bordas)
- Flexbox (`display: flex`) no header, na Home e nos cards
- Medidas relativas (`rem`, `%`, `vh`, `vw`)
- Responsividade com Media Queries (`@media`)
- Git e GitHub com branches e Pull Requests

## Como abrir

1. Clone o repositório:
```bash
   git clone https://github.com/TripWay-Cp/Trip-way---Guia-de-Viagens.git
```
2. Abra o arquivo `index.html` no navegador.

## Organização do trabalho

| Integrante | Responsabilidade | Branch |
|---|---|---|
| Lucas Alves Pires - RM576621 | Home, CSS base (reset, variáveis), header, navegação e botões | `feature/home` |
| Daniel Platero - RM575084 | Destinos, Pacotes e imagens | `feat/páginas-2-3` |
| Rafael - RM575391 | Contato e formulário | `rafael-contato` |

Todo o desenvolvimento foi feito em branches separadas e integrado na `main` por Pull Requests.
