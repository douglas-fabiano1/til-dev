# Git: push --force e --force-with-lease

**Data:** 2026-10-23
**Aula:** curso.dev, aula 6

## O que aprendi

- `git push --force` substitui o histórico do GitHub pelo meu
- Aparece depois de reescrever commits já enviados (por exemplo, `--amend` depois do push)
- Em branch compartilhada ou na main de uma equipe, nunca uso
- `--force-with-lease` é a versão mais segura: recusa o push se o remoto tiver algo novo que eu não vi

## Comandos

```bash
git push --force-with-lease   # preferido
git push --force              # só em branch pessoal, com cuidado
```

## Quando usar

```
Branch só minha, reescrevi um commit já enviado  → --force-with-lease
Branch compartilhada ou main de equipe            → não usar
```

## Analogia

`--force` é trocar a página publicada sem olhar se alguém escreveu nela. `--force-with-lease` é conferir antes se a página continua como você deixou.
