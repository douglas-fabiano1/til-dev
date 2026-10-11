# Primeira página com Next.js (Pages Router)

**Data:** 2026-10-09
**Aula:** curso.dev, aula 4

## O que aprendi
- O arquivo `pages/index.js` vira a rota `/`
- Cada arquivo dentro de `pages/` vira uma rota (`status.js` → `/status`)
- Uma página é um componente React exportado com `export default`
- `npm run dev` sobe o servidor em `http://localhost:3000`
- A pasta `.next` é gerada pelo Next e não vai para o GitHub

## Exemplo real
​```javascript
function Home() {
  return <h1>Teste</h1>;
}

export default Home;
```

## Analogia
`pages` é o mapa da loja: cada arquivo é uma porta que leva a uma vitrine.