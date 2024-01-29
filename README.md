# Analise da Taxa de Natalidade USA 

Leitura e Pré-processamento de Dados:

Dados de nascimentos são lidos de um arquivo CSV (births.csv) usando a biblioteca pandas.
Os primeiros registros do DataFrame são exibidos.

Limpeza e Manipulação de Dados:
Valores ausentes na coluna 'day' são preenchidos com 0 e convertidos para inteiros.
É criada uma nova coluna 'decade' representando a década correspondente a cada ano.

Análise Inicial da Taxa de Natalidade por Década e Gênero:
É criada uma tabela dinâmica (pivot table) para analisar a soma de nascimentos por década e gênero.
Os primeiros registros do DataFrame após as manipulações são exibidos.

Visualização Inicial da Taxa de Natalidade por Década e Gênero:
Gráfico de barras é gerado para visualizar a taxa total de natalidade por década e gênero.

Exploração Adicional e Remoção de Outliers:
Quartis são calculados para identificar valores atípicos na coluna 'births'.
Um intervalo robusto é definido para cortar valores atípicos.
A coluna 'day' é convertida para inteiros.
O índice do DataFrame é ajustado para representar as datas em um formato de data padrão.

Visualização da Taxa de Natalidade por Dia da Semana:
Uma tabela dinâmica é utilizada para calcular a média de nascimentos por dia da semana e década.
Um gráfico de linhas é gerado para visualizar a média de nascimentos por dia da semana ao longo das décadas.

Visualização da Taxa de Natalidade por Dia do Ano:
Uma tabela dinâmica é utilizada para calcular a média de nascimentos por mês e dia.
Um gráfico de linhas é gerado para visualizar a média de nascimentos ao longo do ano.
