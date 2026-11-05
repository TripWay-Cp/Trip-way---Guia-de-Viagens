# Parte do Rafael — como aplicar (5 commits)

Começar da main atualizada:

```bash
git checkout main
git pull
git checkout -b feature/contato-responsivo
```

## Commit 1 — formulário
Substituir `pages/contato.html` pelo arquivo desta pasta.
Colar no fim do `css/style.css` o bloco "PÁGINA DE CONTATO" do `css-para-colar.css`.

```bash
git add pages/contato.html css/style.css
git commit -m "estiliza formulário de contato"
```

## Commit 2 — pacotes
Substituir `pages/pacotes.html` pelo arquivo desta pasta.
Colar no `css/style.css` o bloco "PÁGINA DE PACOTES".

```bash
git add pages/pacotes.html css/style.css
git commit -m "organiza pacotes em cards com flexbox"
```

## Commit 3 — remover CSS duplicado
No `css/style.css`, o bloco `/* TABLET */ @media (max-width: 768px) { .card-destino ... }` aparece 2 vezes seguidas. Apagar um deles.

```bash
git add css/style.css
git commit -m "remove media query duplicada dos destinos"
```

## Commit 4 — responsividade geral
Colar o bloco "RESPONSIVIDADE GERAL" (os dois @media) no fim do `css/style.css`.

```bash
git add css/style.css
git commit -m "adiciona responsividade do menu, pacotes e formulário"
```

## Commit 5 — revisão
Abrir as 4 páginas no navegador (F12 > modo celular) e conferir os links.
Ajustar o `<title>` e indentação se precisar.

```bash
git add .
git commit -m "revisa caminhos e testa responsividade"
git push -u origin feature/contato-responsivo
```

Depois abrir o Pull Request para a main.
