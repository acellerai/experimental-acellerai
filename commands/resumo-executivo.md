---
description: Gera um resumo executivo de uma página do último relatório de fechamento anual da GMI
argument-hint: "[ano]"
---

Gere um resumo executivo de uma página a partir do relatório de fechamento anual da GMI.

Ano pedido: $ARGUMENTS (se vier vazio, use o relatório mais recente).

1. Localize o arquivo `relatorio-fechamento-anual-gmi-AAAA` entre os anexos e os arquivos desta conversa. Se o
   usuário informou um ano, use o relatório desse ano. Se não houver relatório, peça o arquivo e pare.
2. Use só números que estão no relatório. Não recalcule, não estime e não traga dados de outros arquivos.
3. Monte o resumo com no máximo 350 palavras, para caber em uma página:
   - título "Resumo executivo · Fechamento anual GMI AAAA";
   - a mensagem principal do ano em uma frase;
   - cinco números: receita bruta, EBITDA e margem, lucro líquido, caixa gerado pelas operações e atingimento da
     meta, cada um com a referência (meta ou orçado);
   - três destaques positivos e três pontos de atenção;
   - se o relatório tiver comparativo com o ano anterior, duas linhas: o que mais melhorou e o que mais piorou;
   - três decisões ou próximos passos para a Diretoria.
4. Mostre o resumo na conversa e salve como `resumo-executivo-fechamento-anual-gmi-AAAA.docx`.
5. Não envie e-mail e não salve no Drive.
