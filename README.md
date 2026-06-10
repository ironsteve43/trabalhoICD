# Análise Estatística de Desempenho no Campeonato Brasileiro Série A

Trabalho prático da disciplina "Introdução à Ciência dos Dados".

## Alunos

- Lucas de Oliveira Ferreira
- Caio Henrique de Miranda Onofre
- João Pedro Coutinho Capelão

## Estrutura do Repositório

```text
trabalhoICD/
├── data/              # Dataset original e processado
|── docs/
│   ├── tp.pdf         # Definição do tema e objetivos (primeira parte)
├── notebooks/         # Análises e modelos
│   ├── tp.ipynb       # EDA e Testes de Hipótese (segunda parte)
│   └── ml.ipynb       # Machine Learning (terceira parte)
└── repo/              # Recursos visuais e mídias
|    └── simulacao.gif
└── requiriments.txt   # Libs necessárias para execução correta dos notebooks
    
```

## Descrição do Projeto

O projeto investiga os fatores que influenciam o rendimento das equipes na Série A do Brasileirão (2003-2023).

### Notebooks

*   **`tp.ipynb` (Análise Exploratória e Estatística):** 
    *   Limpeza e tratamento de dados.
    *   Análise Exploratória de Dados (EDA) para identificar padrões.
    *   Realização de testes de hipóteses estatísticas para validar correlações (ex: impacto da permanência de treinadores, volume de chutes e faltas).

*   **`ml.ipynb` (Machine Learning e Interface):**
    *   Treinamento de modelos de aprendizado de máquina para prever resultados.

---
(Extra) Na etapa de Machine Learning, implementamos uma interface gráfica para realizar umas inferências de maneira mais agradável.

![Simulação de Jogos](repo/simulacao.gif)

