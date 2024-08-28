# Combinação de Planilhas Excel

Este projeto contém um código em Python, implementado em um Jupyter Notebook, que realiza a combinação de dados de múltiplas abas de uma planilha Excel. Algumas abas são ignoradas conforme especificado no código.

## Contexto

A ideia para este projeto surgiu a partir da necessidade de combinar dados de uma pasta de trabalho do Excel que continha uma aba para cada dia, todas com a mesma estrutura de dados. Para realizar análises mais detalhadas, foi necessário combinar todas essas abas em uma única planilha consolidada.


## Uso

1. O notebook começa com a importação da biblioteca `pandas`, essencial para a manipulação dos dados.
2. Em seguida, um arquivo Excel é carregado, e os nomes das abas são identificados.
3. O código combina os dados de todas as abas, exceto aquelas que foram especificadas para serem ignoradas:
   - Abas ignoradas incluem: `VALORES`, `PAGAMENTOS`, `BASE`, `MODELO NOVO`, e `ANALISE`.
   - Os dados de cada aba são concatenados em um único DataFrame.

4. Após a execução do notebook, os dados combinados estarão prontos para análises adicionais ou exportação para outros formatos.
