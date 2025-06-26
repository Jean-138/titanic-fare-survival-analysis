Análise: Tarifa e Sobrevivência no Titanic

Este projeto analisa a relação entre o valor pago pela passagem (Fare) e a chance de sobrevivência no Titanic, segmentando os dados por sexo (Sex) e classe (Pclass). A análise foi realizada utilizando a biblioteca pandas, com visualizações geradas pelo matplotlib.

Objetivo

Investigar se passageiros que pagaram tarifas mais altas tiveram maior chance de sobreviver. A análise considera se essa relação se mantém entre todos os grupos ou apenas em alguns segmentos específicos.

Etapas da análise

1. Carregamento e limpeza dos dados (arquivo train.csv)
2. Seleção das colunas relevantes: Fare, Survived, Sex, Pclass
3. Agrupamento dos dados por sexo, classe e situação de sobrevivência
4. Cálculo das médias de tarifa para sobreviventes e não sobreviventes
5. Comparação percentual entre os grupos
6. Geração de gráficos de barras com matplotlib
7. Conclusão escrita de forma clara, voltada para a interpretação por não técnicos

Conclusão

Para os homens, quanto maior a tarifa paga, maior foi a chance de sobrevivência, em todas as classes.

Para as mulheres, essa relação só se confirmou na segunda classe. Na primeira e na terceira classes, as sobreviventes pagaram menos, em média.

Estrutura do projeto

analise.ipynb       - Notebook principal com o código e visualizações
tarefa.txt           - Documento com a descrição do problema e etapas esperadas


Dataset

O arquivo train.csv pode ser obtido diretamente no site do Kaggle:

https://www.kaggle.com/c/titanic/data

Coloque o arquivo na mesma pasta do notebook antes de executá-lo

Como executar

1. Clone o repositório:
git clone https://github.com/seu-usuario/titanic-fare-survival-analysis.git

2. Instale as bibliotecas necessárias:
pip install pandas matplotlib

3. Execute o notebook:
jupyter notebook analise.ipynb
