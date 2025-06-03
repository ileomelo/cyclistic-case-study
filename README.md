# Estudo de Caso: Cyclistic - Google Data Analytics Capstone


## 🚲 Sobre a Empresa Cyclistic

**Cyclistic** é uma empresa fictícia criada pelo Google como parte do seu curso de certificação em análise de dados. No cenário proposto, a Cyclistic é uma subsidiária da empresa de mobilidade **Motivate**, que opera um programa de compartilhamento de bicicletas na cidade de Chicago.

Com mais de **5.800 bicicletas** e **600 estações de acoplamento**, a Cyclistic oferece três opções de aluguel: passe único, passe diário e passe anual. A empresa acredita que o sucesso de longo prazo depende da conversão de usuários casuais (que usam passes únicos e diários) em membros anuais.

---

## 🎯 Objetivo do Estudo

A pergunta central deste estudo é:

> *"Como os membros anuais e os usuários casuais diferem em relação ao uso das bicicletas Cyclistic?"*

O objetivo é fornecer insights baseados em dados para ajudar a equipe de marketing a criar estratégias que incentivem a conversão de usuários casuais em assinantes.

---

## 🔎 Etapas do Processo Analítico

Este projeto segue as etapas do processo de análise de dados ensinadas no curso do Google:

1. **Fase de Pergunta (Ask)**
2. **Preparação dos Dados (Prepare)**
3. **Processamento dos Dados (Process)**
4. **Análise dos Dados (Analyze)**
5. **Compartilhamento dos Resultados (Share)**
6. **Ação com Base nos Dados (Act)**

---

## 🧰 Ferramentas e Técnicas Utilizadas

Embora este repositório contenha apenas a **tradução do estudo de caso original**, o projeto completo geralmente envolve:

- **Linguagens:** Python
- **Ferramentas de visualização:** Tableau, Seaborn e Matplotlib
- **Manipulação de dados:** Pandas (Python)

---

## 🧹 Processos de Limpeza de Dados

Os processos de limpeza de dados utilizados neste estudo estão documentados no arquivo **Data_Cleaning.ipynb**. Aqui estão as principais etapas realizadas:

1. **Remoção de Dados Duplicados:** Identificação e exclusão de registros duplicados para garantir a integridade dos dados.
2. **Tratamento de Valores Nulos:** Substituição ou remoção de valores ausentes em colunas críticas.
3. **Correção de Tipos de Dados:** Conversão de colunas como `started_at` e `ended_at` para o formato de data/hora apropriado.
4. **Filtragem de Dados Inválidos:** Exclusão de viagens com duração negativa ou valores inconsistentes.
5. **Normalização de Dados Categóricos:** Padronização de valores em colunas como `rideable_type` e `member_casual` para evitar inconsistências.

Essas etapas garantem que os dados estejam prontos para análise, minimizando erros e maximizando a confiabilidade dos resultados.

---

## 📂 Fonte dos Dados

Os dados utilizados para este estudo são fornecidos pela empresa **Divvy**, operadora real de bicicletas compartilhadas em Chicago, através da plataforma **[Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html)**.

Os dados foram disponibilizados pela Motivate International Inc. sob esta **[licença](https://divvybikes.com/data-license-agreement)**.

Você pode baixar os dados diretamente pelo link acima ou acessá-los conforme orientações do estudo de caso.

---

| Coluna               | Descrição                                                      |
| -------------------- | -------------------------------------------------------------- |
| `ride_id`            | ID único da viagem                                             |
| `rideable_type`      | Tipo de bicicleta (ex: elétrica, convencional, etc.)           |
| `started_at`         | Data e hora de início da viagem                                |
| `ended_at`           | Data e hora de término da viagem                               |
| `start_station_name` | Nome da estação de partida                                     |
| `start_station_id`   | ID da estação de partida                                       |
| `end_station_name`   | Nome da estação de chegada                                     |
| `end_station_id`     | ID da estação de chegada                                       |
| `start_lat`          | Latitude da estação de partida                                 |
| `start_lng`          | Longitude da estação de partida                                |
| `end_lat`            | Latitude da estação de chegada                                 |
| `end_lng`            | Longitude da estação de chegada                                |
| `member_casual`      | Tipo de usuário (`member` = assinante, `casual` = uso pontual) |

---

## 📌 Observações

Este material é uma tradução fiel ao conteúdo original, com o intuito de facilitar o entendimento de falantes da língua portuguesa.

