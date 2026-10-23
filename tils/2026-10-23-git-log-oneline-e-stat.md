# Git: log --oneline e --stat


## O que aprendi

- `--oneline` mostra um commit por linha (código curto + mensagem)
- `--graph` desenha as branches ao lado do log
- `--stat` mostra **quais arquivos** mudaram e quantas linhas foram adicionadas ou removidas
- `--stat` também funciona com `git diff`

## Comandos

```bash
git log --oneline
git log --oneline --graph
git log --stat
git diff --stat
```

## Exemplo de saída do --stat

```
 pages/index.js | 2 +-
 .gitignore     | 3 ++-
 2 files changed, 3 insertions(+), 2 deletions(-)
```

## Analogia

`--oneline` é o índice do álbum. `--stat` é a legenda que diz quais fotos foram trocadas em cada página.
