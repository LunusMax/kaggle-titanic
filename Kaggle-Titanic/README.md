# Titanic - Machine Learning from Disaster

## Description (Descrição)
This project tackles the famous Titanic problem available on Kaggle, where the goal is to predict the survival of passengers based on features such as age, sex, socio-economic class, etc.

Este projeto aborda o famoso problema do Titanic disponível no Kaggle, onde o objetivo é prever a sobrevivência dos passageiros com base em características como idade, sexo, classe socioeconômica, etc.

## Project Structure (Estrutura do Projeto)

- **scripts**: Contains notebooks with different approaches to solve the problem. (Contém os notebooks com diferentes abordagens para resolver o problema.)
  - `naive-bayes.ipynb`: Implementation using the Naive Bayes algorithm. (Implementação utilizando o algoritmo Naive Bayes.)
  - `RandomForestClassifier.ipynb`: Implementation using the Random Forest Classifier. (Implementação utilizando o Random Forest Classifier.)
  - `RandomForestClassifier_MultiData.ipynb`: Implementation using the Random Forest Classifier with multiple datasets. (Implementação utilizando o Random Forest Classifier com múltiplos conjuntos de dados.)

- **outputs**: Contains CSV files with predictions made by the models. (Contém os arquivos CSV com as previsões realizadas pelos modelos.)
  - `NaiveBayes.csv`: Public Score: 0.76555
  - `RandomForestClassifier.csv`: Public Score: 0.77511
  - `RandomForestClassifier_multiData.csv`: Public Score: 0.77751

- **database**: Contains the data provided by Kaggle. (Contém os dados fornecidos pelo Kaggle.)
  - `test.csv`: Test data. (Dados de teste.)
  - `train.csv`: Training data. (Dados de treino.)

## Scripts

### naive-bayes.ipynb
This notebook applies the Naive Bayes algorithm to predict the survival of passengers. The result obtained was a public score of 0.76555.

Este notebook aplica o algoritmo Naive Bayes para prever a sobrevivência dos passageiros. O resultado obtido foi um score público de 0.76555.

### RandomForestClassifier.ipynb
This notebook uses the Random Forest Classifier to make predictions. This method improved the score to 0.77511.

Este notebook utiliza o Random Forest Classifier para realizar a previsão. Este método melhorou o score para 0.77511.

### RandomForestClassifier_MultiData.ipynb
This notebook also uses the Random Forest Classifier but with multiple datasets. This method achieved the best public score of 0.77751.

Neste notebook, também foi utilizado o Random Forest Classifier, porém, com múltiplos conjuntos de dados. Este método obteve o melhor score público de 0.77751.

## Outputs
The generated CSV files contain the predictions made by the models for the test dataset. The columns are:
- `PassengerId`: ID of the passenger.
- `Survived`: Survival prediction (0 = Did not survive, 1 = Survived).

Os arquivos CSV gerados contêm as previsões feitas pelos modelos para o conjunto de dados de teste. As colunas são:
- `PassengerId`: ID do passageiro.
- `Survived`: Previsão de sobrevivência (0 = Não sobreviveu, 1 = Sobreviveu).

## Database (Base de Dados)
The data used in the project is in the `database` folder:
- `train.csv`: Training dataset provided by Kaggle.
- `test.csv`: Test dataset provided by Kaggle.

Os dados utilizados no projeto estão na pasta `database`:
- `train.csv`: Conjunto de dados de treino fornecido pelo Kaggle.
- `test.csv`: Conjunto de dados de teste fornecido pelo Kaggle.

## How to Use (Como Utilizar)
1. Clone this repository. (Clone este repositório.)
   ```sh
   git clone https://github.com/your-username/your-repository.git
