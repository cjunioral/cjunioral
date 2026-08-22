<h1 align="center">Olá, eu sou o Cícero Júnior! 👋</h1>

<p align="center">
  <b>Engenheiro de Dados & Analytics Engineer</b><br>
  <sub>Transformando dados brutos em decisões inteligentes com pipelines escaláveis e confiáveis.</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/cicerorjunior" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:ciceroramalho.dataeng@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
  <img src="https://img.shields.io/badge/Localização-Brasil%20🇧🇷-2C8EBB?style=for-the-badge" alt="Localização">
</p>

---

## 🚀 Sobre mim

Sou **Engenheiro de Dados** em ascensão e **graduando em Engenharia da Computação**, apaixonado por construir a infraestrutura que faz os dados fluírem com qualidade e propósito.

Atualmente atuo como **Analista de Sistemas no Grupo Queiroz**, onde trabalho diretamente com **SQL em ambiente Oracle**, validação de dados, levantamento de requisitos e suporte ao **ERP TOTVS Consinco** — uma vivência que me dá contato diário com qualidade de dados, processos de negócio e tomada de decisão orientada a dados.

Paralelamente, desenvolvo projetos práticos de **Data Engineering** e **Analytics Engineering** com as tecnologias mais adotadas pelo mercado: pipelines ETL automatizados, processamento distribuído, Arquitetura Medallion, Data Warehouses dimensionais e até enriquecimento de dados com **IA Generativa**.

🎯 **Busco oportunidades como** Engenheiro de Dados, Analytics Engineer ou Analista de Dados, contribuindo para soluções de dados escaláveis, confiáveis e orientadas a valor para o negócio.

- 🔭 Construindo pipelines de dados com **Airflow, PySpark e dbt**
- 🌱 Aprofundando em **BigQuery, modelagem dimensional e governança de dados**
- 💬 Fale comigo sobre **Engenharia de Dados, ETL, SQL e Cloud**
- 📫 Contato: **ciceroramalho.dataeng@gmail.com**

---

## 🛠 Stack & Tecnologias

**Linguagens & Processamento**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=Apache%20Spark&logoColor=white" alt="PySpark">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
</p>

**Orquestração & Transformação**
<p align="left">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" alt="Airflow">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt">
</p>

**Bancos de Dados & Data Warehouse**
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white" alt="BigQuery">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
</p>

**Analytics & Ferramentas**
<p align="left">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Metabase-509EE3?style=for-the-badge&logo=metabase&logoColor=white" alt="Metabase">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

---

## 📌 Projetos em Destaque

### 📊 Pipeline de Analytics Engineering — Análise de NPS (Telecom)
**Stack:** BigQuery · dbt · Power BI · Git/GitHub

Projeto **ponta a ponta** de analytics engineering sobre uma base de pesquisa de **NPS** de uma operadora de telecom. A base foi construída com as inconsistências típicas do mundo real, e o desafio central era transformar dados brutos e não confiáveis em um **modelo testado e pronto para decisão**.

- **Ingestão:** Dados crus carregados no BigQuery, preservando as inconsistências da origem
- **Transformação:** dbt em camadas (staging → marts) com modelo dimensional **Star Schema** (fato de respostas + dimensões de cliente, produto, canal, colaborador e calendário)
- **Qualidade:** Testes automatizados (`unique`, `not_null`, `accepted_values`, `relationships`) que capturaram problemas reais antes de virarem métricas erradas
- **Documentação:** Lineage e docs gerados com dbt docs
- **Versionamento:** Git profissional com branches e Pull Requests
- **Visualização:** Dashboard em Power BI com visuais customizados em HTML/CSS/SVG e alternância dinâmica entre tema claro e escuro

🧹 **Qualidade de dado tratada:** notas inválidas (`"onze"`, `"10,0"`, `"11"`), datas impossíveis (mês 13), chaves com espaços e caixa mista, duplicados e órfãos, e categorias inconsistentes — cada uma resolvida na camada correta do pipeline.
**~630 respostas brutas → 562 respostas válidas e testadas.**

🔎 **Principais achados:** NPS geral de **−9,4** (zona crítica) em tendência de piora; jornada de Cobrança e canais humanos concentrando a maior insatisfação; e um produto com NPS alto mas baixo volume sinalizado como **amostra não representativa**, evitando uma conclusão enganosa.

💡 **Aprendizado:** o valor de um dashboard não está no visual, e sim na **confiança do dado por trás dele**.

### 📂 Olist Data Pipeline — Engenharia de Dados
Pipeline de dados de e-commerce construído sobre a **Arquitetura Medallion (Bronze, Silver & Gold)**, garantindo organização, qualidade e governança em cada camada.
- **Processamento:** Python e PySpark para tratamento distribuído dos dados
- **Orquestração:** DAGs automatizadas no Apache Airflow
- **Modelagem:** Data Warehouse com modelagem dimensional (Star Schema)
- **Infraestrutura:** Ambiente WSL2

### ☁️ Pipeline de Dados Climáticos — Airflow + API REST
Pipeline completo simulando um cenário real de engenharia de dados, da ingestão à entrega.
- **Coleta:** Ingestão de dados climáticos de Mossoró (RN) via API pública com Python
- **ETL:** Processamento, validação e transformação com Pandas
- **Orquestração:** Fluxo agendado e automatizado via DAGs no Apache Airflow
- **Versionamento:** Git em ambiente WSL

### 🤖 Análise de Feedbacks com IA Generativa
Aplicação de **IA Generativa** para enriquecimento, classificação e análise de dados não estruturados, extraindo insights de feedbacks de clientes.

### 📰 Processamento de Notícias — Medallion + Data Warehouse
Ingestão automatizada de notícias via APIs externas, organizadas em Arquitetura Medallion e estruturadas em Data Warehouse para análise.

---

## 💼 Experiência Profissional

### 🏢 Grupo Queiroz
**Analista de Sistemas** · *jul/2026 – Atual*
- Desenvolvimento de consultas **SQL** para detalhamento e análise de dados
- Suporte funcional ao **ERP TOTVS Consinco**, analisando e resolvendo inconsistências
- Levantamento de requisitos junto às áreas de negócio para criação de relatórios
- Disponibilização de dados e relatórios para apoiar decisões internas
- Validação da integridade e consistência das informações extraídas do banco

**Estagiário de TI** · *nov/2025 – jun/2026*
- Desenvolvimento de sistema interno de **gestão de estoque** (entradas, transferências entre setores e lojas)
- Consultas **SQL em ambiente Oracle** para validação, conferência e análise de dados operacionais
- Identificação e correção de inconsistências em bases de dados corporativas
- 🏆 Resolução de **mais de 1.000 chamados** de sistemas e suporte técnico
- 🏆 Solução que apoiou o controle de movimentações de estoque do setor

---

## 📚 Formação & Certificações

🎓 **Bacharelado em Engenharia da Computação** — Universidade Potiguar (UnP) · *2023 – 2028*

📜 **Certificações:**
`Introduction to Data Science` · `Python para Data Science` · `Apache Spark` · `dbt — Transformações Modernas de Dados` · `Formação em Power BI`

🌐 **Idiomas:** Português (Nativo) · Inglês (Profissional Limitado)

---

## 📊 Estatísticas do GitHub

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=SEU_USUARIO&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USUARIO&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SEU_USUARIO&theme=tokyonight&hide_border=true" alt="GitHub Streak">
</p>

---

<p align="center">
  <i>💡 "Dados bem trabalhados hoje são as decisões inteligentes de amanhã."</i>
</p>
