# Git: ver o que mudou com git diff

## O que aprendi
- `git diff` calcula a diferença entre versões dos arquivos
- Linhas com `+` foram adicionadas, linhas com `-` foram removidas
- `git diff` mostra o que ainda **não** foi para a staging
- `git diff --staged` mostra o que **já** está na staging, pronto para o commit
- Conferir o diff antes de commitar evita mandar coisa errada
- Funciona offline

## Comandos
```bash
git diff                # alterações ainda não preparadas
git add teste.txt
git diff --staged       # alterações preparadas para o commit
```

## Exemplo real
```diff
-  return <h1>Teste</h1>;
+  return <h1>devnews no ar!</h1>;
```

## Analogia
É conferir a lista de compras riscando o que mudou antes de passar no caixa.
