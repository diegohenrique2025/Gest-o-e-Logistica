# 🚚 Dashboard de Gestão Logística e Performance de Entregas

Este projeto consiste numa análise avançada de uma operação logística, focada no controlo de prazos (SLA), eficiência dos canais de distribuição e performance das equipas de entrega por região.

## 🎯 Objetivos do Projeto
* **Controlo de SLA**: Monitorizar o status das entregas (Antecipado, No Prazo, Atrasado).
* **Eficiência Operacional**: Analisar o tempo decorrido entre a data do pedido e a entrega real.
* **Gestão de Canais**: Identificar quais canais de entrega (Canal 01 a 15) apresentam melhor desempenho.
* **Análise Regional**: Comparar a eficiência logística entre as regiões (Norte, Sul, Sudeste, etc.).

## 🛠️ Tecnologias Utilizadas
* **Power BI**: Construção de dashboards interativos e storytelling de dados.
* **Power Query**: Transformação de datas e criação de colunas condicionais para status de entrega.
* **DAX**: Cálculo de métricas de pontualidade e lead time.

## 📊 Estrutura dos Dados
A base de dados contém informações críticas como:
* **Temporal**: Datas de pedido, previsão de entrega e entrega realizada.
* **Geográfica**: Regiões de operação e IDs de cidades.
* **Parceiros**: Identificação de Clientes, Vendedores e Equipas de Entrega.
* **Status**: Classificação automática da qualidade da entrega.

## 💡 Métricas Chave (KPIs)
1. **Total de Pedidos**: Contagem distinta de IDs de pedidos.
2. **Taxa de Atraso (%)**: Percentual de pedidos entregues após a data prevista.
3. **Lead Time Médio**: Média de dias entre o pedido e a entrega final.
4. **Performance por Equipa**: Ranking de equipas com menor índice de incidentes.

## 📸 Visualização
<img width="1438" height="895" alt="image" src="https://github.com/user-attachments/assets/b412917f-5ddc-4175-8cbd-be5accfc5030" />
<img width="1439" height="900" alt="image" src="https://github.com/user-attachments/assets/ddf77ede-ed3f-4bcc-bcf8-01800cb38f38" />


![Dashboard Logística](screenshots/status_entregas.png)

---
*Projeto desenvolvido para demonstração de competências em BI aplicadas à Logística.*
