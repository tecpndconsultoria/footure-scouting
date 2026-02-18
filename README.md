# SUPER_ZAGUEIRO  
### Modelo Analítico Multidimensional para Avaliação Estratégica de Zagueiros

---

## Visão Geral

O **SUPER_ZAGUEIRO** é um modelo analítico desenvolvido para avaliação comparativa de zagueiros a partir de dados estruturados do FBref.

O projeto transforma métricas brutas em um índice sintético multidimensional, permitindo:

- comparação objetiva entre atletas,
- identificação de assimetrias de perfil,
- análise estratégica para recrutamento e tomada de decisão.

O modelo foi originalmente desenvolvido como projeto final da especialização Footure e estruturado com padrão de engenharia analítica reproduzível.

---

## Problema

Avaliações tradicionais de zagueiros frequentemente:

- supervalorizam métricas isoladas,
- ignoram interdependências entre atributos,
- não oferecem leitura estratégica consolidada.

O SUPER_ZAGUEIRO resolve isso através de:

- normalização padronizada (0–1),
- agregação estruturada por dimensões,
- construção de índice sintético final.

---

## Estrutura do Modelo

O índice é composto por **8 dimensões estruturantes**:

- **Força Defensiva**
- **Posicionamento Defensivo**
- **Jogo Aéreo**
- **Jogo Mental**
- **Concentração**
- **Técnica**
- **Visão de Jogo**
- **Consistência**

Cada dimensão é construída a partir de métricas do FBref, tratadas e normalizadas.

O índice final (**SUPER_ZAGUEIRO**) consolida essas dimensões em um score sintético comparável entre atletas.

---

## Arquitetura Analítica

O projeto segue uma estrutura inspirada em camadas analíticas:

### Bronze
Dados brutos extraídos do FBref.

### Silver
Tratamento, padronização, normalização e enriquecimento.

### Wild
Camada analítica consolidada, contendo:
- dimensões finais,
- índice SUPER_ZAGUEIRO,
- base comparativa para ranking e visualizações.

---

## Principais Outputs

- Ranking dos zagueiros sul-americanos
- Identificação de Top performers por liga
- Radar comparativo entre jogadores
- Análise estratégica aplicada ao Grêmio
- Comparação com melhor zagueiro da Série A segundo o índice

---

## Visualizações

O projeto inclui:

- Scatter comparativo (Força Defensiva x Índice Geral)
- Radar multidimensional (perfil técnico-comportamental)
- Tabelas analíticas consolidadas

Todas as métricas são apresentadas em escala padronizada (0–1).

---

## Reprodutibilidade

O projeto é totalmente replicável.

## Como Executar

### Google Colab

1. Abra o notebook no Google Colab.
2. Clique em **Run All**.
3. O repositório será clonado automaticamente e as dependências instaladas.

Nenhuma configuração adicional é necessária.
