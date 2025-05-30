# 📊 Projeto de Machine Learning: Avaliação de Alunos na Turquia
Este repositório apresenta um pipeline completo de aprendizado de máquina para análise e predição de avaliações estudantis na Turquia, com base no conjunto de dados Turkiye Student Evaluation do kagglehub.

## 🚀 Visão Geral do Pipeline

### 📥 Carregamento de Dados

Dataset com 5.820 registros de avaliações de alunos da Turquia.

### 📊 Análise Exploratória

Estatísticas descritivas para todas as colunas.

### 🛠️ Pré-processamento

Colunas: Padronização das respostas das questões Q1–Q28.

Linhas: Remoção de entradas duplicadas.

### 🔀 Divisão dos Dados

Treinamento: 60%

Validação: 20%

Teste: 20%

### 🤖 Treinamento do Modelo

Algoritmo utilizado: Random Forest Classifier

### 📈 Avaliação do Modelo

Acurácia: 74.84%

Matriz de confusão

![image](https://github.com/user-attachments/assets/07dc6738-1099-4910-acdf-1d12c9ee942c)


### 🎯 Predição

Estimativa do número de repetições para um aluno específico.

## 🧪 Como Executar o Projeto
Clone este repositório ou baixe o arquivo .ipynb.

Instale os pacotes necessários com:

   ```bash
   pip install pandas scikit-learn
   pip install kagglehub[pandas-datasets]
   ```
Execute o notebook `pipeline_estudantes.ipynb` em um ambiente Jupyter ou Google Colab.

## 📁 Estrutura do Projeto

- `pipeline_estudantes.ipynb`: Notebook com toda a esteira de ML.
- `README.md`: Este arquivo de documentação.
