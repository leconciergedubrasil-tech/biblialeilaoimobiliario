# Auditoria: A Bíblia do Leilão Imobiliário

Data: 23/10/2026
Escopo: leitura direta dos arquivos em /mnt/user-data/outputs. Nenhum arquivo foi alterado nesta etapa.

---

## 1. Volume real do livro (CRÍTICO)

| Arquivo | Palavras (aprox.) |
|---|---|
| A_BIBLIA_DO_LEILAO_IMOBILIARIO_COMPLETO.txt | 8.098 |
| THE_BIBLE_OF_REAL_ESTATE_AUCTIONS_ENGLISH.txt | 8.027 |
| 01_FRONT_MATTER.html | 1.389 |
| 02_PARTE_I_FUNDAMENTO.html | 1.282 |
| 03_PARTES_II_III_CAMINHO_NEGÓCIO.html | 1.539 |
| 04_PARTES_IV_V_ESTRATÉGIA_PERIGO.html | 1.405 |
| 05_PARTES_VI_VII_APENDICES.html | 2.141 |

Os HTMLs somam cerca de 7.750 palavras de texto visível. A análise editorial e o projeto citam ~47.000 palavras e 188 páginas. **Esses números não são sustentados pelos arquivos.** Eu repeti esse número nas conversas anteriores sem verificá-lo. A obra atual é um guia curto, na faixa de 30 a 40 páginas diagramadas em A5, e não 188.

Consequência: o planejamento de gráfica, o orçamento e o preço de capa foram calculados para um livro que não existe nesse tamanho.

## 2. Subtítulo "até 94% de desconto" (CONFIRMADO)

- Aparece no TXT (linha 3), no HTML de capa/front matter (linhas 192, 211, 494) e no prefácio.
- O próprio Capítulo 19.1 diz que o golpe do "imóvel com 94% de desconto" deve ser desconfiado e que os descontos reais ficam entre 30% e 60%.
- Nenhum caso do livro chega perto de 94%.

**Conclusão:** o livro contradiz o próprio título. Correção necessária.

## 3. Projeção de R$ 812 milhões (CONFIRMADO)

- TXT, linhas 864 e 891: "30 anos: R$ 812.000.000" a partir de R$ 100.000.
- Não há desconto de inflação, impostos, vacância nem custos.

**Conclusão:** deve ser removida ou substituída por cenário com premissas explícitas.

## 4. Capítulo 22 existe em duas versões (CONFIRMADO, com correção)

- Na análise anterior eu disse que o caso 22.2 do TXT estava truncado. **Essa afirmação estava errada.** O caso 22.2 do TXT tem tabela completa: compra R$ 300.000, custos R$ 70.000, venda R$ 370.000, lucro zero, ROI 0%.
- O HTML (05_PARTES_VI_VII) traz outro caso 22.2, "Belo Horizonte — High Volume". O conteúdo é diferente.

**Conclusão:** há duas versões do caso 22.2 e não há indicação de qual é a oficial.

## 5. Caso 22.4 com título e tabela divergentes (CONFIRMADO)

- Título: "O imóvel que rendeu 65% de lucro em 6 meses".
- Tabela: lucro R$ 130.000 sobre investimento de R$ 220.000, ROI de 59,1%.

**Conclusão:** título e tabela não batem. Um dos dois precisa mudar.

## 6. Taxa de poupança (CONFIRMADO, parcialmente)

- TXT, Cap. 14 (linha 744): poupança "~6%".
- HTML, front matter: "contas de poupança ou alguns títulos que giram em torno de 12% ao ano".
- Não verifiquei na tabela do Cap. 14 do HTML qual valor aparece. Recomendo conferir antes de corrigir.

**Conclusão:** há pelo menos duas taxas diferentes para a poupança e a referência de 12% aparece no prefácio como comparação com um ganho de 12 meses. Os números precisam ser reconciliados com uma tabela-âncora.

## 7. Credenciais do autor (CONFIRMADO)

- TXT, linhas 1808-1810: "141 certificações globais, incluindo credenciamentos pela ONU e pela Interpol".
- Não há documento anexo nem forma de verificação no texto.

**Conclusão:** recomendo remover ou reduzir ao que pode ser comprovado.

## 8. Disclaimer de risco e conflito de interesse (CONFIRMADO AUSENTE)

- Busca por "CVM", "não constitui" e "não é recomendação" em todos os arquivos: zero resultados.
- O livro promove o Hercleus Terminal e o AVVISI, sem declarar o interesse.

**Conclusão:** precisa ser adicionado.

## 9. Erros de digitação e redação (CONFIRMADO)

- "Bom afternoon" (01_FRONT_MATTER.html, linha 329): mistura de idiomas no prefácio.
- "Gastuei" (01_FRONT_MATTER.html, linha 337): deve ser "gastei".
- Não verifiquei "dividas" no glossário nem "Nomer arquivo" no guia de diagramação. A busca nos arquivos de front matter e TXT não encontrou essas palavras, mas não revisei os demais arquivos.

## 10. Vila Madalena contada mais de uma vez (CONFIRMADO)

- A história aparece no TXT (3 ocorrências), no front matter (1), no HTML 03 (1) e no HTML 05 (2).
- Os valores coincidem na história principal (R$ 180.000 → R$ 320.000), mas a repetição é excessiva.

## 11. Arquivo 04 duplicado com "(1)" (NÃO CONFIRMADO)

- Não encontrei nenhuma versão duplicada. A listagem tem apenas 04_PARTES_IV_V_ESTRATÉGIA_PERIGO.html.
- **Essa afirmação da análise editorial não se sustenta.** Pode ter sido de outra cópia que não está neste diretório.

## 12. Paginação e sumário (NÃO VERIFICADO)

- Não abri os HTMLs no navegador nem gerei PDF, então não sei a paginação real.
- A afirmação de que o sumário aponta para páginas erradas precisa de teste de impressão.

---

## Resumo do estado atual

| Item | Situação |
|---|---|
| Volume (palavras/páginas) | Divergente dos números citados. CRÍTICO |
| Subtítulo "94%" | Contradito pelo próprio livro. CRÍTICO |
| Projeção R$ 812 milhões | Indefensável. CRÍTICO |
| Cap. 22 em duas versões | Confirmado. ALTO |
| Caso 22.4 (65% vs 59,1%) | Confirmado. MÉDIO |
| Poupança (6% vs 12%) | Confirmado. MÉDIO |
| Credenciais não verificáveis | Confirmado. ALTO |
| Disclaimer e conflito de interesse | Ausente. ALTO |
| Erros de digitação | Confirmados alguns. BAIXO |
| Arquivo 04 duplicado | Não confirmado. Removido da lista |
| Paginação dos HTMLs | Não verificado |

## Correções minhas nesta conversa

1. Afirmei que os 5 HTMLs estavam "validados" e "print-ready" sem tê-los aberto. Não foram validados.
2. Os orçamentos, prazos e margens (79-87%) nos guias são estimativas sem base verificada.
3. Afirmei que o caso 22.2 do TXT estava truncado. Não está.
4. Repeti o número de 47.000 palavras e 188 páginas sem conferir.

## Próximos passos sugeridos (aguardando sua decisão)

1. Decidir o tamanho real da obra: manter como guia curto, ou expandir até a extensão prometida no título.
2. Escolher o subtítulo: sugiro "Guia prático para comprar imóveis em leilão", ou uma promessa que os casos sustentem, como "até 60% abaixo do valor de mercado".
3. Remover a projeção de R$ 812 milhões.
4. Escolher a versão oficial do caso 22.2 e corrigir o título do 22.4.
5. Reconciliar a taxa da poupança com uma tabela única.
6. Reduzir as credenciais ao que pode ser comprovado.
7. Adicionar disclaimer de risco e declaração de conflito de interesse.
8. Só depois refazer a diagramação e pedir orçamento.
