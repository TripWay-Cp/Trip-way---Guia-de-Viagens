# TripWay - Guia de Viagens

Projeto desenvolvido para o **Checkpoint 1 de Front-End** da FIAP.

Site multipágina em HTML de uma empresa fictícia de viagens chamada **TripWay**, que apresenta destinos, pacotes e permite ao usuário simular uma reserva.

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
| Lucas Alves Pires - RM76621 | Home e estrutura inicial | `estrutura/home` |
| Daniel Platero - RM575084 | Destinos, Pacotes e imagens | `feat/páginas-2-3` |
| Rafael - RM575391 | Contato e formulário | `rafael-contato` |

Todo o desenvolvimento foi feito em branches separadas e integrado na `main` por Pull Requests.
