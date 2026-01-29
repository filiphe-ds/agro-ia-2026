# 🌾 AgroForecast 2026: Previsão de Vigor Vegetativo via IA e Satélite

## 🚀 Demonstração em Tempo Real
**Acesse o Dashboard Interativo:** [Clique aqui para abrir o App](https://agro-ia-2026-n2ov3dyptzkbxkqfhgvfoj.streamlit.app/)

---

## 📋 Sobre o Projeto
Este projeto implementa um sistema de monitoramento e previsão de saúde da cana-de-açúcar para a região de Ribeirão Preto/SP. Utilizando dados de satélite (**Sentinel-2**) e dados climáticos da **NASA POWER**, o modelo de Inteligência Artificial prevê o índice NDVI (vigor da planta) com 7 dias de antecedência, permitindo decisões preventivas no manejo agrícola.

## 🛠️ Stack Tecnológica
* **Dados:** API NASA POWER e Imagens de Satélite (NDVI).
* **Linguagem:** Python 3.
* **Bibliotecas:** Pandas, Scikit-Learn, Streamlit, Plotly.
* **Algoritmo:** Random Forest Regressor.

## 🧠 Inteligência e Feature Engineering
O diferencial deste modelo é a criação de atributos que simulam a "memória" da planta perante o clima:
* **Janelas Móveis:** Acumulado de chuva de 15 e 30 dias (essencial para culturas de sequeiro).
* **Lags Temporais:** Médias móveis de temperatura e umidade do solo.
* **Sazonalidade:** Tratamento de variáveis cíclicas para captar períodos de safra e entressafra.

> **Performance:** O modelo atingiu um **R² Score de 0.72**, demonstrando alta capacidade preditiva para as variações de campo.

---

## 🖥️ Estrutura do Repositório
1.  **Pipeline de Treinamento:** Notebook `.ipynb` documentado com análise exploratória (EDA) e validação estatística.
2.  **Camada de Entrega (App):** Dashboard interativo que atua como um **Agente Agrônomo**, gerando recomendações técnicas automáticas baseadas nas previsões da IA.

---
**Desenvolvido por Filiphe** [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/filipheassuncao/)
