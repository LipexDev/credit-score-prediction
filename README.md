# 📊 Previsão de Score de Crédito de Clientes

Este projeto utiliza algoritmos de Machine Learning em Python para classificar automaticamente o score de crédito de clientes nas categorias **Good (Bom)**, **Standard (Ok)** e **Poor (Ruim)**.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python
- **Análise de Dados:** Pandas
- **Machine Learning:** Scikit-Learn (`RandomForestClassifier`, `KNeighborsClassifier`)

## 📈 Resultados do Modelo
- **Random Forest Classifier:** ~83% de acurácia
- **K-Nearest Neighbors (KNN):** ~74% de acurácia

O modelo **Random Forest** apresentou o melhor desempenho e foi utilizado para realizar as predições em novos clientes.

## 📁 Estrutura do Repositório
- `data/`: Bases de dados de treino e teste em CSV.
- `notebooks/`: Análises exploratórias e treinamento dos modelos em Jupyter Notebook.
