# **Dashboard Estratégico para Análise de Vendas e Performance de Produtos**

Este projeto tem como objetivo criar um **dashboard interativo** que fornece insights valiosos sobre vendas, desempenho de produtos e tendências de mercado, permitindo uma melhor tomada de decisão para empresas fictícias de e-commerce.

---

## **📋 Escopo do Projeto**

O projeto foca em responder às seguintes questões-chave:
- Quais são os produtos mais vendidos e os menos performáticos?
- Quais regiões e canais de venda possuem maior potencial de crescimento?
- Como as vendas variam ao longo do tempo (sazonalidade e tendências)?
- Como está o desempenho de segmentos de clientes baseados em frequência e valor de compra?
- Quais produtos e estratégias podem ser ajustados para melhorar resultados?

---

## **📝 Descrição do Projeto**

Este projeto foi desenvolvido com base nos seguintes requisitos:
1. **Bases de Dados Simuladas**:
   - Tabela de produtos com informações como nome, categoria, preço, custo e estoque.
   - Tabela de vendas relacionando produtos, clientes e dados regionais.
   - Tabela de clientes com dados demográficos e segmentação.
   - Tabela de metas de vendas por região e canal.
   - Tabela de calendário para análises temporais.

2. **Tecnologias Utilizadas**:
   - **Python**: Para simular os dados e realizar o pré-processamento.
   - **Pandas**: Manipulação e organização dos dados.
   - **Faker**: Geração de dados fictícios realistas.
   - **Power BI**: Construção do dashboard interativo.

3. **Principais KPIs Monitorados**:
   - Faturamento total, por região, categoria e canal de venda.
   - Produtos mais vendidos e com menor desempenho.
   - Análise temporal de vendas (mensal, trimestral e anual).
   - Taxa de conversão por canal.
   - Segmentação de clientes (por valor de compra e frequência).

---

## **📊 Insights Obtidos**

A partir dos dados simulados e visualizações no dashboard, é possível identificar:
1. **Produtos**:
   - Os **Top 10 produtos mais vendidos** contribuem para 60% do faturamento total.
   - Alguns produtos com baixa performance em vendas podem ser descontinuados ou reposicionados no mercado.

2. **Regiões e Canais**:
   - A **região Sudeste** é a que mais contribui para o faturamento total, com destaque para o canal online.
   - A **região Norte** possui grande potencial de crescimento, mas carece de estratégias de marketing específicas.

3. **Tendências Temporais**:
   - Picos de vendas são observados nos meses de novembro e dezembro devido à sazonalidade de compras (Black Friday e Natal).
   - Quedas nas vendas são identificadas nos meses de março e abril, indicando uma oportunidade para promoções nesses períodos.

4. **Clientes**:
   - Segmentos de clientes **Alta Receita** representam 35% do faturamento, mas possuem menor frequência de compra.
   - Clientes recorrentes possuem maior impacto em canais físicos.

---

## **🎯 Proposta do Projeto**

O objetivo principal deste projeto é demonstrar como uma análise baseada em dados pode impactar decisões estratégicas em um cenário fictício de e-commerce. Com isso, o projeto:
- **Apresenta habilidades técnicas** em manipulação de dados, geração de visualizações e storytelling.
- **Simula um ambiente empresarial real** com problemas práticos a serem resolvidos.
- **Fornece insights acionáveis** que poderiam ser implementados em um contexto empresarial.

---

## **📂 Estrutura do Projeto**

O projeto está organizado da seguinte forma:

```plaintext
.
├── data/                   # Diretório para os datasets gerados
│   ├── products.csv        # Dados da tabela de produtos
│   ├── sales.csv           # Dados da tabela de vendas
│   ├── customers.csv       # Dados da tabela de clientes
│   ├── targets.csv         # Metas de vendas (regiões e canais)
│   ├── calendar.csv        # Dados de calendário
├── scripts/                # Scripts Python utilizados
│   ├── generate_data.py    # Script para geração dos dados simulados
│   ├── analysis.py         # Script para análises complementares
├── dashboard.pbix          # Arquivo do Power BI com o dashboard final
├── README.md               # Documentação do projeto
```

---

## **📈 Exemplos de Visualizações**

### **1. Resumo Executivo**
- **KPIs principais**: Faturamento total, crescimento anual, e lucros por canal.

### **2. Performance de Produtos**
- Gráfico de barras exibindo os **Top 10 produtos mais vendidos**.
- Tabela dinâmica mostrando produtos com menor desempenho.

### **3. Análise Temporal**
- Série temporal indicando tendências de vendas ao longo de 2022, 2023 e 2024.

### **4. Segmentação de Clientes**
- Análise de clientes baseada em **valor de compra** e **frequência de compras**.

---

## **💡 Conclusão**

Este projeto demonstra como dados bem estruturados e visualizados podem ajudar na tomada de decisão estratégica. Ele combina habilidades técnicas e de negócios, apresentando uma solução completa para análise de vendas e performance de produtos.

