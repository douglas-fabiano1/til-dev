# Fixar a versão do Node com .nvmrc

**Data:** 2026-10-07
**Aula:** curso.dev, aula 3

## O que aprendi
- `.nvmrc` é um arquivo na raiz do projeto com a versão do Node que ele usa
- `nvm install` e `nvm use`, sem argumentos, leem esse arquivo
- O curso usa o Node 18 (apelido `lts/hydrogen`)
- Quem clonar o projeto roda a mesma versão que eu

## Comandos
```bash
nvm install lts/hydrogen   # instala o Node 18 LTS
nvm use lts/hydrogen       # ativa essa versão
node -v > .nvmrc           # grava a versão no arquivo
cat .nvmrc                 # confere o conteúdo

nvm install                # (outra máquina) instala a versão do .nvmrc
nvm use                    # (outra máquina) ativa a versão do .nvmrc
```

## Exemplo real
No `til-dev`, rodei `node -v > .nvmrc` e o arquivo ficou com `v18.x.x`.

## Analogia
É a etiqueta de voltagem do projeto: antes de ligar, todo mundo lê qual versão usar.