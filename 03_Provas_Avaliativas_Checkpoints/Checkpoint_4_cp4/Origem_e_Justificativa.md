# Origem e Justificativa do Problema

**Disciplina:** Algoritmos de Alta Performance
**Ano Letivo:** 2023 | **Turma:** 2ECR
**Avaliação:** Checkpoint 4

### Enunciado do Problema
Determinar a seleção ótima de pacotes de telemetria com restrição de largura de banda W = 50 KB usando Programação Dinâmica para maximizar a entropia e valor da informação transmitida.

### Formulação Formal
$$dp[i][w] = \max(dp[i-1][w], dp[i-1][w - w_i] + v_i)$$
