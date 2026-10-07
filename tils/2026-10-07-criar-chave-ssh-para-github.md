# Criar e adicionar chave SSH no GitHub

## O que aprendi
- A chave SSH tem duas partes: **privada** (nunca compartilho) e **pública** (entrego ao GitHub)
- Com SSH, o `git push` não pede senha

## Passo a passo
​```bash
ssh-keygen -t ed25519 -C "seu-email@exemplo.com"
cat ~/.ssh/id_ed25519.pub     # copia a chave pública
```
1. GitHub → Settings → SSH and GPG keys → New SSH key
2. Colar o conteúdo da chave **pública** (`.pub`)
3. Testar:
```bash
ssh -T git@github.com
​```

## Cuidado
Nunca publique o arquivo sem `.pub`: ele é a chave privada.