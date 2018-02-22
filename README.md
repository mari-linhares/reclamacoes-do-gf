# Análise de sentimento de reclamações do Governo Federal 

Análise da precisão de métodos de análise de sentimentos para estimar o grau de insatisfação nas reclamações recebidas pelos órgãos do Gov Federal via ReclameAqui.

**Grupo:**
- Iaron Araújo
- José Benardi
- Marianne Linhares
- Rafael Klynger
- Ravi Leite

## Entrega

A entrega pode ser acessada na pasta [/analise-eda/](/analise-eda/)

## TODO EDA

- [x] Quantas reclamações cada pessoa analisou;
- [x] Quantas pessoas analisaram cada reclamação;
- [x] Quantidade de caracteres em uma reclamação;
- [x] Quantidade de capslock em uma reclamação;
- [x] boxplot das notas por reclamção;
- [x] Boxplot do comprimento da reclamação por órgão;
- [x] Órgãos com maior proporção de caps lock;
- [x] Deixar nunitim;
- [x] Adicionar textin.

## TODO REGRESSAO

- [ ] Polaridade
- [ ] Graficos 
- [ ] (Modelo) Há relação entre o léxico e a precisão/erro?
- [ ] Tratamento do Texto

**Dica** - o texto de resultado que queremos produzir é algo como: 

Regressão múltipla foi utilizada para analisar se VarIndep1 e VarIndep2 tem uma associação significativa com o erro na estimativa de instatisfação da reclemação. Os resultados da regressão indicam que um modelo com os 2 preditores no formato Erro = XXX.VarIndep1 + YYY.VarIndep2 explicam XX,XX% da variância da variável de resposta (R2 = XX,XX). VarIndep1, medida como/em [unidade ou o que é o 0 e o que é 1] tem uma relação significativa com o erro (b = [yy,yy;  zz,zz], IC com 95%), assim como VarIndep2 medida como [unidade ou o que é o 0 e o que é 1] (b = [yy,yy;  zz,zz], IC com 95%). O aumento de 1 unidade de VarIndep1 produz uma mudança de...
