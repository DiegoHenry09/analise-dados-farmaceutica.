# Analise-Dados-Farmaceutica
Repositório com o projeto de análise de dados exploratória (EDA) do setor farmacêutico, desenvolvido em Python e com visualização final em Power BI.

# 📊 Projeto de Análise de Dados – Indústria Farmacêutica

Este repositório contém um projeto completo de análise de dados, dando continuidade aos estudos aplicados no projeto de e-commerce. O objetivo foi realizar um ciclo completo de **ETL e Análise Exploratória de Dados (EDA)** em um cenário fictício da indústria farmacêutica, aprofundando a complexidade da manipulação e a geração de *insights* estratégicos.

---

## 🔹 Objetivos do Projeto
- Realizar a extração, transformação e carga (ETL) de dados de múltiplas fontes (abas de Excel).
- Praticar a limpeza e o tratamento de dados complexos, incluindo a remoção de duplicatas e o tratamento de valores nulos.
- Aprofundar a análise de **Pareto (80/20)** para identificar a concentração de receita em clientes e produtos.
- Investigar a **sazonalidade de vendas** de forma geral, por produto e por região.
- Realizar uma análise aprofundada do **ciclo de pagamentos**, identificando o perfil de comportamento dos clientes.
- Gerar um **dataset final limpo e unificado**, pronto para ser consumido por ferramentas de Business Intelligence.

---

## 🔹 Estrutura do Repositório
- `Pharma_Hype_analise.ipynb` → Notebook principal com todo o processo de ETL e Análise Exploratória.
- `dados_farmaceuticos_hypera.xlsx` → A fonte de dados original, com múltiplas abas.
- `dados_farmaceuticos_powerbi.csv` → O dataset final, limpo e tratado, pronto para importação.
- `dashboard_final.png` → Uma imagem do dashboard final criado no Power BI.

---

## 🔹 Tecnologias Utilizadas
- **Python** → Pandas, NumPy, Matplotlib, Seaborn
- **Excel/CSV** como fonte e saída de dados
- **Power BI** para a camada final de dashboards
- **Jupyter Notebook** no VS Code para desenvolvimento

---

## 🔹 Análises Realizadas
✔️ **Análise de Performance:** Ranking de produtos e UFs por receita e por volume de vendas, revelando a diferença entre os mais rentáveis e os mais populares.
✔️ **Análise de Pareto (80/20):** Confirmação de que a receita é altamente concentrada em um número restrito de clientes e moderadamente concentrada em um grupo de produtos-chave.
✔️ **Análise de Sazonalidade:** Identificação de um claro padrão de vendas, com baixa no início do ano e um pico expressivo no último trimestre, padrão este que se repete nos principais produtos e mercados.
✔️ **Análise do Ciclo de Pagamentos:** Descoberta de um ciclo de pagamento médio de ~30 dias e identificação do perfil de clientes com maior percentual de atraso (Distribuidores e Clínicas).
✔️ **Análise de Comportamento:** Descoberta do "viés de volume", que mostra que a contagem absoluta de atrasos é uma métrica enganosa, e que os clientes de maior volume são, na verdade, pagadores mais consistentes.

---

## 🔹 Resultados e Aprendizados
- Sucesso na integração e limpeza de um dataset complexo com múltiplas tabelas relacionadas.
- Geração de *insights* de negócio estratégicos, como a divergência entre popularidade e rentabilidade de produtos e o verdadeiro perfil de risco dos clientes.
- Criação de visualizações complexas, como dashboards com subplots e gráficos de Pareto.
- Estruturação de um pipeline de tratamento de dados robusto e bem documentado.

---

## 🔹 Resultados e Impacto do Projeto

Este projeto transcendeu a simples execução de código, focando na transformação de dados brutos em inteligência de negócio. Os principais resultados alcançados foram:

✔️ **Construção de uma "Fonte da Verdade":** Foi criado um *dataset* unificado e limpo a partir de cinco fontes de dados distintas, estabelecendo uma base de dados coesa e confiável, pronta para ser explorada em ferramentas de BI como o Power BI.

✔️ **Geração de *Insights* Estratégicos Acionáveis:** A análise exploratória revelou conclusões de alto impacto para o negócio, como:
  - A **descoberta de perfis de produtos distintos** ("volume" vs. "valor"), permitindo estratégias de marketing e estoque mais inteligentes.
  - A **identificação do principal mercado geográfico** (RS), direcionando o foco dos esforços comerciais.
  - A **identificação do verdadeiro perfil de risco de clientes**, mostrando que o comportamento de pagamento (percentual de atraso) é uma métrica mais precisa do que o volume absoluto de vendas.

✔️ **Desenvolvimento de um Processo Analítico Robusto:** O projeto serviu para consolidar um fluxo de trabalho completo, desde a limpeza e enriquecimento de dados (Feature Engineering) até a criação de visualizações complexas (dashboards e Paretos) para comunicar as descobertas de forma eficaz.


✍️ **Autor:** Diego Henrique 
🔗 Meu LinkedIn(https://www.linkedin.com/in/diego-henrique-8048aa174)
