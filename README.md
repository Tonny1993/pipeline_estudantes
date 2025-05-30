
# Projeto de Machine Learning: Avaliação de Alunos na Turquia

Este projeto implementa uma esteira de aprendizado de máquina usando o conjunto de dados `TurkiyeStudentEvaluation.csv`.

## Etapas Realizadas

1. **Carregamento dos Dados**: Importação do dataset com 5820 avaliações de alunos.
2. **Estatísticas Descritivas**: Resumo estatístico de todas as colunas.
3. **Transformações**:
   - Colunas: Padronização das respostas das questões (Q1–Q28).
   - Linhas: Remoção de duplicatas.
4. **Divisão dos Dados**:
   - Treino: 60%
   - Validação: 20%
   - Teste: 20%
5. **Treinamento do Modelo**: Random Forest Classifier.
6. **Avaliação**:
   - Acurácia: 74.84%
   - Matriz de Confusão: fornecida no notebook.
7. **Predição Exemplar**: Previsão do número de repetições para um aluno.

## Como Executar

1. Clone este repositório ou baixe os arquivos.
2. Certifique-se de ter Python 3.x e instale as dependências:
   ```bash
   pip install pandas scikit-learn
   pip install kagglehub[pandas-datasets]
   ```
3. Execute o notebook `pipeline_estudantes.ipynb` em um ambiente Jupyter ou Google Colab.

## Arquivos

- `TurkiyeStudentEvaluation.csv`: Conjunto de dados.
- `pipeline_estudantes.ipynb`: Notebook com toda a esteira de ML.
- `README.md`: Este arquivo.