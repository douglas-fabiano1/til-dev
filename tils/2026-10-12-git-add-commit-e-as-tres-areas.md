# Git: add, commit e as três áreas

## O que aprendi
- **Working directory:** onde eu edito os arquivos
- **Staging area:** onde preparo o que vai no próximo commit (`git add`)
- **Repositório:** onde os commits ficam salvos (`git commit`)
- `git add` sobe as alterações para a staging area
- `git commit` cria um commit novo com o que está na staging
- Esses comandos funcionam offline, nada sai do meu computador

## Comandos
```bash
git add pages/index.js          # prepara um arquivo
git add .                       # prepara tudo
git commit -m "feat: cria primeira página"
```

## Exemplo real
No devnews, usei `git add pages/index.js` e depois `git commit -m "feat: cria primeira página e script dev"`.

## Analogia
Working é a mesa bagunçada. Staging é separar o que vai na caixa. Commit é lacrar e etiquetar a caixa.
