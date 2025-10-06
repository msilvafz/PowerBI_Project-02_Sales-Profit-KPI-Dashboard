# 📊 Dashboard de Vendas, Custos, Margem de Lucro e KPI  

Dashboard desenvolvido no **Microsoft Power BI** com foco em **analisar vendas, custos, lucros e indicadores de desempenho (KPIs)**.  

> 💡 Este projeto apresenta o processo completo — da **extração e modelagem de dados (ETL)** até a **criação de métricas DAX** e **visualizações interativas** para insights de negócio.

---

## 📢 Sobre  

Este projeto demonstra o uso prático do **Power BI** na construção de **dashboards executivos e analíticos**, aplicando boas práticas de **modelagem de dados, DAX e design visual**.  
O layout foi planejado com foco em **clareza, performance e storytelling visual**, priorizando métricas que apoiam a **tomada de decisão estratégica**.

---

## 🎯 Objetivo  

Analisar o desempenho comercial por meio de indicadores-chave, identificando:  
- Tendências de **margem de lucro** ao longo do tempo.  
- **Custos médios de envio** por mercado.  
- **Distribuição de lucros** entre categorias de produto.  
- **Variações no volume de vendas** conforme o modo de envio.  
- Atingimento de **metas de vendas (KPI)**.  

---

## ⚙️ Processos Realizados  

* 📥 **Integração de dados**: importação de múltiplas fontes — *clientes, pedidos, produtos e vendas*.  
* 🧹 **Tratamento e limpeza** no Power Query:  
  - Remoção de duplicatas e colunas desnecessárias.  
  - Correção de tipos de dados e estrutura de relacionamentos.  
* 🧩 **Modelagem de dados** com diferentes cardinalidades (*1:1*, *1:N*, *N:N*).  
* 🧮 **Criação de medidas DAX**:  
  - `Lucro = Valor de Venda - Custo de Envio`  
  - `Margem de Lucro = DIVIDE(Lucro, Valor de Venda)`  
* 🧠 **Funções adicionais**: `ROUND()` e `DIVIDE()` para cálculos precisos.  
* 🎯 **KPI configurado** para acompanhar metas de vendas (R$350).  
* 🎨 **Design visual personalizado** com tema escuro, ícones e hierarquia de leitura.  

---

## 📊 Visualizações Utilizadas  

Cada gráfico do dashboard foi escolhido estrategicamente para responder a perguntas de negócio específicas e facilitar a interpretação dos dados:

- **📈 Evolução da Margem de Lucro ao Longo do Tempo**  
  → Gráfico de linha utilizado para exibir a tendência da margem de lucro entre 2011 e 2014, facilitando a análise de oscilações e estabilidade ao longo do tempo.  

- **💰 Valor Médio das Vendas Realizadas (KPI)**  
  → Indicador KPI em formato de velocímetro configurado com meta de R$350, permitindo avaliar se o desempenho médio das vendas está dentro do esperado.  

- **🌍 Custo Médio de Envio por Mercado (Treemap)**  
  → Visual em treemap que compara de forma intuitiva os custos médios de envio entre diferentes mercados globais, destacando regiões de maior peso logístico.  

- **🏷️ Distribuição do Lucro Médio por Categoria (Gráfico de Rosca)**  
  → Exibe a representatividade de cada categoria de produto (Tecnologia, Móveis e Material de Escritório) no lucro médio total.  

- **🚚 Valor de Vendas por Modo de Envio (Gráfico de Cascata)**  
  → Ilustra como cada modo de envio contribui para o valor total de vendas, evidenciando os impactos positivos e negativos na soma final.  

---

## 💡 Insights Obtidos  

- 🚚 **Modo de envio** “Classe Padrão” teve o maior valor total de vendas.  
- 🌎 **Mercado APAC** apresentou o maior custo médio de envio.  
- 💰 **Categoria Tecnologia** apresentou o maior lucro médio.  
- 📉 O **valor médio de vendas** ficou **abaixo da meta de 350**, conforme o indicador KPI.  
- 📊 A **margem de lucro manteve-se estável** ao longo do período analisado, com pequenas oscilações entre os anos.  

---

## 🧠 O que Aprendi  

- Apliquei **ETL (Extração, Transformação e Carga)** com Power Query para limpeza e modelagem de dados.  
- Configurei **relacionamentos entre tabelas** garantindo integridade e consistência.  
- Desenvolvi **colunas e medidas DAX personalizadas**.  
- Explorei **indicadores KPI** para metas de desempenho.  
- Aprimorei **funções DAX** e boas práticas de formatação.  
- Realizei **personalização visual completa** com foco em clareza e impacto executivo.  

---

## 🧰 Stack  

* 💻 **Microsoft Power BI Desktop**  
* ⚙️ **Power Query**  
* 🧮 **Linguagem DAX**  

---

## 🗂️ Estrutura do Projeto  

- 📁 **/data** → Contém os arquivos CSV utilizados na análise.  
- 📁 **/dashboard** → Arquivo principal do Power BI (`.pbix`) com toda a modelagem e visualizações.  
- 📁 **/images** → Capturas de tela do dashboard finalizado.  

---
