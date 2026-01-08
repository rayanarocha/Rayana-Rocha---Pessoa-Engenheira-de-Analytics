# Rayana-Rocha---Pessoa-Engenheira-de-Analytics

# 📊 Dashboard de Análise de Vendas e Manufatura (2013-2016)

## 📝 Sobre o Projeto
Neste projeto, desenvolvi uma solução completa de Business Intelligence no **Power BI** para analisar o desempenho de vendas e manufatura de uma operação global. O meu objetivo foi transformar dados brutos e desestruturados de múltiplos anos (2013 a 2016) num dashboard estratégico capaz de guiar decisões de negócio baseadas em factos.

## 🛠️ Tecnologias e Ferramentas
* **Power BI Desktop**
* **Power Query** (Processos de ETL e Limpeza)
* **Linguagem DAX** (Criação de Medidas e Inteligência de Dados)
* **Modelagem Star Schema** (Esquema Estrela)

## ⚙️ Processo de Desenvolvimento

### 1. ETL e Tratamento de Dados
Iniciei o projeto com a extração e limpeza dos dados utilizando o Power Query. As minhas principais ações foram:
* **Padronização de Estrutura:** Corrigi as bases de 2013-2014, separando manualmente as colunas mescladas de `Country` e `Product`.
* **Consolidação de Dados:** Unifiquei os ficheiros anuais através de operações de *Append*, criando duas tabelas mestre: `Fato_Vendas` e `Fato_Manufatura`.
* **Sanitização:** Apliquei funções de *Trim* (Recortar) para garantir que não existissem espaços em branco que pudessem comprometer a integridade dos filtros e cálculos.

### 2. Modelação de Dados e Inteligência
Para garantir a performance do relatório, estruturei o modelo em **Star Schema**:
* **Dimensões:** Criei tabelas de dimensão para Produtos e uma tabela `dCalendario` dinâmica via DAX para análises temporais.
* **Medidas DAX:** Desenvolvi as principais métricas de negócio, incluindo:
  * `Total Sales`: Faturamento bruto total.
  * `Total Profit`: Lucro líquido após custos.
  * `% Margem Bruta`: Eficiência financeira relativa por segmento e país.

### 3. Visualização e UX
Desenvolvi um layout intuitivo para facilitar a leitura dos dados pelo utilizador final:
* **KPI Cards:** Destaque para os números globais no topo do relatório.
* **Análise de Segmentos:** Gráfico de rosca para identificar a distribuição de vendas.
* **Sazonalidade:** Gráfico de linhas para monitorizar a evolução mensal e anual.

## 🧠 Insights de Negócio Extraídos
Através da minha análise, identifiquei pontos críticos para a estratégia da empresa:
* **Dominância Governamental:** O segmento de *Government* representa quase 50% da receita total, indicando uma forte dependência de contratos públicos.
* **Mix de Lucratividade:** Identifiquei que os produtos *VTT* e *Amarilla* possuem as melhores margens, apesar de não serem os mais vendidos em volume.
* **Oportunidade de Mercado:** O segmento de *Midmarket* apresenta baixa penetração, sendo uma oportunidade clara de diversificação de risco.

## 🚀 Como Executar o Projeto
1. Faz o download do ficheiro `.pbix` presente neste repositório.
2. Abre o ficheiro no **Power BI Desktop**.
3. Utiliza os filtros de **Ano**, **País** e **Produto** no topo do dashboard para explorar as diferentes camadas de dados.

---
📫 **Contacto:** [O Teu Nome/Link para LinkedIn]
