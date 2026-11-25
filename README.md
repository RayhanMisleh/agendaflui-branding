# Agenda Flui — marca

Identidade do Agenda Flui. É a fonte do design do painel, do site e do app: eles copiam os valores daqui, nada é importado em tempo de execução.

## Conteúdo

- `Agenda-Flui-Manual-da-Marca.pdf`: manual (ideia, logo, cores, fontes, voz). Comece por ele. Há uma cópia dentro de `AgendaFlui-Marca/`.
- `AgendaFlui-Marca/logos/svg` e `logos/png`: logos (horizontal, símbolo, pet, versões negativas; PNG em @2x e @4x, fundo transparente).
- `AgendaFlui-Marca/fontes`: Bricolage Grotesque (títulos) e Figtree (texto), variáveis, ambas do Google Fonts.
- `AgendaFlui-Marca/design-tokens/agenda-flui-tokens.json`: cores (tema claro e escuro, com uso de cada uma), tamanhos de texto, espaçamentos e cantos.
- `AgendaFlui-Marca/site`: landing de referência em HTML e capturas.
- `AgendaFlui-Marca/LEIA-ME.txt`: resumo do pacote. No SVG o nome "agenda flui" é texto; converta em curvas antes de enviar para gráfica.

## Regras

- Cor-assinatura: Água (`brand`). Acento quente: Caramelo, nunca como cor de texto.
- Tokens têm tema claro e escuro; texto em `brand` sobre `ground` passa contraste 4.5:1 nos dois.
- Mudou um token aqui: replique em `painel/` (`src/ui/styles/tokens.css`), `site/` (`app/globals.css`) e `app/` (`src/theme/tokens.js`).
