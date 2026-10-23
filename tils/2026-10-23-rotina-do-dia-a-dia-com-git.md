# Rotina do dia a dia com Git


## O que aprendi

- `git status` é o primeiro comando antes de agir: mostra o que está pendente
- Existe uma sequência segura para todo ciclo de trabalho

## Rotina

```bash
git pull                       # 1. traz as novidades
git status                     # 2. vê o estado
git diff                       # 3. confere o que mudou
git add .                      # 4. prepara
git commit -m "feat: ..."      # 5. salva
git log --oneline              # 6. confirma
git push                       # 7. envia
```

## Qual comando usar em cada problema

| Situação | Comando |
| --- | --- |
| Errei a mensagem do último commit (sem push) | `git commit --amend -m "..."` |
| Esqueci um arquivo no último commit (sem push) | `git add arquivo` + `git commit --amend --no-edit` |
| Quero descartar o que editei em um arquivo | `git restore arquivo` |
| Adicionei um arquivo por engano à staging | `git restore --staged arquivo` |
| Quero ver o que mudou em cada commit | `git log --stat` |
| O push foi recusado | `git pull --rebase` e depois `git push` |

## Analogia

É a checklist do piloto antes de decolar: sempre na mesma ordem, para não esquecer nada.
