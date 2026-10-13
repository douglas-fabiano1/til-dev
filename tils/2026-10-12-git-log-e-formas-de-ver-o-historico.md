# Git: ver o histórico com git log

## O que aprendi
- `git log` lista os commits do repositório, do mais novo para o mais antigo
- Cada commit tem um código (hash), autor, data e mensagem
- Existem versões mais compactas e visuais do mesmo comando
- Funciona offline

## Comandos
```bash
git log                      # completo
git log --oneline            # uma linha por commit
git log --oneline --graph    # mostra o desenho das branches
git log -5                   # só os 5 últimos
```

## Exemplo real
Usei `git log --oneline` para confirmar que meu commit `docs: define objetivo do projeto` estava no histórico.

## Dica
Dentro do `git log`, aperte `q` para sair.

## Analogia
É folhear o álbum de fotos do projeto, da mais recente para a mais antiga.
