# Git: corrigir o último commit com --amend

## O que aprendi
- `git commit --amend` substitui o último commit por um novo, aproveitando as alterações dele
- Serve para corrigir a mensagem ou incluir um arquivo esquecido
- `--no-edit` mantém a mensagem original
- Reescreve o histórico (o commit ganha outro código)
- Só uso antes do `push`; depois do push, gera branches divergentes
- Funciona offline

## Comandos
```bash
git commit --amend -m "nova mensagem"     # corrige a mensagem

git add arquivo-esquecido.txt
git commit --amend --no-edit              # inclui o arquivo no último commit
```

## Regra de ouro
```
Commit ainda não enviado (push)  →  pode usar amend
Commit já enviado (push)         →  evitar
```

## Analogia
É abrir a última caixa lacrada, colocar o item esquecido e lacrar de novo com outra etiqueta.
