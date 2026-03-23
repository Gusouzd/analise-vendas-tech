📊 Análise de Vendas - Tech

📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma análise exploratória e tratamento de dados de vendas de uma empresa do setor de tecnologia.

A base de dados foi tratada, enriquecida e analisada com foco em gerar insights relevantes sobre faturamento, desempenho por loja, produtos mais vendidos e análise de metas.


🛠️ Tecnologias utilizadas

- Python
- Pandas
- NumPy


📂 Base de Dados

O projeto utiliza duas bases:
- vendas_tech.csv → Contém os dados de vendas
- gerentes_lojas.xlsx → Contém informações dos gerentes e metas


🔍 Etapas do Projeto

1. Importação e inspeção dos dados
- Leitura dos arquivos CSV e Excel
- Análise inicial com:
   .info()
   .describe()
   .head() / .tail()

2. Tratamento de dados
- Remoção de colunas desnecessárias
- Tratamento de valores nulos
- Conversão de tipos (datas)
- Padronização de textos (nomes de lojas)
- Remoção de duplicatas

3. Criação de novas colunas
- Faturamento → Preço * Quantidade
- Forma de Venda → Online ou Presencial
- Região → Classificação por localização das lojas

4. Análises realizadas

📈 Ranking de faturamento por loja
Identifica quais lojas geram mais receita.
🛒 Produtos mais vendidos (Online)
Mostra os produtos com maior volume de vendas no canal online.

🏬 Análise cruzada
- Produtos mais vendidos por loja
- Lojas que mais vendem cada produto

🎯 Análise de metas
Verificação de quais gerentes bateram a meta em janeiro de 2023.

📅 Evolução de vendas ao longo do tempo
- Agrupamento por mês
- Visualização da tendência de faturamento


📤 Exportações

Foram gerados arquivos com dados filtrados:

- Vendas SP.csv → Vendas da loja de São Paulo
- Vendas 2024.csv → Vendas do ano de 2024


💡 Principais Insights (exemplo)

- Diferença de desempenho entre lojas físicas e online
- Identificação de regiões mais lucrativas
- Produtos com maior volume de vendas
- Acompanhamento de metas por gerente


🚀 Possíveis melhorias futuras
- Criação de dashboards no Power BI
- Análises preditivas (forecast de vendas)
- Segmentação de clientes
- KPIs mais avançados


📎 Como executar o projeto
# Clone o repositório
- git clone https://github.com/Gusouzd/analise-vendas-tech.git

# Instale as dependências
- pip install pandas numpy

# Abra o Jupyter Notebook
- jupyter notebook
- Em seguida abra o arquivo "pandas_supremo.ipynb"

Gustavo Rafael
📍 São Paulo - SP
📧 gurafael@hotmail.com.br
🔗 https://www.linkedin.com/in/gustavorafael09

⭐ Observação

Este é um projeto de portfólio com foco em demonstrar habilidades em análise e tratamento de dados utilizando Python.
