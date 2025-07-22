📊 Análise Exploratória de Vendas — Superstore Dataset
Este projeto tem como objetivo realizar uma análise exploratória de dados de vendas utilizando Python e bibliotecas poderosas de visualização e manipulação de dados. O dataset é fictício (estilo Superstore), mas os insights são dignos de reunião com diretoria.

🧰 Tecnologias Utilizadas
Pandas — manipulação de dados tabulares

NumPy — suporte numérico

Matplotlib & Seaborn — visualização de dados em alto nível

Datetime — manipulação de datas

📦 Etapas da Análise
1. Leitura e Verificação dos Dados
Leitura com pandas.read_csv()

Verificação de duplicatas e valores ausentes

Conversão da coluna de data com pd.to_datetime()

2. Análises Exploratórias
Distribuição estatística das vendas

Filtro por categorias como Office Supplies

Agrupamento por:

Data do pedido

Estado

Cidade

Segmento de cliente

3. Visualizações
Gráficos de barras por tempo e região

Top 10 cidades com maiores volumes de vendas

Gráfico de pizza com distribuição de vendas por segmento

Comparativo de vendas ao longo dos anos por segmento

4. Simulação de Descontos
Aplicação de descontos condicionais (15% ou 10%)

Cálculo de nova coluna com o valor final pós-desconto

Comparativo da média de vendas antes e depois da aplicação dos descontos

📈 Exemplos de Insights
Segmento Consumer domina em vendas, mas o desconto afeta a rentabilidade.

Cidades como Los Angeles têm alta concentração de pedidos.

Ano a ano, os três segmentos mantêm crescimento consistente.

⚠️ Observações Técnicas
Foi emitido um warning sobre parsing de datas por conta do formato DD/MM/YYYY. O ideal seria usar:

python
Copiar
Editar
pd.to_datetime(df['Data_Pedido'], format='%d/%m/%Y')
Alerta de incompatibilidade com numpy >=1.26: se você estiver usando versões mais recentes, recomenda-se atualizar o scipy para evitar warnings no ambiente Anaconda.

📎 Arquivos
dataset.csv — base de dados simulada com informações de vendas

analise_vendas.py — script principal com as análises e visualizações

👨‍💻 Autor
Henrique Souza
📍 Cientista de Dados em formação | Especialista em GIS
🔗 [Seu GitHub aqui]
🔗 [LinkedIn, se quiser meter uma moral também]

🤝 Contribuições
Contribuições, melhorias e novas visualizações são bem-vindas.
Sinta-se à vontade para abrir uma issue ou mandar um pull request.

