# Projeto de Data Warehouse and Analytics
Este projeto demonstra uma solução abrangente de armazenamento e análise de dados, desde a construção de um data warehouse até a geração de insights acionáveis. Concebido como um projeto de portfólio, ele destaca as melhores práticas do setor em engenharia e análise de dados.

---
# Arquitetura de Dados
A arquitetura de dados para este projeto segue as camadas Bronze, Prata e Ouro da Arquitetura Medallion:
<img width="722" height="421" alt="arquitetura de alto nível" src="https://github.com/user-attachments/assets/0424c3c3-f893-4399-91fd-288a3da048f7" />

* **Camada Bronze:** Armazena os dados brutos tal como estão, provenientes dos sistemas de origem. Os dados são importados de arquivos CSV para um banco de dados SQL Server.
* **Camada Prata:** Esta camada inclui processos de limpeza, padronização e normalização de dados para prepará-los para análise.
* **Camada Ouro:** Abriga os dados prontos para uso comercial, modelados em um esquema em estrela, necessários para geração de relatórios e análises.

---
# Visão Geral do Projeto
Este projeto envolve:
* **Arquitetura de Dados:** Projetar um Data Warehouse moderno usando a arquitetura Medallion nas camadas Bronze, Prata e Ouro.
* **Pipelines ETL:** Extrair, transformar e carregar dados de sistemas de origem para o data warehouse.
* **Modelagem de Dados:** Desenvolver tabelas de fatos e dimensões otimizadas para consultas analíticas.
* **Análise e Relatórios:** Criar relatórios e dashboards baseados em SQL para insights acionáveis.
