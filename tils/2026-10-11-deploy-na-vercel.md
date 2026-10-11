# Deploy de um app Next.js na Vercel

**Data:** 2026-10-11
**Aula:** curso.dev

## O que aprendi
- Deploy é publicar o projeto em um servidor com URL pública
- A Vercel conecta no repositório do GitHub e roda o Next.js de verdade
- Cada `git push` na `main` dispara um novo deploy automático
- Se o build falhar, os Build Logs mostram o motivo
- A versão do Node pode ser ajustada em Settings → General

## Fluxo
```
git push → GitHub → Vercel → build → site atualizado
```

## Exemplo real
Publiquei o devnews: https://devnews-theta.vercel.app/

## Analogia
A Vercel é a cozinha que prepara o prato na hora, e o GitHub é o livro de receitas que ela consulta a cada mudança.