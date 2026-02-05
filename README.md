# 🌾 Smart Farming 2024: Eficiência de Insumos e Alerta Fitossanitário / Input Efficiency & Phytosanitary Alert

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Data Science](https://img.shields.io/badge/R%26D-Analytics-green)

[English](#english) • [Português](#portugues)

---

<a name="english"></a>
## 🇺🇸 English

### 📝 Project Overview
This project presents an advanced analysis of smart farming data, simulating a real-world **Research & Development (R&D)** scenario. The goal was to transform raw sensor and field data into operational efficiency metrics and phytosanitary safety protocols.

### 🔬 Technical Deep Dive & Methodology
The analysis was structured into four critical phases:

1. **Standardization & Data Cleaning:** - Mapping 22 variables from English to Portuguese to align with local technical teams.
   - Categorical mapping of crops (Wheat, Soybean, Maize, Cotton, Rice).
2. **Data Auditing (Quality Control):**
   - High-density missing data analysis (30% in irrigation types).
   - Implementation of standard imputation for categorical health status to prevent data loss.
3. **Advanced Feature Engineering:**
   - **Pesticide Efficiency Metric:** Calculated as $Yield (kg) / Input (ml)$. This allows for benchmarking regional performance regardless of farm size.
4. **Phytosanitary & Environmental Correlation:**
   - Analysis of "Severe Disease" clusters against ambient temperature and relative humidity averages to identify environmental triggers for crop stress.

### 📊 Project Highlights
* **Strategic Insight:** South India leads in input efficiency, while East Africa requires technical auditing due to low yield-to-input ratios.
* **Precision Agriculture:** Use of NDVI (Normalized Difference Vegetation Index) to correlate vegetative vigor with final yield.

---

<a name="portugues"></a>
## 🇧🇷 Português

### 📝 Resumo do Projeto
Este projeto apresenta uma análise avançada de dados de agricultura inteligente, simulando um cenário real de **Pesquisa e Desenvolvimento (P&D)**. O objetivo foi transformar dados brutos de sensores em métricas de eficiência operacional e protocolos de segurança fitossanitária.

### 🔬 Detalhamento Técnico e Metodologia
A análise foi estruturada em quatro fases críticas:

1. **Padronização e Limpeza:** - Mapeamento de 22 variáveis para o português para alinhamento com equipes técnicas locais.
   - Tradução e padronização das culturas (Trigo, Soja, Milho, Algodão, Arroz).
2. **Auditoria de Dados (Controle de Qualidade):**
   - Análise de densidade de dados faltantes (30% em tipos de irrigação).
   - Imputação estratégica de categorias padrão ("Saudável", "Desconhecido") para evitar descarte de amostras.
3. **Engenharia de Atributos Avançada:**
   - **Métrica de Eficiência de Pesticida:** Calculada como $Produtividade (kg) / Insumo (ml)$. Permite o benchmarking regional de performance.
4. **Correlação Fitossanitária:**
   - Cruzamento de casos de "Doença Severa" com médias de temperatura e umidade para identificar gatilhos ambientais de estresse na cultura.

### 📊 Destaques do Projeto
* **Insight Estratégico:** A região de South India lidera a eficiência, enquanto East Africa demanda auditoria técnica por baixo aproveitamento de insumos.
* **Agricultura de Precisão:** Uso do índice NDVI para correlacionar vigor vegetativo com o rendimento final.

---

## 📂 Repository Structure / Estrutura do Repositório

- 📄 [Smart_Farming_Analysis_2024.ipynb](./Smart_Farming_Analysis_2024.ipynb): Notebook com lógica completa e documentada.
- 📊 [Smart_Farming_2024_Final.csv](./Smart_Farming_2024_Final.csv): Dataset tratado com as novas métricas de eficiência.
- ⚠️ [alerta_fitossanitario_2024.csv](./alerta_fitossanitario_2024.csv): Relatório de exceções para ação imediata em campo.

---
👤 **Author:** Cleverson Moura Andrade
