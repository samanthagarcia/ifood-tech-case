# ifood-tech-case

📊 iFood Case Técnico – Data Analysis
Este repositório contém a análise de um experimento A/B realizado pelo iFood, com o objetivo de avaliar o impacto do uso de cupons na retenção de usuários. A solução foi desenvolvida utilizando PySpark no Google Colab.

🧠 Objetivo
Você foi contratado como Analista de Dados no iFood, uma das maiores empresas de tecnologia da América Latina. Seu primeiro projeto envolve analisar os resulta dos de um teste A/B realizado recentemente, desenhado para avaliar o impacto de uma estratégia de cupons na retenção de usuários.

📁 Estrutura do Repositório
📦 ifood-case
├── ifood_testcase.ipynb       # Notebook com todo o processamento e análise
├── README.md                  # Este arquivo

⚙️ Como Executar Localmente
1. Clone o repositório
git clone https://github.com/seu-usuario/ifood-case.git
cd ifood-case

2. Requisitos
--> Python 3.8+
--> PySpark
--> Java 8
--> Pandas
--> Matplotlib / Seaborn (para gráficos)

Obs: a execução também pode ser feita diretamente no Google Colab, sem necessidade de setup local.

3. Execute o notebook
Abra o ifood_testcase.ipynb e execute as células na ordem. O notebook está estruturado em:

Setup e configuração do ambiente
Leitura e exploração dos dados
Cálculo de KPIs por grupo (teste x controle)
Testes estatísticos (T-Test)
Segmentação de usuários
Análise por segmentos
Considerações finais

📦 Dados Utilizados
Os datasets foram disponibilizados pelo próprio iFood:

Pedidos: order.json.gz ()
Consumidores: consumer.csv.gz ()
Restaurantes: restaurant.csv.gz ()
Marcação A/B: ab_test_ref.tar.gz ()

🛠 Ferramentas e Tecnologias
PySpark
Google Colab
Pandas
Seaborn
SciPy para testes estatísticos

📈 Métricas Avaliadas
Ticket médio
Retenção de usuários
Total gasto por usuário
Número médio de pedidos

Todas as análises estão disponíveis no notebook.

A apresentação executiva com insights de negócio foi separada em um arquivo PDF complementar (incluso neste repositório).

🤝 Contato
Caso tenha dúvidas ou queira conversar mais sobre o case, estou à disposição!
📬 samanthamcgarcia@gmail.com | Samantha Garcia (Linkedin)

