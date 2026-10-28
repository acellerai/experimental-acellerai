---
description: Gera só o comparativo entre dois relatórios de fechamento anual da GMI (por exemplo, 2025 e 2026)
argument-hint: "[ano anterior] [ano atual]"
---

Compare dois relatórios de fechamento anual da GMI e entregue apenas o comparativo.

Anos pedidos: $ARGUMENTS (o primeiro é o ano anterior e o segundo, o ano atual; se vier vazio, use os dois
relatórios mais recentes disponíveis).

1. Localize os arquivos `relatorio-fechamento-anual-gmi-AAAA` dos dois anos entre os anexos e os arquivos desta
   conversa. Se faltar algum, diga qual falta e pare.
2. Monte a tabela Indicador | ano anterior | ano atual | Variação | Leitura. Variação em % para valores, em pontos
   percentuais (p.p.) para percentuais e em unidades para dias e pontos. Leitura: "melhorou", "piorou" ou
   "estável". Em custos, despesas, rotatividade, absenteísmo, inadimplência, avarias, prazo de entrega, custo de
   frete, ciclo de caixa e dívida, menor é melhor.
3. Use os números como estão em cada relatório. Indicador que só aparece em um dos dois fica como "não
   disponível". Não recalcule os anos com outros arquivos.
4. Depois da tabela: três pontos que melhoraram, três que pioraram e uma leitura de até cinco linhas.
5. Mostre na conversa e salve como `comparativo-fechamento-anual-gmi-AAAA-x-AAAA.docx` (ano atual primeiro).
6. Não envie e-mail e não salve no Drive.
