# 🎲 Dashboard de Análise de Salários na Área de Dados


[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.32+-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.0+-3F4F75?logo=plotly&logoColor=white)](https://plotly.com/)


Este projeto consiste em um **dashboard interativo** desenvolvido com Python, Pandas, Plotly e Streamlit. Ele permite explorar e analisar informações sobre **salários na área de dados**, trazendo métricas, gráficos e filtros para refinar os resultados de acordo com ano, senioridade, contrato e tamanho da empresa.


A base de dados utilizada contém informações sobre salários em diferentes países, cargos e níveis de experiência, oferecendo uma visão ampla do mercado internacional de dados. As visualizações ajudam a entender melhor a distribuição salarial, diferenças por cargo e a relação entre senioridade e remuneração.


---



## 🌐 Links
[![Abrir no Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://salary-data-dashboard.streamlit.app)


---


## ✨ Funcionalidades


- 📊 Exibição de **métricas principais** (salário médio, máximo, total de registros, cargo mais frequente)
- 📈 Gráficos interativos com **Plotly**:
- Top 10 cargos por salário médio
- Distribuição de salários anuais
- Proporção dos tipos de trabalho (remoto, presencial, híbrido)
- Salário médio de Cientistas de Dados por país
- 🔍 **Filtros dinâmicos** (ano, senioridade, tipo de contrato e tamanho da empresa)
- 🗂️ Tabela detalhada dos registros filtrados


---


## 🛠️ Tecnologias Utilizadas


- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) – manipulação e tratamento dos dados
- [Plotly](https://plotly.com/) – visualização de dados interativa
- [Streamlit](https://streamlit.io/) – desenvolvimento da aplicação web


---


## 📂 Estrutura do Projeto
```
📦 salary-data-dashboard
┣ 📄 data-analysis.csv # Base de dados usada no projeto
┣ 📄 app.py # Código principal da aplicação
┣ 📄 requirements.txt # Dependências do projeto
┗ 📄 README.md # Documentação do projeto
```


---


## ▶️ Como Executar o Projeto


1. **Clone este repositório**
```bash
git clone https://github.com/PxS00/salary-data-dashboard.git
cd salary-data-dashboard
```


2. **Crie um ambiente virtual (opcional, mas recomendado)**
```bash
python -m venv venv
source venv/bin/activate # Linux/Mac
venv\Scripts\activate # Windows
```


3. **Instale as dependências**
```bash
pip install -r requirements.txt
```


4. **Execute a aplicação**
```bash
streamlit run app.py
```


5. **Acesse no navegador**
```
http://localhost:8501
```


---


## 👨‍💻 Autor


Desenvolvido por Lucas Rossoni Dieder  
GitHub: [@PxS00](https://github.com/PxS00)  
LinkedIn: [lucas-rossoni-dieder](https://www.linkedin.com/in/lucas-rossoni-dieder)


---


📌 Este projeto foi desenvolvido **com fins educacionais** durante a Imersão de Dados da Alura 2025.
