# nvm no Ubuntu (WSL) é diferente do nvm no Windows

**Data:** 2026-10-07
**Aula:** curso.dev, aula 3

## O que aprendi
- No Windows existe o nvm-windows, que não entende `lts/hydrogen`
- No Ubuntu, o nvm oficial entende apelidos de versão LTS
- Após instalar o nvm, preciso rodar `source ~/.bashrc` ou reabrir o terminal
- `which node` mostra de onde vem o Node em uso
- Para definir a versão Nodejs lts/hydrogen como padrão no Ubuntu `nvm alias default lts/hydrogen`

## Comandos
```bash
source ~/.bashrc
nvm install lts/hydrogen
nvm use lts/hydrogen
nvm alias default lts/hydrogen
```

## Analogia
Duas lojas com o mesmo nome: cada sistema tem a sua.
