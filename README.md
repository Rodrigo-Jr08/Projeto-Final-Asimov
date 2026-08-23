# README - Solução Integrada de Acompanhamento e Análise de Desempenho (Asimov Jr.)

> **Capacitação de Ciência de Dados — Projeto Final**

---

## 📌 Contexto & Problemática
A Diretoria Executiva (Direx) da Asimov Jr. enfrentava desafios no acompanhamento estruturado do desempenho da Empresa Júnior ao longo do ano:
- **Centralização:** Indicadores dispersos em diferentes fontes e dependentes de atualização manual.
- **Análise Evolutiva:** Ausência de visualização contínua de tendências de faturamento e sazonalidade.
- **Clusterização:** Dificuldade em simular e mensurar as regras de enquadramento da EJ na Régua de Cluster do MEJ.

---

## 🎯 Objetivo do Projeto
Desenvolver uma solução integrada e orientada a dados que permita à Direx visualizar, monitorar, interpretar e projetar os principais indicadores estratégicos da organização, oferecendo suporte analítico para a tomada de decisão e alcance de metas como o **Cluster 5**.

---

## 🚀 Escopo & Realizações do Projeto

### 1. Painel de Indicadores Estratégicos (Dashboard)
- **Acompanhamento de Projetos:** Quantidade de projetos ativos, novos projetos e segmentação por área.
- **Pesquisas:** Total de avaliações de CSAT coletadas.
- **Indicadores Essenciais:**
  - **Faturamento Anual:** Meta de R$ 88.000,00
  - **CSAT:** Meta de 3,5
  - **Tempo de Permanência no MEJ:** Meta de 50
  - **Engajamento com o MEJ:** Meta de 75%
- **Indicadores Complementares:**
  - **Faturamento Colaborativo:** Meta de R$ 69.752,00 (R$ 70.000,00)
  - **Políticas de Diversidade e Inclusão:** Meta de 1
  - **Projetos de Impacto:** Meta de 1 (Requisito para o Cluster 5)

---

### 2. Acompanhamento Evolutivo do Faturamento
- Visualização temporal e gráfica comparando o faturamento real com a meta acumulada mês a mês.
- Identificação rápida de *gaps* e desvios de desempenho.

---

### 3. Calculadora e Modelo Preditivo de Cluster
- **Fórmula do Índice do Cluster:**
- **Régua de Clusterização:**
  - **Cluster 1:** R$ 0,00 a R$ 12.000.000,00
  - **Cluster 2:** R$ 12.000.000,01 a R$ 24.000.000,00
  - **Cluster 3:** R$ 24.000.000,01 a R$ 61.000.000,00
  - **Cluster 4:** R$ 61.000.000,01 a R$ 130.000.000,00
  - **Cluster 5:** R$ 130.000.000,01 em diante
- **Regras e Travas Negociais:**
  - Validação de conformidade com o **Selo EJ**.
  - Rebaixamento automático para o **Cluster 1** em caso de faturamento zerado no ano.
  - Subida limitada a no máximo **1 cluster por ano**.
  - Campo Interativo (*Checkbox/Caixa de Seleção*) para adição de **Projeto de Impacto**, obrigatoriedade para o atingimento do Cluster 5.

---

### 4. Governança e Atualização dos Dados
- Estrutura simples e prática para atualização dos dados pela diretoria, reduzindo erros manuais e garantindo a confiabilidade.

---

## 📊 Resultados Esperados
- Centralização dos dados e eliminação do retrabalho operacional.
- Previsibilidade e capacidade de simulação de cenários futuros.
- Suporte consistente e contínuo para decisões estratégicas da Direx.
