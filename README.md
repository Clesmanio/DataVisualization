# Imigração para o Canadá (1980–2013)

Notebook de estudo que usa dados de 195 países para explorar a imigração para o Canadá. A série anual do Brasil é usada para mostrar como preparar os dados e ajustar a apresentação dos gráficos.

## Análise

1. Ler a base com pandas e inspecionar os campos e tipos de dados.
2. Selecionar os registros do Brasil e extrair os valores anuais entre 1980 e 2013.
3. Construir gráficos e ajustar eixos, rótulos e escala. O notebook reúne exemplos com Matplotlib, Seaborn e Plotly.

## Como consultar ou executar

Abra [datavisualization.ipynb](./datavisualization.ipynb) para consultar o código e as saídas salvas. Para executar, use Jupyter ou Colab com as bibliotecas `pandas`, `matplotlib`, `seaborn` e `plotly` instaladas.

A base `imigrantes_canada.csv` precisa ser obtida separadamente. O notebook procura o CSV em `/content/imigrantes_canada.csv`. No Jupyter local, ajuste a chamada de `read_csv` para o caminho onde você salvou o arquivo.
