# 🌊 Tecnicas Avançadas de Machine Learning

Este repositório apresenta um modelo de **Machine Learning** baseado em **Random Forest**.

---

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1irpq0D153ajc9I6eHjQ0LlrdYcFM5tdK)


## 📌 Visão Geral
Este projeto realiza:

### 📊 **Preparação dos Dados**
✔ Carregamento do conjunto de dados   
✔ Tratamento de valores ausentes  
✔ Conversão de variáveis categóricas para formato numérico 🔄  
✔ Seleção das features mais relevantes para a previsão 🎯  
✔ Divisão dos dados em conjunto de treino (70%) e teste (30%) 📚  

### **Redução Dimensionalidade com PCA:**
✔ Redução de Dimensionalidade → O PCA transforma muitos dados em poucos, mantendo a informação essencial.  
✔ Autovalores e Autovetores → Definem a importância e a direção das novas variáveis.  
✔ Variância Explicada → Escolhemos quantos componentes usar analisando a variância acumulada.  

### 🏋️ **Treinamento do Modelo**
✔ Ajuste do modelo com os dados de treino 📉  
 

### 📈 **Validação e Teste**
✔ Avaliação do modelo com dados de teste 📊  
✔ Medida de desempenho usando `accuracy_score` 📏  

### GridSearchCV
✔ GridSearchCV testa várias combinações de hiperparâmetros automaticamente.  
✔ Ele usa validação cruzada para escolher a melhor configuração do modelo.  
✔ Isso ajuda a otimizar modelos como Decision Trees, SVM e Random Forest. 🚀  

### Bagging
✔ Bagging treina vários modelos em subconjuntos aleatórios dos dados.  
✔ Suas previsões são combinadas para reduzir overfitting e melhorar a precisão.  
✔ O Random Forest é um exemplo famoso de Bagging com árvores de decisão.  

---

## 🛠 Tecnologias Utilizadas
- **Python** 🐍
- **Pandas** 📊
- **Scikit-Learn** 🤖
- **Matplotlib** 📉
- **Seaborn** 🎨

---
 
## 🔍 Melhorias Futuras
🔹 Escolher o número ideal de componentes no PCA  
🔹 Melhorar o GridSearchCV com mais hiperparâmetros  
🔹 Testar RandomizedSearchCV para otimização mais rápida  
🔹 Adicionar classification_report e confusion_matrix para melhor análise  

---


