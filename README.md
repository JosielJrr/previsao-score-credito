# 🧠 Python IA: Previsão de Score de Crédito com Machine Learning

Este projeto usa inteligência artificial para prever o score de crédito de clientes de um banco. A partir de dados históricos, o modelo classifica novos clientes como tendo um score **Ruim**, **Ok** ou **Bom**.

## 📌 Objetivo

Criar um modelo de machine learning capaz de prever automaticamente a classificação de crédito de novos clientes com base em dados históricos.

## 🗂️ Etapas do Projeto

### ✅ Passo 1: Importar e visualizar a base de dados

- Lê a base `clientes.csv`.
- Visualiza os dados pra entender a estrutura inicial.

### ✅ Passo 2: Preparar os dados (tratamento)

- Converte colunas com texto em números usando `LabelEncoder`.

### ✅ Passo 3: Separar dados para treino e teste

- Separa a coluna que será prevista das que serão usadas na previsão.
- Divide os dados em treino e teste com `train_test_split`.

### ✅ Passo 4: Criar e treinar modelos de IA

- Cria dois modelos: `RandomForestClassifier` e `KNeighborsClassifier`.
- Treina os modelos com os dados de treino.

### ✅ Passo 5: Avaliar desempenho dos modelos

- Avalia com `accuracy_score`.
- Compara a acurácia os dois modelos pra escolher o melhor.

### ✅ Passo 6: Fazer previsões com novos dados

- Lê a base `novos_clientes.csv`.
- Converte colunas com texto em números usando `LabelEncoder`.
- Prevê o score com o modelo escolhido.
- Adiciona o resultado na tabela.

## 📊 Resultado Final

Ao fim do processo, é gerado um dataframe com os novos clientes e suas respectivas classificações de score de crédito previstos pelo modelo.

## 🧪 Tecnologias Utilizadas

- Python 3.x
- Pandas
- Scikit-learn
- Jupyter Notebook

## 📌 Observação

Modelos de score de crédito não exigem 100% de acurácia. Neste projeto, uma boa taxa de acerto (>80%) já é considerada suficiente para aplicação prática no contexto bancário.

> Projeto criado na **Jornada Python** da [Hashtag Programação](https://www.youtube.com/@HashtagProgramacao).
