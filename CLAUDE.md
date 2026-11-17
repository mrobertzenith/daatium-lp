# DAATIUM · Contexto do projeto

Landing page de daatium.com (HTML único em `index.html`, GitHub Pages, domínio `www.daatium.com`). Plataforma pessoal de Mário Almeida: palestras, mentoria executiva e conselhos.

## Antes de qualquer trabalho visual ou de copy

Leia e siga **`docs/DAATIUM-manual-de-marca.md`**. É a fonte única da identidade e **substitui qualquer documento, skill ou template anterior** (azul, dourado, A COSTURA, Space Grotesk, Newsreader). Em conflito, o manual vence.

## Resumo operacional (detalhes no manual)

- **Fontes:** Archivo (manchete: largura 118%, peso 900; texto: 400 a 800) + IBM Plex Mono. Nenhuma terceira família.
- **Cores:** papel `#F7F6F1`, tinta `#121419`, cobalto `#2B32FF`, cobalto-luz `#7C82FF` (texto pequeno sobre tinta), neu `#5A5E6B`, neu-esc `#9CA1B0`. Cobalto sobre tinta como texto é proibido (2,63:1).
- **Caixa:** alta só em wordmark, manchete, títulos de até 4 palavras, rótulos mono, botões e números. Tudo o mais em caixa alta e baixa. Nome em texto corrido: "Daatium"; como marca: "DAATIUM".
- **Copy:** sem travessões, exclamações, emojis, superlativos ou preços. Depoimentos intocáveis. Âncora: "Velocidade virou commodity. Direção virou o ativo escasso. Meu trabalho é direção."
- **Fotos:** sempre P&B, receita no manual (seção 7). Ao trocar imagem, renomear o arquivo (`_v2`, `_v3`) para furar cache.
- **Mobile:** 360 px sem overflow horizontal; reduzir o tamanho da fonte, nunca a largura da Archivo.

## Operação

- Preview local: servidor `daatium-lp` (porta 8765, `.claude/launch.json`).
- Deploy: push em `main` dispara GitHub Actions para o Pages. O Pages exige repositório público no plano Free.
- Backups por tag git: `v1.0.0` (azul), `v3.0.0` (dourado), `v4.0.0` (A COSTURA). A versão atual de marca é a 4.1.
- Derivar materiais (PPTX, PDF, OG, LinkedIn): seção 10 do manual.
