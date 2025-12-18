# 📋 Manual de Integração: Modelo de Predição de Churn (ChurnInsight)

Este documento descreve como integrar o modelo de Machine Learning para predição de churn na infraestrutura de Back-end. O modelo foi desenvolvido para identificar clientes com alta probabilidade de cancelamento, permitindo ações preventivas de retenção.

## 1. Arquivos Incluídos no Pacote
* `pipeline_churn_modelo.joblib`: O Pipeline completo serializado (inclui Imputação, Escalonamento, Encoding e o Modelo Random Forest).
* `app.py`: Script de exemplo da API utilizando Flask para servir o modelo.
* `Telecom_churn.csv`: Base de dados original utilizada para o treinamento (referência de colunas).

## 2. Requisitos do Sistema
O ambiente de execução deve ter o Python 3.10 ou superior instalado com as seguintes dependências:

```bash
pip install pandas numpy scikit-learn joblib flask
