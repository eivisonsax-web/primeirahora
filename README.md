
# Primeira Hora — Starter

## Como publicar no GitHub Pages
1. Crie um repositório público e envie **todos** os arquivos desta pasta (incluindo a pasta `data/`).
2. Vá em Settings → **Pages** → *Deploy from a branch* → branch **main** e pasta **/**.
3. Abra o link gerado (ex.: `https://SEU_USUARIO.github.io/primeirahora/`).

## Como atualizar notícias
- Edite o arquivo **data/posts.json**. Cada post tem:
  - `cat`: delmiro, alagoas, sertao, policia, politica, economia, esportes, cultura
  - `title`, `dt` (ISO, use `-03:00`), `img`, `excerpt`, `body`.
- Faça commit; o site atualiza sozinho.

## Arquivos adicionais
- **rss.xml**: RSS simples (atualize manualmente ou peça para automatizarmos).
- **sitemap.xml**: mapa do site (pode ser expandido com outras páginas).
- **robots.txt**: aponta para o sitemap.

> Dúvidas? Atualize `posts.json` e envie imagens para um CDN (ou a própria pasta `images/` do repositório).
