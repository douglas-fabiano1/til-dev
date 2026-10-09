# Subir o servidor web com next dev

**Data:** 2026-10-09
**Aula:** curso.dev, aula 4

## O que aprendi
- `next dev` sobe o servidor de desenvolvimento
- Por padrão ele responde em `http://localhost:3000`
- Recarrega a página sozinho quando salvo um arquivo
- É melhor criar um script no `package.json` do que digitar o comando

## Configuração
```json
"scripts": {
  "dev": "next dev"
}
```

​```bash
npm run dev
​```

## Analogia
`npm run dev` é abrir a loja para testes: só eu vejo, e as vitrines mudam na hora que eu mexo.