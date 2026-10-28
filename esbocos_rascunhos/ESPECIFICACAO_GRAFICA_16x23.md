# Especificação técnica para a gráfica: A Bíblia do Leilão Imobiliário

Data: 25/10/2026. Versão: primeira edição, teste (brochura, preto e branco).

## Miolo
- Formato de acabamento: **16 × 23 cm** (160 × 230 mm).
- Páginas: **80** em português (77 de conteúdo + 3 em branco para fechar o múltiplo de 4). Em inglês: **76** páginas.
- Impressão: **preto e branco** (escala de cinza, somente preto).
- Papel: **offset 90 g/m²**.
- Sangria do miolo: sem imagens que cheguem à borda. Se a gráfica exigir, 2,5 mm.
- Margens do miolo: 19 mm (interna), 15 mm (externa), 18 mm (topo), 20 mm (base).
- Fontes: todas incorporadas no PDF (DejaVu Serif e Sans).
- Arquivos: `LIVRO_MIOLO_BW_160x230.pdf` (PT) e `LIVRO_MIOLO_EN_BW_160x230.pdf` (EN).
- Cores: a versão colorida será gerada depois, a partir do mesmo código, quando houver orçamento para impressão em cores.

## Capa
- Papel: **couché 300 g/m²**, laminação fosca (a confirmar com a gráfica).
- Formato: **16 × 23 cm**, **sem orelhas**.
- Sangria: **2,5 mm** em todos os lados, conforme o gabarito da gráfica.
- Margem de segurança: **5 mm** a partir do corte.
- Acabamento: brochura, sem margem de vinco (o gabarito da gráfica mostra margem de vinco de 0,7 cm; vale perguntar se é necessária para brochura).
- Tamanho total (frente + lombada + verso + sangrias):
  - **Português (80 págs.):** 160 + 4,0 + 160 + 5 = **329 mm** × **235 mm** (lombada estimada em 4,0 mm).
  - **Inglês (76 págs.):** 160 + 3,8 + 160 + 5 = **328,8 mm** × **235 mm** (lombada estimada em 3,8 mm).
- O gabarito da gráfica tem 335 mm de largura e lombada de cerca de 10 mm. Essa lombada não corresponde ao miolo de 80 páginas em offset 90 g. **A gráfica deve confirmar a espessura real** antes da arte final.

## Textos da capa
- Frente: título, subtítulo "Compre seu Imóvel com até 60% de Desconto" e nome do autor.
- Lombada: somente "A BÍBLIA DO LEILÃO IMOBILIÁRIO", sem nome do autor, e apenas se a espessura confirmada for de pelo menos 4 mm.
- Verso: textos conforme `TEXTO_CONTRACAPA.md` e o briefing do editor.
- Código de barras: área de 50 × 30 mm em branco, para o ISBN, que só será registrado depois do texto final.

## Perguntas para o orçamento
1. Espessura real da lombada para 80 páginas em offset 90 g.
2. Se precisam de sangria de 2,5 mm no miolo ou se aceitam sem sangria.
3. Se a capa couché 300 g aceita laminação fosca e se a margem de vinco do gabarito é necessária.
4. Prova digital e exemplar de prova impresso antes da tiragem.
5. Formato de entrega (PDF/X-1a, CMYK para capa, escala de cinza para o miolo).
