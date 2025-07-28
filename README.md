## 📊 Desafio **"Dados que Transformam"** – Análise do E-commerce Olist para a **Bemol Digital**

### 👩‍💻 **Autora**  
**Rayane Neves Lira**  
Estudante de **Sistemas de Informação** no Instituto de Ciências Exatas e Tecnologia (**ICET**) da Universidade Federal do Amazonas (**UFAM**). Apaixonada por dados e pela capacidade que eles têm de revelar histórias e guiar decisões inteligentes. Buscando aplicar o conhecimento técnico em projetos que gerem **impacto real no negócio**.

---

## 1. 📌 Visão Geral do Projeto

Este repositório contém a solução completa para o desafio **"Dados que Transformam"**, proposto pela **Bemol Digital** para a vaga de **Estágio em Dados**.

🎯 **Objetivo:**  
Realizar um pipeline completo de **ETL** (Extração, Transformação e Carga) e uma **Análise Exploratória de Dados (EDA)** a partir de um dataset público da **Olist**, um dos maiores marketplaces do Brasil.

📓 O projeto foi desenvolvido em um **notebook Jupyter** e seguiu uma metodologia rigorosa, desde a limpeza e estruturação dos dados brutos até a criação de visualizações e a extração de **insights estratégicos** em cinco áreas de negócio:

- 🛍️ **Performance de Vendas**  
- 🚚 **Logística**  
- 🙂 **Satisfação do Cliente**  
- 💰 **Análise Financeira**  
- 📢 **Marketing**

---

## 2. 🔍 Desafios Encontrados e Soluções

> A análise de dados do mundo real raramente é um processo linear.

Durante o projeto, alguns **desafios importantes** foram identificados e solucionados com criatividade e rigor técnico:

### ❗ Dados Ausentes e Qualidade
- **Problema:** Valores nulos em colunas críticas (ex: categoria de produtos, datas) e tipos incorretos (datas como texto).
- **Solução:**  
  - Limpeza robusta com estratégias específicas por caso.  
  - Preenchimento com texto padrão ou **mediana**.  
  - Conversão das colunas de data para o tipo `datetime` (essencial para análises temporais).

---

### 📉 Limitações do Dataset e o Uso de Proxies

#### 💡 Lucratividade
- **Problema:** Ausência de coluna "custo do produto".
- **Solução:**  
  Utilização de **Receita Total** e **Ticket Médio** como **proxies** da performance financeira.

#### 📦 Desempenho de Transportadoras
- **Problema:** Ausência de nome da transportadora.
- **Solução:**  
  Uso do `seller_id` como proxy, associado à localização geográfica (**cidade/estado**) para avaliar a performance logística.

#### 🎯 Campanhas de Marketing
- **Problema:** Ausência de dados sobre ações promocionais.
- **Solução:**  
  Utilização dos **pagamentos com voucher** como indicador de campanha, permitindo medir o impacto na aquisição e retenção de clientes.

---

## 3. 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido com o **ecossistema Python**, utilizando bibliotecas amplamente adotadas na indústria de dados:

- **Pandas:**  
  Manipulação, limpeza e estruturação de dados durante o ETL e EDA.

- **NumPy:**  
  Operações numéricas e suporte à base de dados vetoriais.

- **Matplotlib & Seaborn:**  
  Criação de visualizações — de gráficos simples a painéis analíticos complexos.

---

### ✅ **Conclusão**

Este projeto demonstra a **capacidade de transformar dados brutos em análises claras, documentadas e com insights acionáveis**, atendendo a todos os **diferenciais propostos pelo desafio da Bemol Digital**.
