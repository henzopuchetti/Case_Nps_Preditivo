# 📊 Case NPS Preditivo

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo analisar uma base de dados de um e-commerce para entender **quais fatores operacionais impactam a satisfação do cliente**, utilizando o **NPS (Net Promoter Score)** como principal indicador.

A proposta é:
- Identificar padrões que influenciam o NPS  
- Entender o comportamento de detratores, neutros e promotores  
- Gerar insights práticos para melhorar a experiência do cliente de forma proativa  

---

## 📁 Descrição da Base de Dados

A base utilizada (`desafio_nps_fase.csv`) contém dados relacionados à experiência do cliente, incluindo variáveis como:

- `nps_score` → Nota de satisfação do cliente  
- `delivery_delay_days` → Dias de atraso na entrega  
- `complaints_count` → Quantidade de reclamações  
- `customer_service_contacts` → Número de contatos com suporte  
- `resolution_time_days` → Tempo de resolução de problemas  

---

## ⚙️ Metodologia Utilizada

A análise foi realizada em Python no Google Colab, seguindo estas etapas:

### 1. Importação e exploração inicial
- Leitura dos dados com pandas  
- Análise estrutural com df.info() e df.describe()  
- Objetivo: entender qualidade dos dados e variáveis disponíveis

### 2. Classificação do NPS
- 0 a 6 → Detrator  
- 7 a 8 → Neutro  
- 9 a 10 → Promotor  

### 3. Distribuição dos grupos
- Análise da proporção de detratores, neutros e promotores 
- Objetivo: entender o equilíbrio entre satisfação e insatisfação 

### 4. Análise dos fatores operacionais
- Comparação entre grupos de NPS e variáveis operacionais
- Objetivo: Identificar quais fatores mais impactam cada tipo de cliente

### 5. Análise de impacto de reclamações
- Relação entre número de reclamações e NPS  
- Objetivo: entender como o aumento de problemas afeta diretamente a satisfação

---

## 🧠 Principais Insights

- Atrasos impactam negativamente o NPS  
- Mais reclamações → menor satisfação  
- Muitos contatos com suporte indicam fricção  
- Tempo alto de resolução gera detratores  

---

## ▶️ Como Reproduzir

1. Acesse o Google Colab  
2. Faça upload do notebook `Trabalho_Faculdade.ipynb`  
3. Faça upload da base `desafio_nps_fase.csv`  
4. Execute todas as células  

---

## 🎥 Vídeo Explicativo

Para uma melhor compreensão do projeto e dos resultados obtidos, assista ao vídeo abaixo:

[▶️ Assistir no YouTube](https://www.youtube.com/watch?v=O6IJFYy3qt4)

---
