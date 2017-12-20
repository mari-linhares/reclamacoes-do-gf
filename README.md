# Análise de sentimento de reclamações do Governo Federal 

Análise da precisão de métodos de análise de sentimentos para estimar o grau de insatisfação nas reclamações recebidas pelos órgãos do Gov Federal via ReclameAqui.

**Grupo:**
- Iaron Araújo
- José Benardi
- Marianne Linhares
- Rafael Klynger
- Ravi Leite

## Dependências

O código é em R. Rode: 

```
deps = c("tidyverse", "rvest", "stringr")
install.packages(deps)
```

## TODO

- [x] Quantas reclamações cada pessoa analisou;
- [x] Quantas pessoas analisaram cada reclamação;
- [x] Quantidade de caracteres em uma reclamação;
- [x] Quantidade de capslock em uma reclamação;
- [x] boxplot das notas por reclamção;
- [x] Boxplot do comprimento da reclamação por órgão;
- [x] Órgãos com maior proporção de caps lock;
- [ ] Deixar nunitim;
- [x] Adicionar textin.
