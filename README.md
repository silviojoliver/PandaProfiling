# PandaProfiling

Gera relatórios de perfil a partir de um DataFrame do pandas. A função pandas df.describe () é excelente, mas um pouco básica para análises exploratórias sérias de dados. pandas_profiling estende o pandas DataFrame com df.profile_report () para análise rápida de dados.

Para cada coluna, as seguintes estatísticas - se relevantes para o tipo de coluna - são apresentadas em um relatório HTML interativo:

Inferência de tipo: detecta os tipos de colunas em um dataframe.
Fundamentos: tipo, valores únicos, valores ausentes
Estatísticas de quantis como valor mínimo, Q1, mediana, Q3, máximo, intervalo, intervalo interquartil
Estatísticas descritivas como média, modo, desvio padrão, soma, desvio absoluto mediano, coeficiente de variação, curtose, assimetria
Valores mais frequentes
Histograma
Destacamento de correlações de variáveis ​​altamente correlacionadas, matrizes de Spearman, Pearson e Kendall
Matriz de valores ausentes, contagem, mapa de calor e dendrograma de valores ausentes
A análise de texto aprende sobre categorias (maiúsculas, espaço), scripts (latino, cirílico) e blocos (ASCII) de dados de texto.
A análise de arquivos e imagens extrai tamanhos de arquivos, datas e dimensões de criação e verifica se há imagens truncadas ou que contêm informações EXIF.
