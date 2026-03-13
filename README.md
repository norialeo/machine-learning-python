🧠 Previsão de Score de Crédito com Machine Learning

Este projeto utiliza Machine Learning em Python para prever o score de crédito de clientes com base em diferentes características financeiras e comportamentais.

O modelo é treinado utilizando uma base de dados histórica contendo informações de clientes e seus respectivos scores de crédito. Após o treinamento, o sistema é capaz de prever o score de novos clientes a partir de seus dados.

O projeto compara dois algoritmos de Machine Learning para avaliar qual apresenta melhor desempenho na classificação dos scores de crédito.

⚙️ Tecnologias utilizadas

Python

Pandas

Scikit-learn

Jupyter Notebook

Machine Learning

Random Forest

K-Nearest Neighbors (KNN)

🧪 Como o projeto funciona

1️⃣ Carregamento da base de dados

O projeto começa carregando os dados de clientes utilizando Pandas.

2️⃣ Pré-processamento dos dados

Algumas colunas categóricas precisam ser convertidas para valores numéricos para que os modelos de Machine Learning consigam processá-las.

Para isso é utilizado:

LabelEncoder

Campos transformados:

profissão

mix de crédito

comportamento de pagamento

3️⃣ Separação entre treino e teste

Os dados são divididos em:

70% para treinamento

30% para teste

Utilizando:

train_test_split
4️⃣ Treinamento dos modelos

Dois algoritmos são utilizados para comparação:

Random Forest

K-Nearest Neighbors (KNN)

Os modelos são treinados com os dados de treino.

5️⃣ Avaliação dos modelos

O desempenho dos modelos é avaliado utilizando:

accuracy_score

Isso permite verificar qual modelo apresenta maior precisão na previsão do score de crédito.

6️⃣ Previsão para novos clientes

Após o treinamento, o modelo é utilizado para prever o score de crédito de novos clientes utilizando a base:

novos_clientes.csv

O sistema então gera a previsão automática para cada cliente.

📊 Objetivo do projeto

Este projeto demonstra:

aplicação prática de Machine Learning

pré-processamento de dados

treinamento e avaliação de modelos

uso de Python para análise de dados

criação de um sistema de previsão baseado em dados
