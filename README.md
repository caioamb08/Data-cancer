# Classificação de tumores de mama (Breast Cancer Wisconsin)

Projeto de aprendizado de máquina para classificar tumores como benignos ou malignos a partir de 30 características numéricas.

## Etapas
1. Limpeza dos dados (remoção de coluna vazia e do id, conversão do diagnóstico para 0/1)
2. Divisão treino/teste (70/30, estratificada)
3. Comparação de 9 algoritmos com validação cruzada de 5 folds
4. Ajuste da regressão logística com GridSearchCV
5. Teste com pacientes reais do conjunto de teste

## Resultado
O melhor modelo foi a regressão logística, com 98,48% de acurácia na validação cruzada e 95,32% no teste.

## Como rodar
```bash
pip install -r requirements.txt
jupyter lab
```
Abra o notebook `data_cancer_completo.ipynb` e execute as células em ordem.

## Dados
Breast Cancer Wisconsin (Diagnostic), disponível na UCI Machine Learning Repository e no Kaggle.

## Aviso
Projeto de estudo. Não deve ser usado para diagnóstico médico.
