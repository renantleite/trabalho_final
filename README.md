<h1 align="center">Preço de Imóveis por m²: Análise e Predição</h1>

Entender o valor dos imóveis é essencial para evitar preços injustos e tomar decisões melhores na hora de comprar, vender ou investir. Fatores como metrô, idade do prédio e infraestrutura do bairro influenciam muito no preço, e analisar dados ajuda a enxergar isso com mais clareza, e nem sempre é facil de entender se o preço é justo , por isso, usaremos modelos preditivos para ajudar.
## Metodologia
Este projeto utiliza o [Real Estate Valuation](https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set) para prever o prever o valor dos imóveis por metro quadrado, identificando padrões e tendências por meio de técnicas de [Ciência de Dados](https://en.wikipedia.org/wiki/Data_science) e [Aprendizado de Máquina](https://en.wikipedia.org/wiki/Machine_learning). Realizamos uma Análise Exploratória dos dados, preparações para garantir a qualidade dos dados e uma Análise Comparativa de Modelos para identificar o melhor modelo preditivo.

##  Objetivos do Projeto

### 🔹 **Regressão**
Prever o **preço por m²** de um imóvel com base em suas características:
- idade do edifício  
- distância ao metrô (transformada em escala logarítmica)  
- número de lojas na região  
- localização (latitude/longitude)  
- ano e mês da transação  
- categoria da idade (novo, médio, antigo)

>  **Melhor modelo:** Random Forest Regressor  
> Explica ~81% da variação nos preços e apresenta o menor erro médio.

---

### 🔹 **Classificação**
Identificar se um imóvel pertence ao grupo dos **25% mais caros** da base de dados  
(`alto_preco = 1`) ou não (`= 0`).

>  **Melhor modelo:** Logistic Regression  
> Acurácia de ~90%, precisão de ~93% e recall de ~67%.

---

##  Metodologia

- **Passos realizados:**  
  ✔ Analise Exploratoria  
  ✔ Criação de novas features (log da distância, faixa de idade, perto do metrô)  
  ✔ Divisão entre treino/teste  
  ✔ Comparação de modelos (Regressão Linear, Random Forest, XGBoost, Logistic Regression)  
  ✔ Avaliação com métricas adequadas para cada (MAE, RMSE, R², Accuracy, Precision, Recall, F1)

---

## Desenvolvedores
 - [Renan Teixeira](https://github.com/renantleite)
 - [Tiago Magalhães](https://github.com/magalhaestiago)
