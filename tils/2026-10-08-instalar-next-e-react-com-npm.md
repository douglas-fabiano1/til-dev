# Instalar Next.js e React com npm

**Data:** 2026-10-08
**Aula:** curso.dev

## O que aprendi
- `npm install pacote@versão` instala uma versão específica
- O Next.js precisa de uma versão compatível do React (peer dependency)
- `react-dom` conecta o React ao navegador
- `package-lock.json` trava as versões exatas instaladas
- `npm audit fix --force` pode quebrar o projeto, então evito em versões de estudo

## Comandos
```bash
npm install next@13.1.6
npm install react@18.2.0
npm install react-dom@18.2.0
```

## Analogia
O `package.json` é a lista de ingredientes. O `package-lock.json` é a nota fiscal com a marca e o lote exatos.