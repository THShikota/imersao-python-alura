📊 Dashboard de Salários na Área de Dados

Dashboard interativo desenvolvido em Python para análise de salários na área de dados, permitindo a exploração dos dados por meio de filtros dinâmicos, KPIs e visualizações interativas.

O projeto cobre todo o fluxo de um projeto de dados: tratamento → análise → visualização → entrega como produto.


🎯 Objetivo do Projeto

  - Consolidar conhecimentos em Análise e Visualização de Dados com Python
  
  - Criar um dashboard interativo para exploração de dados reais
  
  - Aplicar boas práticas de:

    - Manipulação de dados com Pandas
    
    - Visualização com Plotly
    
    - Construção de aplicações com Streamlit
    
    - Versionamento e deploy de projetos


🧰 Tecnologias Utilizadas

- Python
- Pandas
- Plotly
- Streamlit

📂 Estrutura do Projeto
dashboard_salarios_dados/
- app.py                     # Arquivo principal do dashboard (Streamlit)
- dados-imersao-final.csv    # Dataset tratado utilizado na aplicação
- requirements.txt           # Dependências do projeto
- README.md                  # Documentação do projeto


⚙️ Funcionalidades do Dashboard

- Filtros dinâmicos:

  - Ano
  
  - Senioridade
  
  - Tipo de contrato
  
  - Tamanho da empresa
  

- KPIs principais:

  - Salário médio
  
  - Salário máximo
  
  - Total de registros
  
  - Cargo mais frequente
  

- Visualizações interativas:

  - Top 10 cargos por salário médio
  
  - Distribuição dos salários anuais
  
  - Proporção dos tipos de trabalho (remoto, presencial, híbrido)
  
  - Mapa coroplético com salário médio de Data Scientists por país
  

- Tabela detalhada com os dados filtrados para exploração completa


▶️ Como Executar o Projeto Localmente
1. Clone o repositório
- git clone https://github.com/seu-usuario/dashboard_salarios_dados.git
- cd dashboard_salarios_dados

2. Crie e ative um ambiente virtual (opcional, mas recomendado)
- python -m venv venv
- source venv/bin/activate  # Linux / Mac
- venv\Scripts\activate     # Windows

3. Instale as dependências
- pip install -r requirements.txt

4. Execute a aplicação
- streamlit run app.py


O dashboard será aberto automaticamente no navegador.

🌐 Acesso Online

O projeto também foi publicado no Streamlit, permitindo acesso público ao dashboard sem necessidade de instalação local.

🔗 Link do dashboard:
👉 https://imersao-python-alura-2026.streamlit.app/
