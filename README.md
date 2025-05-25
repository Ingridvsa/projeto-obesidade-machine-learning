# 🤖 Projeto de Classificação de Obesidade com Machine Learning

Este projeto tem como objetivo realizar uma análise exploratória e construir modelos de classificação para prever o grau de obesidade com base em variáveis relacionadas ao estilo de vida, hábitos alimentares e dados antropométricos.

---

## 📂 Estrutura do Projeto

```
projeto-obesidade-machine-learning/
├── dados/ # Base de dados original
│ └── Obesity prediction.csv
├── notebooks/ # Cadernos Jupyter com análise
│ └── IA_e_DataScience__Equipe_06.ipynb
├── imagens/ # Gráficos gerados para EDA
│ ├── Boxplots para variáveis numéricas.png
│ ├── Boxplots para verificar outliers depois do tratamento.png
│ ├── Gráficos de barras para variáveis categóricas.png
│ ├── Gráficos de dispersão.png
│ ├── Histogramas.png
│ ├── Mapa de calor de correlação com mais variáveis.png
│ └── Matriz de correlação para variáveis numéricas.png
├── modelo_rf.joblib # Modelo Random Forest treinado (opcional)
├── requirements.txt # Bibliotecas utilizadas
└── README.md
```

---

## 🧠 Tecnologias e Bibliotecas Utilizadas

- Python 3.13+
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Joblib
- Pickle (via pickle-mixin)

---

## 📊 Análise Exploratória de Dados (EDA)

Durante a EDA foram gerados os seguintes gráficos:

- 📈 **Histogramas com curva de densidade** para distribuição de variáveis numéricas
- 📦 **Boxplots** antes e depois do tratamento de outliers
- 📊 **Gráficos de barras** para análise de variáveis categóricas
- 🔁 **Gráficos de dispersão** para verificar tendências e padrões
- 🧩 **Matriz de correlação** entre variáveis numéricas
- 🔥 **Mapa de calor** com variáveis selecionadas

> Todos os gráficos estão salvos na pasta `/imagens`.

---

## 🧪 Modelagem

Foram testados diversos algoritmos de classificação supervisionada:

- **Logistic Regression**
- **Decision Tree**
- **Random Forest** (modelo com melhor desempenho)
- **MLPClassifier** (Rede Neural Multicamadas)

### 📐 Avaliação de desempenho:
- Matriz de confusão
- Relatório de classificação (`classification_report`)
- Comparação entre os modelos

> O melhor modelo foi salvo com o uso da biblioteca `joblib`.

---

## ⚙️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/Ingridvsa/projeto-obesidade-machine-learning.git
```

2. Instale as dependênicas:
```
pip install -r requirements.txt
```
3.Execute o notebook:
Abra o arquivo **notebooks/IA_e_DataScience__Equipe_06.ipynb** no VS Code (com a extensão Jupyter instalada) ou no Jupyter Notebook tradicional.
