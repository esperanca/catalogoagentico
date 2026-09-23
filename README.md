# catalogoagentico

Protótipo navegável publicado na Netlify.

- Repo: https://github.com/esperanca/catalogoagentico
- Site (Netlify): a conectar — veja passos abaixo

## Publicar na Netlify (2 opções)

### Opção A — via painel (recomendado, 2 min)
1. Acesse https://app.netlify.com/start
2. **Add new site → Import an existing project → GitHub → `esperanca/catalogoagentico`**
3. Build settings: **Publish directory = `.`** (sem build command)
4. Deploy. A cada `git push`, a Netlify republica sozinho.

### Opção B — via CLI (faço por você quando me passar o token)
```bash
npm i -g netlify-cli
netlify link   # ou netlify init
netlify deploy --prod --dir .
```

## Enviar o protótipo
Copie os arquivos do protótipo para esta pasta, mantendo `index.html` na raiz, depois:
```bash
git add . && git commit -m "adiciona prototipo" && git push
```
