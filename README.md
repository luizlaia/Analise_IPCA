# Análise do IPCA - Últimos 30 Anos

## Descrição
Este repositório contém os resultados da análise do Índice Nacional de Preços ao Consumidor Amplo (IPCA) dos últimos 30 anos. A análise inclui o acumulado anual, médias dos últimos 5 anos (desconsiderando o período da pandemia) e a avaliação da taxa de crescimento, destacando períodos de aceleração e desaceleração.

## Ferramentas Utilizadas

- **PySpark (Databricks):** Utilizado para processamento e análise dos dados.
- **Power BI:** Responsável pela visualização e apresentação gráfica dos resultados.

## Fonte dos Dados

Os dados foram extraídos da API do **Banco Central do Brasil** em formato JSON, abrangendo os últimos 30 anos de informações do IPCA.

## Metodologia

1. **Extração de Dados:**
   - Coleta de dados via API do Banco Central.
   
2. **Processamento:**
   - Limpeza e tratamento dos dados utilizando PySpark no ambiente Databricks.
   - Cálculo do acumulado anual do IPCA.

3. **Análise:**
   - Cálculo da média dos últimos 5 anos, desconsiderando o período da pandemia.
   - Avaliação da taxa de crescimento para identificar períodos de aceleração e desaceleração do IPCA.

4. **Visualização:**
   - Criação de dashboards interativos no Power BI para apresentação dos resultados.

## Resultados

Os resultados incluem:
- Gráficos do acumulado anual do IPCA.
- Média dos últimos 5 anos (sem o impacto da pandemia).
- Análise da taxa de crescimento, com destaque para períodos de aceleração e desaceleração.
