# Prefixos de mensagem de commit (Conventional Commits)

## O que aprendi
- Prefixo é uma etiqueta no começo da mensagem que diz o tipo da mudança
- O padrão se chama **Conventional Commits**
- Um commit por propósito: mudanças de naturezas diferentes ficam em commits separados
- A descrição começa com verbo, em minúsculas, sem ponto final, até ~50 caracteres

## Os prefixos

| Prefixo | Quando usar | Exemplo |
|---|---|---|
| `feat:` | funcionalidade nova | `feat: cria primeira página` |
| `fix:` | correção de erro de funcionamento | `fix: corrige link quebrado no menu` |
| `docs:` | README e documentação | `docs: atualiza índice de TILs` |
| `style:` | formatação, sem mudar o comportamento | `style: adiciona newline no index.js` |
| `refactor:` | reorganizar o código sem mudar o resultado | `refactor: separa componente Header` |
| `test:` | criar ou ajustar testes | `test: adiciona teste da rota /status` |
| `chore:` | configuração e manutenção | `chore: fixa Node 18 no .nvmrc` |
| `build:` | build e dependências | `build: atualiza versão do next` |
| `ci:` | automações (GitHub Actions) | `ci: adiciona workflow de testes` |
| `perf:` | melhoria de desempenho | `perf: reduz tamanho da imagem` |
| `revert:` | desfazer um commit anterior | `revert: desfaz mudança no título` |
| `til:` | prefixo próprio do til-dev, novo aprendizado | `til: git commit --amend` |

## Como escolher
```
Mudou o que o usuário vê ou faz?
├─ algo novo       → feat:
└─ algo consertado → fix:

Mudou só documentação?                   → docs:
Mudou só a aparência do código?          → style:
Mudou a estrutura, não o resultado?      → refactor:
Mudou configuração ou ferramentas?       → chore:
Mudou testes?                            → test:
```

## Formato completo
```
tipo(escopo opcional): descrição curta no presente

feat(pages): cria página de status
feat!: remove rota antiga     ← "!" indica mudança que quebra compatibilidade
```

## Exemplo real
No devnews, ajustei o newline do `index.js` e um comentário no `.gitignore`. Foram dois commits:
```bash
git commit -m "style: adiciona newline no final do index.js"
git commit -m "chore: adiciona comentário no .gitignore"
```

## Analogia
Os prefixos são as etiquetas coloridas das pastas: antes de ler o conteúdo, você já sabe de que tipo é.
