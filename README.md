# 💵 Análise da Cotação do Dólar em 2023

## 📌 Sobre o projeto
Este projeto foi parte do processo seletivo do Ciclo 15 | Python para Análise de Dados (Pretalab) e teve como objetivo avaliar minha familiaridade com o uso de Python para análise de dados, incluindo leitura de arquivos CSV, inspeção inicial do dataset e criação de um gráfico simples.

A análise foi realizada a partir de um dataset público, com foco em explorar os dados, tratar a variável de data e visualizar o comportamento da moeda ao longo do tempo.

---

## 📊 Dataset
- Fonte: Banco Central do Brasil  
- Período: janeiro a dezembro de 2023  
- Frequência: dados diários  
- Variável principal:
  - `valor`: cotação do dólar em reais (R$)

---

## 🛠️ Ferramentas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib

---

## 🧹 Etapas da análise

### 1. Leitura dos dados
- Importação do arquivo CSV diretamente de uma URL
- Visualização inicial com `.head()`

### 2. Tratamento dos dados
- Conversão da coluna `data` para o formato datetime
- Definição da coluna de data como índice do dataframe

### 3. Análise temporal
- Agrupamento dos dados por mês com `resample('ME')`
- Cálculo da média mensal com `.mean()`

### 4. Visualização
- Criação de gráfico de linha da média mensal
- Ajuste de título, rótulos e tamanho da figura

---

## 📈 Principais análises

- Evolução mensal da cotação do dólar
- Comparação entre início e final do ano
- Identificação de oscilações ao longo do período

---

## 🔍 Principais insights

- O dólar iniciou o ano de 2023 em valores mais altos
- Ao longo dos meses, apresentou uma leve tendência de queda
- No segundo semestre, manteve-se mais estável
- Não houve variações extremamente bruscas ao longo do ano

---

## 💡 Conclusão

- A análise mostra que o dólar apresentou oscilações ao longo de 2023, com uma leve tendência de queda ao longo do ano. Esse comportamento pode estar relacionado a fatores econômicos e mudanças ao longo do período. 
- Apesar das variações, o comportamento geral foi relativamente estável.

---

## ⚠️ Limitações

- A análise não considera fatores econômicos externos
- Não foram aplicados modelos estatísticos ou preditivos
- O foco foi apenas na visualização e análise descritiva


---

## 👩🏽‍💻 Autora
Elisabeth Aparecida Ribeiro  
Estudante em transição de carreira para a área de dados
