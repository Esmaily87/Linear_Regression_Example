# Análise de Vendas e Modelagem Preditiva

Este projeto realiza uma análise exploratória de dados de vendas e aplica técnicas de regressão para prever comportamentos futuros. Ele inclui limpeza de dados, visualizações estatísticas, testes de normalidade, padronização e construção de modelos preditivos.

## 📊 Objetivos

- Análise estatística dos dados de vendas.
- Visualização de distribuições e correlações.
- Aplicação de testes de normalidade.
- Criação de pipeline com `scikit-learn`.
- Avaliação de desempenho com métricas como MAE, MSE e R².

## 🧰 Bibliotecas Utilizadas

- `pandas`
- `seaborn`
- `matplotlib.pyplot`
- `scikit-learn`
  - `Pipeline`, `LinearRegression`, `StandardScaler`, `SimpleImputer`
  - `train_test_split`, `mean_absolute_error`, `mean_squared_error`, `r2_score`
  - `OneHotEncoder`, `OrdinalEncoder`, `ColumnTransformer`
- `scipy.stats`
  - `shapiro`, `kstest`, `zscore`, `probplot`
- `pingouin` (`pg`)

## 📁 Estrutura do Projeto

```
sales_simples.ipynb      # Notebook principal com todo o código
README.md                # Este arquivo
```

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/Esmaily87/sales_simples.git
cd sales_simples
```

2. Instale as dependências (recomenda-se ambiente virtual):

```bash
pip install -r requirements.txt
```

3. Abra o notebook:

```bash
jupyter notebook sales_simples.ipynb
```

## 📈 Métricas de Avaliação

Durante o processo, o modelo é avaliado com as seguintes métricas:

- `MAE`: Mean Absolute Error
- `MSE`: Mean Squared Error
- `R²`: Coeficiente de Determinação

## 📌 Observações

- O notebook inclui visualizações gráficas e análise estatística com `pingouin`.
- Testes de normalidade (`Shapiro`, `Kolmogorov-Smirnov`) ajudam a decidir se os dados precisam de transformações.
- Pipelines são utilizados para garantir reprodutibilidade.

## 👤 Autor

- **Esmaily Peixoto**  
  - [GitHub](https://github.com/Esmaily87)  
  - [LinkedIn](https://www.linkedin.com/in/esmaily-peixoto-03448398)

---

Sinta-se à vontade para contribuir com melhorias!
