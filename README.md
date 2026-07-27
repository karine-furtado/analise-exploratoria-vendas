📊 Análise Exploratória de Dados de Vendas
Projeto da aula PY-06 para praticar Análise Exploratória de Dados (EDA) com Python no Google Colab.
O objetivo é explorar um conjunto de dados de vendas, identificar padrões semanais, gerar estatísticas descritivas e construir visualizações que apoiem a tomada de decisão.

📂 Conjunto de Dados
sales_data.csv — conjunto de dados original.

sales_data_analisado.csv — arquivo gerado ao final da análise contendo os dados tratados.

PY_06_EDA_Vendas_Colab.ipynb — notebook com inspeção, agrupamentos, visualizações e conclusões.

🛠️ Bibliotecas Utilizadas
Pandas

Matplotlib

Seaborn

Instalação:

bash
pip install pandas matplotlib seaborn notebook
📈 Etapas da Análise
Importação das bibliotecas.

Leitura do conjunto de dados (sales_data.csv).

Exploração inicial: estrutura, tipos, estatísticas descritivas.

Criação de atributos temporais e agrupamento por dia da semana.

Análise não visual (totais de vendas por dia).

Visualização com gráfico de barras.

Interpretação dos resultados e recomendações práticas.

Exportação do dataset tratado (sales_data_analisado.csv).

📊 Principais Conclusões
Terça-feira foi o dia mais forte, com maior volume de vendas (1000).

Quarta-feira e Domingo foram os dias mais fracos, com apenas 200 vendas cada.

Segunda-feira também apresentou desempenho elevado (700).

Sexta-feira manteve vendas consistentes (500).

O final de semana mostrou queda significativa, principalmente no domingo.

Esses resultados sugerem que o planejamento de estoque e campanhas promocionais devem ser ajustados conforme o comportamento semanal.

🎯 Recomendações
Aproveitar dias fortes: reforçar estoque e campanhas promocionais às terças-feiras e segundas-feiras.

Desenvolver dias fracos: criar ações específicas para quarta-feira e domingo, como descontos ou combos, e medir o impacto comparando o crescimento percentual das vendas.

▶️ Como Executar
Opção 1 — Google Colab
Acesse Google Colab.

Faça upload dos arquivos PY_06_EDA_Vendas_Colab.ipynb e sales_data.csv.

Execute todas as células do notebook.

Opção 2 — Jupyter Notebook
bash
git clone https://github.com/SEU-USUARIO/NOME_DO_REPOSITORIO.git
cd NOME_DO_REPOSITORIO
python -m venv .venv
.venv\Scripts\activate
pip install pandas matplotlib seaborn notebook
jupyter notebook
Abra o arquivo PY_06_EDA_Vendas_Colab.ipynb e execute todas as células.

📁 Estrutura do Projeto
Código
📦 Analise-Exploratoria-Vendas
│
├── images
│   └── grafico_vendas_semana.png
├── PY_06_EDA_Vendas_Colab.ipynb
├── README.md
├── sales_data.csv
├── sales_data_analisado.csv
└── requirements.txt
🚀 Possíveis Melhorias
Dashboards interativos com Power BI ou Plotly.

Modelos de previsão de vendas.

Automatização da geração de relatórios.

Pipeline ETL para preparação automática dos dados.
