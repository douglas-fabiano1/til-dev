# Git: restore e restore --staged


## O que aprendi

- `git restore arquivo` **descarta** minhas edições e volta o arquivo ao último commit
- Isso não tem volta: o que eu escrevi é perdido
- `git restore --staged arquivo` só tira o arquivo da staging, e minha edição continua
- Uso `git diff` antes para ter certeza do que vou descartar

## Comandos

```bash
git restore pages/index.js            # descarta a edição (cuidado)
git restore --staged .gitignore       # desfaz o git add, mantém o texto
```

## Resumo

| Comando | Edição | Staging |
| --- | --- | --- |
| `git restore arquivo` | perdida | não muda |
| `git restore --staged arquivo` | mantida | desfeita |

## Analogia

`restore --staged` é tirar o item da caixa antes de lacrar. `restore` é jogar o rascunho fora e voltar à última versão limpa.
