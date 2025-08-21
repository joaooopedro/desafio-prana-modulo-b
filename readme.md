# 📦 Desafio Prana -- Módulo B (Estoque)

## 🔹 1. Tratamento dos dados

-   As planilhas originais vieram separadas em múltiplas abas (**Sala 1,
    Sala 2, Sala 3, Sala 4, Ju, Ka, Fa**).\
-   Realizei a **limpeza e consolidação**:
    -   Removi colunas vazias e padronizei nomes de campos.\
    -   Organizei as abas de salas em uma **tabela de estoque atual**,
        com colunas `Produto`, `Estoque_Atual` e `Estoque_Minimo`.\
    -   Nas abas **Ju, Ka, Fa**, identifiquei que os dados representam
        **movimentações** (entradas/saídas), mas não estão estruturados
        com clareza suficiente para automatizar uma análise mais
        profunda sem transformação adicional.

------------------------------------------------------------------------

## 🔹 2. Decisões e limitações

-   ❌ **Custo Unitário**: não foi disponibilizado. Por isso, não foi
    possível calcular o **Valor total em estoque**.\
-   ❌ **Categoria e Fornecedor**: não estavam presentes nos dados.
    Assim, não foi possível aplicar filtros ou segmentações por esses
    campos.\
-   ⚠️ **Tipo de Movimentação (Entrada/Saída)**: as abas de
    movimentações não trazem de forma padronizada se o lançamento é
    entrada ou saída, o que dificulta separar os fluxos com segurança.
    Para atender ao desafio, considerei apenas a possibilidade de
    contabilizar **saídas**, mas documentei a limitação.

------------------------------------------------------------------------

## 🔹 3. Relatório entregue

📊 O relatório final em **Excel** contém:
- ✅ **KPI 1 -- Itens abaixo do mínimo**
- ❌ **KPI 2 -- Valor em estoque**: não pôde ser entregue por falta de
dados de custo.\
- ✅ **Gráfico Top 5 Saídas**: utilizei as abas de movimentações, mas
ressaltei a necessidade de dados mais claros para diferenciar entradas
de saídas de forma confiável.

------------------------------------------------------------------------

## 🔹 4. Possíveis melhorias na base

Para uma análise mais robusta e completa, a base deveria conter:\
- 💲 **Coluna de Custo Unitário** para cada item.\
- 🏷️ **Categoria** e **Fornecedor** vinculados a cada produto.\
- 🔄 **Identificação clara do tipo de movimentação** (Entrada, Saída,
Devolução etc.), com datas padronizadas.\
- 📂 **Consolidação única** em vez de múltiplas abas, facilitando a
automação no Power BI ou Excel.

------------------------------------------------------------------------

📌 **Resumo**: O dashboard foi construído dentro das possibilidades
reais dos dados fornecidos, com destaque para o monitoramento dos itens
abaixo do mínimo e a visão simplificada de movimentações. Limitações
importantes foram documentadas e melhorias foram sugeridas para
viabilizar análises financeiras e operacionais mais ricas.
