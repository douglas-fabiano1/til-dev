# Next.js: Pages Router vs App Router

**Data:** 2026-10-09
**Aula:** curso.dev, aula 4

## O que aprendi
- O Next organiza as rotas pelas **pastas**
- **Pages Router (antigo):** pasta `pages/`, cada arquivo vira uma rota
- **App Router (novo):** pasta `app/`, cada pasta com um `page.js` vira uma rota

## Comparativo
| Rota | Pages Router | App Router |
|---|---|---|
| `/` | `pages/index.js` | `app/page.js` |
| `/status` | `pages/status.js` | `app/status/page.js` |

## Analogia
Pages: cada arquivo é uma sala. App: cada pasta é uma sala, e o `page.js` é a porta de entrada.