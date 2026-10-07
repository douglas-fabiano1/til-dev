# Branches divergentes: merge vs rebase no git pull

**Data:** 2026-10-07
**Aula:** Aprendizado na prática

## O que aprendi
- Branches divergem quando o remoto e o local ganham commits diferentes a partir do mesmo ponto
- Isso aconteceu porque editei um arquivo direto no site do GitHub e depois commitei localmente
- O `git pull` pede para eu escolher: merge ou rebase
- **Merge** junta as duas linhas e cria um commit extra de merge (abre o Vim pedindo a mensagem)
- **Rebase** reencaixa meus commits depois dos remotos, deixando o histórico em linha reta

## Comandos
```bash
git pull --rebase                      # pull com rebase só desta vez
git config --global pull.rebase true   # rebase como padrão em todo pull
git rebase --abort                     # desiste e volta ao estado anterior
```

## Se o Vim abrir (merge)
​```
Esc → :wq → Enter    # salvar e sair
Esc → :q! → Enter    # sair sem salvar
​```

## Exemplo real
Editei o `nvm-no-ubuntu-vs-windows.md` pelo site do GitHub e fiz um commit local sobre o `.nvmrc`. O `git pull` reclamou de branches divergentes. Resolvi com `git pull --rebase` e `git push`.

## Para lembrar
- Antes de editar localmente: `git pull`
- Evitar editar arquivos pelo site do GitHub
- Se precisar editar pelo site, fazer `git pull` antes de voltar ao VS Code

## Analogia
Merge é uma reunião para juntar duas versões do caderno. Rebase é costurar a sua página depois da página do colega, como se ela tivesse sido escrita depois.