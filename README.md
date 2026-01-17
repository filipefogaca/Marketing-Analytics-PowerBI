# 📊 Marketing Analytics: Perfil de Cliente e Campanhas

Este projeto consiste em uma análise estratégica de dados de marketing para identificar padrões de consumo, segmentar perfis de clientes e mensurar a eficácia de campanhas publicitárias. O foco principal foi a utilização do **Power BI** como ferramenta de **ETL (Extract, Transform, Load)** para garantir a qualidade e a integridade da base de dados.

---

## 🎯 Objetivos do Projeto
* **Análise do Perfil do Cliente:** Identificação de características demográficas (escolaridade, estado civil, idade) e comportamento de compra.
* **Performance de Campanhas:** Mensuração da taxa de aceitação e sucesso das ofertas enviadas aos clientes.
* **Padrões de Venda:** Avaliação do faturamento e ticket médio por ponto de compra (Loja Física, Web e Catálogo).

---

## 🛠️ Processo de ETL e Qualidade de Dados
O tratamento de dados foi realizado inteiramente no **Power Query**, demonstrando a capacidade da ferramenta em resolver problemas complexos de limpeza de dados sem a necessidade de ferramentas externas.

| Etapa | Ação Realizada no Power Query |
| :--- | :--- |
| **Limpeza de Duplicadas** | Identificação e remoção de registros repetidos para evitar inflação nos números de vendas. |
| **Tratamento de Nulos** | Correção de valores ausentes em colunas críticas para a análise de perfil e comportamento. |
| **Normalização** | Ajuste de tipos de dados (datas e valores monetários) para garantir a precisão dos cálculos. |
| **Enriquecimento** | Criação de colunas condicionais para segmentar clientes por "Ticket Médio" e "Faixa Etária". |



---

## 🚀 Tecnologias Utilizadas
* **Microsoft Power BI:** Desenvolvimento do dashboard e modelagem de dados.
* **Power Query:** Motor de transformação e limpeza de dados (ETL).
* **Dataset:** Arquivo `dados_marketing.csv`.

---

## 📂 Estrutura do Repositório
```text
Marketing-Analytics/
├── data/
│   └── dados_marketing.csv    # Dataset original
├── dashboard/
│   └── analise_marketing.pbix # Arquivo do Power BI com o modelo final
├── images/                    # Prints do dashboard e do fluxo de ETL
└── README.md                  # Documentação do projeto
```
Desenvolvido por Filipe Fogaça
