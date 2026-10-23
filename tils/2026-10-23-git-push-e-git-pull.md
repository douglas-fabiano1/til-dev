# Git: push e pull

**Data:** 2026-10-23
**Aula:** curso.dev, aula 6

## O que aprendi

- `git push` envia meus commits do local para o origin (GitHub)
- `git pull` traz do origin o que eu ainda não tenho
- Faço `git pull` **antes** de começar a trabalhar, para evitar branches divergentes
- Se o push for recusado, o remoto tem commits que eu não tenho: `git pull --rebase` e depois `git push`
- No primeiro push de um repositório novo: `git push -u origin main`

## Comandos

```bash
git pull              # traz as novidades
git push              # envia meus commits
git pull --rebase     # traz e reencaixa meus commits por cima
git push -u origin main   # primeiro push, grava o vínculo
```

## Exemplo real

Editei um arquivo direto no site do GitHub e depois commitei local. O pull reclamou de branches divergentes e resolvi com `git pull --rebase`.

## Analogia

Push é entregar meu caderno na gráfica. Pull é buscar na gráfica as páginas que outras pessoas acrescentaram.
