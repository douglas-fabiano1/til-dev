# GitHub Pages vs Vercel para Next.js


## O que aprendi
- GitHub Pages serve apenas arquivos estáticos (HTML, CSS, JS prontos)
- Ele não executa Node.js, então não roda um app Next.js completo
- Sem `index.html`, o GitHub Pages mostrou meu README
- Vercel executa o Next.js e faz deploy automático a cada push
- Deploy é publicar o projeto em um servidor com URL pública

## Comparativo
| | GitHub Pages | Vercel |
|---|---|---|
| Roda Node | não | sim |
| Serve Next.js | só exportação estática | completo |
| Deploy automático | sim | sim |

## Analogia
GitHub Pages é uma vitrine de cartazes impressos. Vercel é uma cozinha que prepara o prato na hora.