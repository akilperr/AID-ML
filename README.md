# Predicción de Abandono de Clientes (Customer Churn)
## Descripción general
En este proyecto se aborda un problema de clasificación supervisada utilizando el dataset [**Telco Customer Churn**](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data).
El objetivo es predecir si un cliente de una compañía de telecomunicaciones abandonará el servicio (churn) en función de sus características contractuales y de consumo.
Este problema tiene relevancia empresarial real, ya que permite a las compañías anticiparse a la pérdida de clientes y aplicar estrategias de retención.

## Objetivo del proyecto
Desarrollar y comparar distintos modelos de Machine Learning para predecir la variable Churn, evaluando:
- El impacto del preprocesado de datos
- La selección de atributos
- La elección de métricas adecuadas
- El rendimiento de diferentes modelos

## Entorno de trabajo (Cachy OS)
- python3.12 -m venv env
- source env/bin/activate.fish
- pip install --upgrade pip
- pip install pandas numpy matplotlib seaborn scikit-learn jupyterlab
- pip freeze > requirements.txt
- jupyter lab
