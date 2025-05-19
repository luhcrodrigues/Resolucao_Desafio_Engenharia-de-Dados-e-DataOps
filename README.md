# README.md - Análise de Dados do E-commerce Brasileiro (Olist)


## 🎯 Objetivo do Projeto

Este projeto tem como objetivo realizar uma análise completa do conjunto de dados da Olist, uma plataforma de e-commerce brasileira. O foco é extrair **insights estratégicos** sobre vendas, entregas, satisfação de clientes e comportamento de compra, com o intuito de apoiar decisões de negócio.

## 🧩 Problemas de Negócio Abordados

- Como melhorar a retenção de clientes?
- Como prever e evitar atrasos na entrega?
- Como segmentar os clientes para estratégias personalizadas?
- Qual a relação entre avaliação do cliente e desempenho operacional?

## 📁 Estrutura do Projeto

O projeto está organizado nas seguintes seções:

1. **Preparação dos Dados**: Importação, limpeza, normalização e criação de um modelo relacional.
2. **Análise Exploratória de Dados**: Investigação de padrões, tendências e relações nos dados.
3. **Solução de Problemas de Negócio**: Modelagem preditiva e análise de cluster.
4. **Visualização e Dashboards**: Criação de visualizações interativas para apresentar os resultados.

## 📊 Conjunto de Dados

O conjunto de dados utilizado é o ["Brazilian E-commerce Public Dataset by Olist"](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce ), contendo informações sobre 100.000 pedidos entre 2016 e 2018, distribuídos em 9 arquivos CSV:

- `olist_customers_dataset.csv`
- `olist_geolocation_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_order_payments_dataset.csv`
- `olist_order_reviews_dataset.csv`
- `olist_orders_dataset.csv`
- `olist_products_dataset.csv`
- `olist_sellers_dataset.csv`
- `product_category_name_translation.csv`

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn (Random Forest, KMeans, PCA)
- SQLite (para modelagem relacional)

## ▶️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-olist.git 
   cd projeto-olist
