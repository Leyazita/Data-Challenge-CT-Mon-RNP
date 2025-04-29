# Data Challenge CT-Mon/RNP

**Desafio de Previsão de Métricas de Desempenho na RedeIpê**  
Este repositório documenta a participação no **Data Challenge CT-Mon/RNP**, desenvolvido durante a disciplina **Tópicos em Mineração de Dados (2024.2)**.

---

## Descrição do Desafio

O contexto do desafio gira em torno de um problema clássico em monitoramento de redes: **a escolha do melhor servidor para entrega de conteúdo** ao cliente.

Imagine que você está assistindo a um vídeo em um serviço de streaming. Garantir que o vídeo chegue com qualidade e sem interrupções envolve selecionar, em tempo real, o servidor ideal — levando em consideração fatores como congestionamento da rede e métricas de qualidade de experiência (QoE).

Para enfrentar esse problema, o desafio propõe:

- Prever **métricas de rede** (como DASH, RTT e Traceroute) entre pares cliente-servidor na **RedeIpê**.
- Cada consulta do conjunto `Q` inclui medições em um intervalo de tempo `[ti, tf]` (desconhecido).
- O objetivo é prever a **média** e o **desvio padrão** das duas próximas medições de DASH para cada consulta.

📎 **Mais informações sobre o desafio**:  
[Documentação oficial (PDF)](https://drive.google.com/file/d/1EQm_2uubv6H1QxpNis8rYSrRCWaVkX4E/view)

---

## Objetivos na Disciplina

Durante a disciplina, buscamos propor uma solução eficaz para o desafio do CT-Mon/RNP, documentando os métodos utilizados e os resultados obtidos em um **relatório técnico**.

A proposta deveria contemplar ao menos um dos seguintes tópicos abordados na disciplina:

1. Análise descritiva de dados  
2. Séries temporais  
3. Caracterização de cargas de trabalho  
4. Classificação  
5. Regressão  
6. Agrupamento  
7. Ciência de redes  

---

## Etapas da Solução

Iniciamos a resolução estudando as abordagens das **equipes vencedoras** do desafio. A partir disso, seguimos com as seguintes etapas:

🔗 **Estudo das soluções anteriores**  
[Vídeo de apresentação](https://eduplay.rnp.br/portal/video/228055)

 **Exploração dos dados no Kaggle**  
- Acesso ao conjunto de dados completo  
- Dados de treino: DASH, RTT, Traceroute  
- Dados de teste e formato de submissão  
[Dataset Kaggle](https://www.kaggle.com/competitions/open-data-challenge-ct-mon-rnp/data)

 **Desenvolvimento da solução**  
- Código em Python (notebook Jupyter) disponível neste repositório  
- Relatório técnico explicativo, baseado no **template da SBC**  
  - [Versão no Overleaf](https://pt.overleaf.com/read/hskqrzssdfkh#7803bd)  
  - [PDF disponível neste repositório]

 **Resultado final**  
- Submetemos a solução na plataforma Kaggle  
- **Baseline do desafio** (MAPE = **0.0995022123**)
- Nosso resultado foi **superior ao baseline do desafio** (MAPE = **0.0817763788**)

---

## Autoras

- **Vandirleya Barbosa**  
- **Melissa Alves**

**Disciplina:** Tópicos em Mineração de Dados  
**Período:** 2024.2  
🔗 [Desafio no Kaggle](https://kaggle.com/competitions/open-data-challenge-ct-mon-rnp)

---

## Estrutura do Repositório

Data-Challenge-CT-Mon-RNP 

├── 📜 README.md 

├── 📓 Trabalho Final - Data Challenge CT-Mon.ipynb 

├── 📄 Trabalho_Final_Desafio_CT_Mon_RNP.pdf

---

> Este projeto é parte de um exercício acadêmico com fins de aprendizado e desenvolvimento de competências em mineração de dados e modelagem preditiva aplicadas a redes de computadores.
