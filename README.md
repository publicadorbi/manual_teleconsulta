# Manual Teleconsulta

Breve README do site "Manual Teleconsulta" — orientações rápidas para executar, desenvolver e publicar.

## Descrição
Site estático com conteúdo de teleconsulta e interconsulta, pronto para ser servido em um servidor HTTP simples ou aberto localmente no navegador.

## Estrutura do projeto
- `index.html` — página inicial
- `css/style.css` — estilos do site
- `img/` — imagens usadas no site
- `pages/teleconsulta.html` — página de teleconsulta
- `pages/Interconsulta.html` — página de interconsulta

## Tecnologias
- HTML5
- CSS3

## Requisitos
- Navegador moderno (Chrome, Edge, Firefox, Safari)
- Para servidor local opcional: Python 3 (opcional)

## Como executar (local)

Opção 1 — Abrir direto (modo desenvolvimento rápido):

1. Abra o arquivo `index.html` no seu navegador.

Opção 2 — Servir via servidor HTTP simples (recomendado para testar rotas/paths):

```bash
# na pasta do projeto
python -m http.server 8000
# abra http://localhost:8000
```

## Desenvolvimento
- Edite as páginas em `pages/` e os estilos em `css/style.css`.
- Mantenha imagens em `img/` e use caminhos relativos nas páginas.

## Deploy
- Este é um site estático: qualquer host estático serve (GitHub Pages, Netlify, Vercel, S3, etc.).
- Para GitHub Pages, crie um repositório e publique a branch `main` ou a pasta `docs/` conforme preferir.

## Contribuição
- Abra uma issue descrevendo a sugestão ou bug.
- Envie um pull request com mudanças pequenas e bem descritas.

## Licença
Por padrão: MIT. Atualize conforme necessidade.

## Contato
Atualize o arquivo com seu nome e contato ou mantenha registro do repositório.
