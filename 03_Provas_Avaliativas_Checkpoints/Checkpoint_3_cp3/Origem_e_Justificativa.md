# Origem e Justificativa do Problema

**Disciplina:** Algoritmos de Alta Performance
**Ano Letivo:** 2023 | **Turma:** 2ECR
**Avaliação:** Checkpoint 3

### Enunciado do Problema
Modelar a malha de roteamento de dados entre nós de monitoramento florestal como um grafo ponderado G = (V, E) e calcular as distâncias mínimas a partir da estação base usando Dijkstra com Heap Binário.

### Formulação Formal
$$d(v) = \min_{(u, v) \in E} \{ d(u) + w(u, v) \}, \quad T = O((V + E) \log V)$$
