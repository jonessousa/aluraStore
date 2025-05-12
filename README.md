# 📊 Análise de Desempenho das Lojas - Alura Store

Este projeto tem como objetivo analisar os dados de vendas de **quatro lojas fictícias da Alura Store**, com o intuito de recomendar ao Sr. João **qual loja vender ou encerrar**, baseado em métricas reais de desempenho como faturamento, avaliações, frete médio e produtos vendidos.

---

## 📁 Dados Utilizados

Os dados foram fornecidos em formato `.csv`, contendo informações como:
- Produto e categoria
- Preço e frete
- Avaliação dos clientes
- Tipo de pagamento
- Localização geográfica (latitude e longitude)

Cada loja tem seu próprio conjunto de dados.

---

## 🧪 Etapas da Análise

O notebook é dividido em 5 categorias principais:

### 1. 📈 Análise do Faturamento
- Soma de **Preço + Frete** para calcular o faturamento total por loja.
- Representação visual com gráfico de barras.
- ![image](https://github.com/user-attachments/assets/653f412b-f693-414b-ae61-1e8b5b333a23)


### 2. 🛍️ Vendas por Categoria
- Identificação da **categoria de produto mais vendida** em cada loja.
- Mostra a representatividade da categoria mais forte (% de vendas).

### 3. ⭐ Média de Avaliação das Lojas
- Cálculo da **média das avaliações** dadas pelos clientes após a compra.
- Gráfico de comparação entre as lojas.
- ![image](https://github.com/user-attachments/assets/1e8ccd38-ed1f-469a-9097-23d9fc87e4cf)


### 4. 🔝 Produtos Mais e Menos Vendidos
- Levanta o produto **com maior e menor número de vendas** por loja.
- Permite entender o apelo dos produtos junto ao público.

### 5. 🚚 Frete Médio por Loja
- Cálculo da **média de frete cobrado** por cada loja.
- Ajuda a entender o impacto nos custos para o consumidor.
- ![image](https://github.com/user-attachments/assets/67973393-a9ce-4a86-9806-58fc005b4fd7)


---

## ✅ Recomendação Final

Utilizamos uma análise multicritério, considerando:

- Faturamento (quanto a loja vende)
- Avaliação média (satisfação dos clientes)
- Frete médio (custos ao consumidor)

Cada métrica é **normalizada** (ajustada para uma escala de 0 a 1), e uma **pontuação final** é atribuída para cada loja. A loja com **menor pontuação geral é recomendada para venda**.

---

## 📎 Como Executar

1. Faça o upload do notebook `.ipynb` no [Google Colab](https://colab.research.google.com)
2. Envie também os arquivos `.csv` de cada loja
3. Execute as células sequencialmente
4. Veja os gráficos e a recomendação final no final do notebook

