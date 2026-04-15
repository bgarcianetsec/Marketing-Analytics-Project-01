# 📊 Marketing Analytics: Insights e Comportamento do Consumidor

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=python&logoColor=white)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido como parte dos meus estudos em **Análise de Dados com Python**. O objetivo principal foi realizar uma análise exploratória (EDA) em um dataset de campanhas de marketing para entender o perfil dos clientes e o que impulsiona o consumo.

Como entusiasta da área, foquei não apenas em gerar gráficos, mas em garantir a **qualidade do dado** (Data Cleaning) e extrair recomendações de negócio reais.

## 📂 Estrutura do Repositório
* `data/`: Contém o dataset original (Kaggle) e arquivos auxiliares.
* `notebooks/`: Notebook Jupyter com todo o passo a passo da análise, desde a importação até os insights finais.
* `requirements.txt`: Lista de bibliotecas necessárias para rodar o projeto.

## 🛠️ Etapas do Projeto

### 1. Limpeza e Tratamento de Dados
Um dos maiores desafios foi garantir que outliers não distorcessem a análise. Realizei:
* **Tratamento de Erros:** Implementação de blocos `try/except` para carregamento de arquivos.
* **Remoção de Outliers:** Identificação e exclusão de dados inconsistentes (clientes com mais de 120 anos e rendas fora da realidade estatística).
* **Feature Engineering:** Criação de novas métricas como `Age` (Idade), `Total_Mnt` (Gasto Total) e `Total_Children` (Total de Filhos).

### 2. Análise e Insights (Principais Descobertas)
* **Escolaridade vs. Consumo:** Identifiquei que clientes com nível de escolaridade **PhD** e **Graduation** possuem o maior ticket médio de gasto total.
* **Canais de Venda:** Apesar da digitalização, a **Loja Física** ainda representa o maior volume de compras, superando as compras via Web.
* **Perfil da Campanha:** A última campanha de marketing teve maior taxa de aceitação entre o grupo de **alta renda**.

## 🚀 Como rodar o projeto
1. Clone o repositório: `git clone https://github.com/bgarcianetsec/Marketing-Analytics-Project-01.git`
2. Crie um ambiente virtual: `python -m venv .venv`
3. Instale as dependências: `pip install -r requirements.txt`
4. Execute o notebook na pasta `notebooks/`.

## 👨‍💻 Sobre mim
Sou **Bruno Garcia**, estudante de tecnologia e entusiasta de Análise de Dados e Segurança Cibernética. Estou em constante aprendizado, buscando transformar dados brutos em decisões inteligentes.

---
📫 **Contatos:**
* [LinkedIn](linkedin.com/in/bgarcianetsec)
* [GitHub](https://github.com/bgarcianetsec)
