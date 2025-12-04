# 🤖☕ LA Restaurants Insights — Abrindo uma Cafeteria com Garçons Robôs

## Sobre o Projeto
Este projeto analisa o mercado de restaurantes em Los Angeles para avaliar se abrir uma cafeteria com garçons robôs é viável — e, principalmente, se esse modelo se sustenta depois que a “novidade” passar.

## 🎯 Objetivo Principal
Mapear o cenário atual dos restaurantes em LA: tipos de estabelecimentos, presença de redes, capacidade média de assentos, distribuição geográfica e tendências por rua. A meta é entender qual formato de restaurante faz mais sentido abrir e se vale a pena criar uma rede.

---

## 📌 O Que Foi Feito

### **1. Carregamento e Preparação dos Dados**
Arquivo usado: `rest_data_us_upd.csv`.

Ações realizadas:
- Importação do dataset.
- Ajuste dos tipos de dados.
- Remoção de duplicados e tratamento de ausentes.
- Extração do nome da rua a partir do endereço.

---

### **2. Análise Exploratória (EDA)**
Análises realizadas:
- Proporção de tipos de estabelecimentos.
- Comparação entre estabelecimentos de rede e não rede.
- Identificação do tipo mais comum entre redes.
- Avaliação do perfil das redes: muitos pontos pequenos ou poucos grandes.
- Média de assentos por tipo de restaurante.
- Top 10 ruas com mais restaurantes.
- Contagem de ruas com apenas 1 restaurante.
- Distribuição de assentos em ruas com muitos restaurantes.

Visualizações produzidas:
- Gráfico de tipos de estabelecimentos.
- Gráfico de proporção rede vs não rede.
- Média de assentos por tipo.
- Top 10 ruas.
- Distribuições das capacidades.

---

## 🧩 Conclusão
- O melhor tipo de estabelecimento para abrir: **Restaurante com cerca de 48 assentos**.
- **68,4%** dos estabelecimentos em LA **não são de rede**, indicando que não vale a pena começar como rede.
- Expansão pode ser considerada depois da validação do negócio, mas não como estratégia inicial.

---

## 🚀 Entregáveis
- Notebook Jupyter com código + análises.
- Visualizações claras e interpretadas.
- Apresentação em PDF (link incluído no notebook, conforme instruções).
