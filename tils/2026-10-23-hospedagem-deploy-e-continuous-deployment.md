# Hospedagem, deploy e continuous deployment

## O que aprendi

- **Hospedagem:** deixar o site em um servidor que fica ligado e acessível pela internet
- **Deploy:** o ato de publicar uma nova versão do projeto nesse servidor
- **Continuous deployment:** o deploy acontece automaticamente a cada mudança no código
- **CI (integração contínua):** etapa automática que valida o código quando ele chega ao repositório
- A forma de hospedar evoluiu com o tempo, cada vez com mais etapas automatizadas

## Evolução

```
Antes:  PC  →  Servidor              (envio manual)
Hoje:   PC  →  CI  →  Build  →  Servidor    (automático)
```

## Fluxo no devnews

```
git push → GitHub → Vercel (CI + build) → site atualizado
```

## Analogia

Antes, o dono levava cada produto até a loja. Hoje existe uma esteira: ele deixa o produto na entrada e a esteira confere, embala e coloca na vitrine.
