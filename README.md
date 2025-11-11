# Clusterização de Países — Projeto de Aprendizado Não Supervisionado

Este repositório contém o notebook e artefatos do trabalho de **Clusterização de Países** com base em dados socioeconômicos e de saúde do Kaggle.

---

## 🧩 Estrutura

- `country_clustering.ipynb` — Notebook Jupyter completo com explicações teóricas curtas e código executável.
- `requirements.txt` — Lista de dependências para recriar o ambiente.
- `perfil_clusters_kmeans.csv` — Saída opcional gerada com o perfil médio de cada cluster (salvo ao rodar o notebook).

---

## 🚀 Execução no macOS

1. **Crie um ambiente virtual**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```

3. **Baixe o dataset**
   - Acesse: [Kaggle - Unsupervised Learning on Country Data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)
   - Coloque o arquivo `Country-data.csv` na mesma pasta do notebook.

4. **Rode o Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Abra `country_clustering.ipynb` e execute célula por célula.

---

## 📊 Objetivo

Aplicar técnicas de **clusterização não supervisionada** para agrupar países em 3 grupos com base em indicadores socioeconômicos e de saúde.

Algoritmos utilizados:
- **K-Means**
- **Clusterização Hierárquica (Ward)**
- Discussão sobre **K-Medoids** e **DBSCAN**

---

## ✨ Resultados esperados

- Interpretação dos grupos formados (ex.: países desenvolvidos, em desenvolvimento e subdesenvolvidos).
- Comparação entre métodos (semelhanças e diferenças).
- Visualizações com gráficos e dendrograma.

---

## 📁 Créditos

Dataset: [Kaggle - Unsupervised Learning on Country Data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)  
Autor do notebook: Felipe Rocha
