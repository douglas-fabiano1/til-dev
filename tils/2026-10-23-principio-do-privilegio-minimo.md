# Princípio do privilégio mínimo

## O que aprendi

- Cada pessoa ou ferramenta deve ter só o acesso de que precisa para fazer o trabalho
- Se algo der errado (erro, vazamento, ataque), o estrago fica limitado
- Vale para ferramentas externas, pessoas, chaves de API e contas de serviço

## Exemplo real

Ao autorizar a Vercel no GitHub, escolher apenas o repositório devnews em vez de liberar todos.

## Como aplicar

```
Preciso que a ferramenta acesse 1 repositório?  →  liberar só ele
Preciso só de leitura?                          →  não dar permissão de escrita
Não preciso mais do acesso?                     →  revogar
```

## Analogia

O zelador recebe a chave do prédio que cuida, não a de todos os prédios da cidade.
