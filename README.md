# Projeto Final — Análise de Dados no Futebol 2026  
## **FOOTURE ACADEMY**

Bem-vindo(a)!  
Este projeto foi desenvolvido no **Google Colab**, com arquivos organizados no **Google Drive**, e tem como objetivo aplicar **Análise de Dados no Futebol** para:

- criar uma **métrica autoral de avaliação defensiva** (Parte 1);
- realizar uma **análise de mercado (scout)** para identificação de reforços defensivos (Parte 2), incluindo um jogador **complementar a Lucas Halter (EC Vitória)**.

---

## Estrutura de Pastas (Mapa do Projeto)

```text
projeto_final_footure/
├── assets/
│   └── escudo_br25/
│       ├── Atletico.png
│       ├── Flamengo.png
│       ├── ...
│       └── Vitoria.png
│
├── data/
│   ├── CB.BR2025.csv
│   ├── zagueiros_br.csv
|   └── zagueiros_br_misc.csv
│
├── notebooks/
│   ├── projeto_final_footure_p1.ipynb
│   └── projeto_final_footure_p2.ipynb
│
└── reports/
    └── Relatorio_Final_Daniel.pdf
``` 
## O que há em cada pasta

### `assets/`
Arquivos visuais do projeto.  
Atualmente contém os escudos dos clubes, usados nos gráficos e rankings.

---

### `data/`
Bases de dados estatísticas (WyScout / Footure Academy).  
Esses arquivos são apenas lidos pelo código e **não devem ser editados manualmente**.

---

### `notebooks/`
Notebooks do Google Colab.  
Aqui está o arquivo principal (`projeto_final.ipynb`), onde todo o código, análises e visualizações são executados.

**Este é o ponto de partida do projeto.**

---

### `reports/`
Arquivos de relatório em Markdown/PDF.  
Contém a versão escrita do trabalho, com metodologia, resultados e conclusões.

---

## Como navegar pelo projeto

1. Comece pelo notebook em `notebooks/projeto_final.ipynb`
2. O notebook lê dados da pasta `data/`
3. Os gráficos utilizam imagens da pasta `assets/`
4. Os resultados finais estão documentados em `reports/`

---

## O que esperar do projeto

- Métrica defensiva autoral
- Análise de mercado baseada em dados reais
- Código organizado e comentado
- Relatório técnico replicável
