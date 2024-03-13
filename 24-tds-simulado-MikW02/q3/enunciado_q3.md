# Template para desenvolvimento e entrega do Checkpoint 2

O arquivo `claims.csv` contém uma amostra aleatória de 996 apólices de seguros de veículos referente ao periodo de 2004-2005. As variaveis do arquivo estão na seguinte ordem:
 
- (i) `valorv` (valor do veiculo em 10k dolares australianos),
- (ii) `expos`(exposição do veiculo), 
- (iii) `nsinistros`(numero de sinistros no periodo),  
- (iv) `csinistros` (custo total dos sinistros em dolares australianos),
- (v)`tipov` (tipo do veiculo em 11 categorias),
- (vi)`idadev`(idade do veiculo em 4 categorias), 
- (vii) `sexoc` (sexo do condutor principal), 
- (viii) `areac` (area de residencia do condutor principal) e 
- (ix) `idadec` (idade do condutor principal em 6 categorias).

Crie um arquivo notebook chamado `resolucao.ipynb` e desenvolva de forma clara, objetiva o que é solicitado nos itens a seguir:

a. (até 2,5 pontos) Faça inicialmente uma análise descritiva dos dados e procure agrupar em um numero menor de categorias algumas variaveis categoricas. Considere como variavel resposta (target) cmsinistros = csinistros/nsinistros.

b. (até 2 pontos) Faça um modelo de regressão linear. Faça uma análise e veja se o modelo se adequa bem ao problema (dica: análise de residuos)

c. (até 2 pontos) Faça um modelo usando arvore de decisão

d. (até 3,5 pontos) Compare os dois modelos usando a métrica mais apropriada (você deve decidir qual usar.)