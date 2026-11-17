# DAATIUM · Manual de Marca v4 (Manchete)

Fonte única de verdade da marca. **Substitui integralmente** toda identidade anterior: azul `#004AAD` com Poppins e Playfair (v1-v2), dourado com Cormorant (v3.0.0) e A COSTURA com Newsreader (v4.0.0). Nenhum material novo usa qualquer elemento visual delas. Em caso de conflito com qualquer outro documento, skill ou template, vale este.

Versão: 4.1 · Novembro de 2026 · Dono: Mário Almeida

---

## 1. Essência

DAATIUM é a plataforma pessoal de Mário Almeida em três frentes: **palestras, mentoria executiva e conselhos**. O formato de apresentação é o de um portfólio de palestrante sênior: ativos escaneáveis (temas, números, palcos, clientes) antes de narrativa.

**Âncora (três frases canônicas, nesta ordem):**
1. Velocidade virou commodity.
2. Direção virou o ativo escasso.
3. Meu trabalho é direção.

**Personalidade visual:** vivo, direto, com peso de palco. Cartaz editorial sobre papel claro, um único acento elétrico. Autoridade pela clareza e pela escala, não por ornamento.

## 2. O nome

- **Daat**: raiz hebraica (דעת), o conhecimento que só existe por experiência, que muda quem o carrega.
- **-ium**: sufixo latino que nomeia os elementos químicos, a substância que não se decompõe mais.
- **Grafia:**
  - Marca (wordmark, rótulos, rodapé, OG, capas): **DAATIUM**, em caixa alta.
  - Em texto corrido: **Daatium**, com inicial maiúscula ("a Daatium trabalha...").
  - Nunca "daatium" em minúsculas, nunca "DaatIum", nunca "Daat.ium".
- O hebraico דעת só aparece em conteúdo sobre a etimologia, com a fonte Noto Serif Hebrew (subset dos três glifos). Não é elemento da identidade de rotina.

## 3. Tipografia

Duas famílias. Não existe terceira.

| Voz | Família | Uso |
|---|---|---|
| **Manchete** | **Archivo**, eixo de largura **118%**, peso **900** (wordmark 800) | Wordmark, hero, títulos curtos de seção, números grandes, CTA |
| **Texto** | **Archivo**, largura 100%, pesos 400 a 800 | Títulos de tema e oferta (700 a 800), corpo (400), depoimentos |
| **Máquina** | **IBM Plex Mono** 400 e 500 | Rótulos, navegação, dados, fontes de pesquisa, cargos, botões |

Licença: ambas SIL Open Font License. Uso comercial livre, inclusive em PPTX, PDF, imagens e OG. Google Fonts.

### 3.1 Regra de caixa (inviolável)

- **CAIXA ALTA** somente em: wordmark, manchete do hero, títulos de seção de **até 4 palavras**, rótulos em Plex Mono, botões e números.
- **Caixa alta e baixa** em: títulos de tema e de oferta, corpo, depoimentos, biografia, nome em texto corrido.
- Qualquer título com mais de 4 palavras vai em caixa alta e baixa. Caixa alta em frase longa lê devagar e perde hierarquia.

### 3.2 Escala (web)

| Papel | Peso / largura | Tamanho |
|---|---|---|
| Hero | 900 / 118% | 26 a 92 px (fluido, `clamp(26px, 6.9vw, 92px)`) |
| Título de seção | 900 / 118% | 24 a 48 px |
| Números | 900 / 112% | 30 a 62 px |
| Título de tema | 700 / 100% | 22 a 34 px |
| Título de oferta | 800 / 100% | 26 a 36 px |
| Corpo | 400 / 100% | 18 px, entrelinha 1,6 |
| Rótulo mono | 400 ou 500, caixa alta, tracking 0,1 a 0,2 em | 11 a 15 px |

A largura 118% ocupa mais espaço: em tela estreita, **reduza o tamanho, nunca a largura** (nada de fonte condensada no lugar).

### 3.3 Itálico

Não faz parte do sistema. A identidade anterior (Newsreader) usava itálico; esta não. Citações usam Archivo 400 com aspas cobalto.

## 4. Cor

**A marca tem três cores e uma luz.** Cor nova só entra por decisão deste manual.

| Token | Hex | Papel |
|---|---|---|
| `papel` | `#F7F6F1` | Fundo padrão |
| `tinta` | `#121419` | Texto, filetes, faixas e fundos escuros |
| `cobalto` | `#2B32FF` | Acento único: palavra em destaque, bloco invertido, botões, links |
| `cobalto-luz` | `#7C82FF` | Cobalto para **texto pequeno sobre tinta** |
| `neu` | `#5A5E6B` | Secundário sobre papel |
| `neu-esc` | `#9CA1B0` | Secundário sobre tinta |

**Contrastes verificados (WCAG):**

| Par | Razão | Uso permitido |
|---|---|---|
| tinta sobre papel | 17,03:1 | Todo texto |
| neu sobre papel | 5,97:1 | Texto secundário |
| cobalto sobre papel | 6,46:1 | Texto e botões |
| papel sobre cobalto | 6,46:1 | Texto no bloco invertido |
| neu-esc sobre tinta | 7,14:1 | Texto secundário em fundo escuro |
| cobalto-luz sobre tinta | 5,70:1 | Texto pequeno em fundo escuro |
| **cobalto sobre tinta** | **2,63:1** | **Proibido para texto. Só decorativo grande.** |

**Proporção:** 70% papel, 20% tinta, 10% cobalto. O cobalto é raro de propósito: quando aparece, é o ponto.

## 5. Logo e símbolo

- **Símbolo:** hexágono com núcleo circular. Geometria canônica imutável (viewBox `27.8 143.6 76.1 87.8`; arquivos em `assets/brand/v3/simbolo_*.svg`). Sempre monocromático, na cor do texto do contexto (tinta sobre papel, papel sobre tinta).
- **Wordmark:** **DAATIUM** em Archivo largura 118%, peso 800, caixa alta, tracking -1%.
- **Logo completo:** símbolo + wordmark lado a lado, símbolo à esquerda, espaço entre eles igual a 0,35 da altura do símbolo.
- **Área de respiro:** a altura do núcleo circular do símbolo, em todos os lados.
- **Tamanho mínimo:** símbolo 16 px (digital) ou 6 mm (impresso); logo completo 90 px de largura.
- **Favicon:** `assets/favicon/` (16, 32, 48, 180, 512), símbolo papel sobre fundo tinta.
- **Proibido:** colorir o símbolo de cobalto, inclinar, aplicar sombra ou gradiente, trocar a fonte do wordmark, usar os logos antigos (azul, dourado, Newsreader).

> Atenção: os arquivos `logo_*.svg` e `assinatura_*.svg` em `assets/brand/v3/` trazem o wordmark antigo em Newsreader e estão **obsoletos**. Valem apenas os `simbolo_*.svg` e os favicons. O logo completo deve ser montado com o símbolo mais o wordmark em Archivo, como no site.

## 6. Dispositivos gráficos

1. **Bloco invertido:** palavra-chave sobre bloco cobalto com texto papel, girado **-1,2°**, padding de 0,16 em na lateral. Uma por tela, no máximo.
2. **Filete:** linha de **2 px** tinta, separando seções, abaixo da navegação e sobre rodapés.
3. **Faixa tinta:** seção escura (números, newsletter, marquee de clientes) para quebrar o ritmo do papel.
4. **Marquee de clientes:** logos em movimento contínuo sobre faixa tinta (monocromáticos invertidos). Respeita `prefers-reduced-motion` (vira grade estática).
5. **Flood no hover:** cartões de oferta invertem para tinta ao passar o mouse. Transição de 180 ms.

Movimento é bem-vindo, mas sempre decorativo e desligável. Nenhum conteúdo depende de animação.

## 7. Fotografia

- **Sempre preto e branco.** Retratos e fotos de palco.
- **Receita (retrato sobre papel):** converter com peso no canal vermelho (`0,50 R + 0,38 G + 0,12 B`), normalizar entre os percentis 0,5 e 99,5, aplicar gamma 1,25, mapear para o intervalo 14 a 240, curva S leve. Resultado com pretos reais e camisa sem estourar.
- **Fotos de palco** (escuras na origem): autocontraste e remapeamento do ponto de preto para 66, de modo a não pesar sobre o papel.
- Proporção do retrato: 4:5. Sem cantos arredondados. Moldura de 2 px tinta.
- Sempre renomear o arquivo ao trocar a imagem (`_v2`, `_v3`) para furar cache.

## 8. Voz e copy

- Frases curtas, afirmativas, sem adjetivação.
- **Proibido:** travessões em texto próprio, exclamações, emojis, superlativos, linguagem motivacional, preços.
- Depoimentos são citações na íntegra: nunca editar, mesmo que contenham travessão ou "transformação digital".
- Rótulos e fontes em caixa alta mono. Dados sempre com fonte citada.
- Tom de quem decide, não de quem vende. Direto, sem justificar.

## 9. Tokens de implementação (web)

```css
:root{
  --papel:#F7F6F1; --tinta:#121419; --cobalto:#2B32FF; --cobalto-luz:#7C82FF;
  --neu:#5A5E6B; --neu-esc:#9CA1B0;
  --rule:2px solid var(--tinta);
  --display:'Archivo',system-ui,sans-serif;
  --mono:'IBM Plex Mono',ui-monospace,monospace;
}
/* manchete */ h1{ font-family:var(--display); font-weight:900; font-stretch:118%; text-transform:uppercase; letter-spacing:-.03em; line-height:.98 }
```

```html
<link href="https://fonts.googleapis.com/css2?family=Archivo:wdth,wght@62..125,400;500;600;700;800;900&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
```

## 10. Derivação para outros materiais

Princípio: todo material é um recorte do site. Mesmas fontes, mesma paleta, mesmos dispositivos.

### 10.1 PPTX e slides

- **16:9**, fundo `papel` por padrão; `tinta` para slides de impacto (número, tese, fechamento).
- **Fontes:** Archivo (Black, Expanded) e IBM Plex Mono precisam estar **instaladas** na máquina que abre o arquivo, ou embutidas. Sem isso o PowerPoint substitui por Arial e quebra a identidade. Alternativa segura: exportar PDF.
- **Tipos de slide:**
  - *Número*: valor em Archivo 900 expandida (grande), unidade em bloco cobalto invertido, fonte em mono.
  - *Tese*: uma frase em Archivo 900 caixa alta, palavra-chave em bloco cobalto.
  - *Lista de temas*: numeração em mono (01, 02), título em Archivo 700, descrição em 400.
  - *Citação*: aspas cobalto grandes, texto Archivo 400, autor em mono.
  - *Dado com fonte*: sempre rodapé mono com a origem da pesquisa.
- Topo de cada slide: filete tinta de 2 px com wordmark à esquerda e rótulo da seção em mono à direita. Rodapé em mono: cliente, "CONFIDENCIAL", daatium.com.
- Cobalto nunca ocupa mais de 10% do slide. Sobre fundo tinta, texto cobalto usa `cobalto-luz`.

### 10.2 PDF de portfólio de palestras
Mesma lógica do site: capa em manchete, uma página por tema, página de números, página de palco. A versão atual (`palestras.pdf`) ainda está em A COSTURA e precisa ser regenerada neste sistema.

### 10.3 OG e redes sociais
- OG: 1200 x 630, fundo papel, manchete em Archivo 900 expandida caixa alta, bloco cobalto no último termo, faixa tinta inferior com a linha de superfícies em mono. Arquivo vigente: `assets/og-daatium-archivo.png`. Ao alterar, renomear.
- LinkedIn (capa e avatar): avatar usa o símbolo em papel sobre tinta; capa segue a manchete.

### 10.4 E-mail e assinatura
Texto simples em Archivo ou fonte do sistema, nome em caixa alta e baixa, wordmark DAATIUM em caixa alta mono abaixo do nome. Sem imagens pesadas.

## 11. Documentos e ativos obsoletos

Os itens abaixo não valem mais e não devem ser usados como referência de estilo:

- `daatium-identidade-v3.md`, `daatium-costura.html`, `daatium-sistema-apresentacoes-v3.md`, `daatium-project-instructions-v3.md`, `prompt-code-lp-costura.md` e `daatium_qa.py` (A COSTURA, em `/Users/ma/Downloads/DAATIUM-v3 2/docs/`).
- `_materiais/DAATIUM_Brand_Guide.pdf`, `DAATIUM_Template.pptx`, `DAATIUM_TEASER_v2026.pptx`, `DAATIUM_Apresentacao_2026.pptx`, `DAATIUM_Clientes_Slide.pptx` e `daatium-presentation-template.html` (identidade azul).
- `PortfolioPalestras_2026_v3.pdf` e `palestras.pdf` (A COSTURA, a regenerar).
- Logos completos em `assets/brand/v3/logo_*` e `assinatura_*` (wordmark Newsreader).
- A skill de apresentações `daatium-presentations`, se ainda aponta para a paleta azul ou dourada: precisa ser atualizada com as seções 3, 4 e 10 deste manual.
- Cores aposentadas (não podem reaparecer em nenhum arquivo): `#004AAD`, `#C2A260`, `#8A744A`, `#7A6336`, `#EFE8D8`, `#131109`, `#524A3B`, `#E4DCC8`, `#B9B2A1`, `#A79C85`, `#1C1910`, `#ECEDEA`, `#4B4F52`, `#98A1A7`, `#227586`. Fontes aposentadas: Poppins, Playfair Display, Helvetica Now, Cormorant Garamond, Spectral, Frank Ruhl Libre, Newsreader, Space Grotesk.

## 12. Checklist antes de publicar qualquer peça

1. Só Archivo e IBM Plex Mono? Nenhuma outra família?
2. Caixa alta apenas em wordmark, manchete, títulos de até 4 palavras, rótulos e números?
3. Cores só dos seis tokens? Cobalto nunca como texto sobre tinta?
4. No máximo um bloco cobalto invertido por tela?
5. Fotos em preto e branco com a receita da seção 7?
6. Zero travessões, exclamações, emojis e preços no texto próprio?
7. Nenhuma cor ou fonte da lista de aposentadas?
8. Arquivo de imagem renomeado se substituiu um existente?

## 13. Histórico

| Versão | Data | Mudança |
|---|---|---|
| 1 a 2 | abr/2026 | Identidade azul (Poppins, Playfair) |
| 3.0 | jul/2026 | Dourado, Cormorant, tema escuro (tag `v3.0.0`) |
| 4.0 | jul/2026 | A COSTURA: Newsreader, sem cor de marca (tag `v4.0.0`) |
| **4.1** | **nov/2026** | **Manchete: papel, tinta e cobalto; Archivo expandida + Plex Mono; formato portfólio** |
