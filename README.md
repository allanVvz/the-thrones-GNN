# Game of Thrones: Mineração de Grafos

Este projeto compara as redes de interação de personagens das temporadas 1 e 8 de *Game of Thrones* usando apenas notebooks Jupyter (*.ipynb*).

## Lógica e fluxo do notebook principal

1. **Carregamento de Dados**: Leitura dos arquivos `got-s1-edges.csv` e `got-s8-edges.csv`.
2. **Distribuição de Graus**: Plot de histogramas, cálculo de grau médio, densidade e transitividade.
3. **Centralidades**: Identificação dos 3 personagens mais centrais por grau, intermediação, proximidade e autovetor.
4. **Detecção de Comunidades**: Aplicação de algoritmo (e.g. Louvain), visualização colorida e comparação entre temporadas.
5. **Conclusões**: Resumo das principais diferenças e similaridades encontradas.

---

## Arquitetura simples do notebook

```
├── 1_load_data.ipynb       # Importação e limpeza básica
├── 2_degree_analysis.ipynb # Distribuição de graus e métricas
├── 3_centrality.ipynb      # Cálculo e ranking de centralidades
├── 4_communities.ipynb     # Detecção e visualização de comunidades
└── report_summary.ipynb    # Conclusões finais e comparações
```

---

## About

Análise comparativa de redes de personagens de *Game of Thrones* via grafos.

---

*Trabalho para a PUC-PR.*
