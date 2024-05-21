# First Things First

## Introdução

Após a elicitação de requisitos pelos métodos de questionário, brainstorm e observação, é necessário utilizar técnicas com o intuito de priorizar os requisitos identificados. A priorização eficaz dos requisitos é essencial para direcionar os esforços de desenvolvimento de software para os elementos que agregam mais valor ao produto final. Neste contexto, a técnica "First Things First" (Primeiro as Coisas Mais Importantes) emerge como uma abordagem valiosa para ordenar os requisitos de acordo com sua importância e impacto nos objetivos do projeto. Este artefato explora os princípios e a metodologia da técnica "First Things First" na priorização de requisitos de software.

## Metodologia

1. Listar todos os requisitos;
2. Estimar o valor de cada requisito para o cliente: Usando uma escala de 1 a 9, onde 1 é pouco valoroso e 9 é muito valoroso.
3. Estimar uma penalidade que o negócio sofreria na falta daquele requisito: Seguindo a mesma escala anterior.
4. Criar uma coluna valor total: Onde Vtotal = (Benefício relativo * Peso relativo) + (Penalidade relativa * Peso relativo).
5. Estimar o custo relativo de implementação: Levando em conta a complexidade de implementação, UI necessária, reúso de telas, etc.
6. Estimar o risco da implementação de um requisito.
7. Calcular a prioridade dos requisitos com: Prioridade = Valor% / (Custo% * PesoCusto + Risco % * PesoRisco).
8. Ordenar a lista de forma decrescente de prioridade: Os requisitos do topo têm maior prioridade de implementação.

| Versão | Data | Autor | Descrição | Revisor
|:-:|:-:|:-:|:-:|:-:|
|`1.0`|  | [Ricardo Augusto](https://www.github.com/avmricardo) | Criação do documento | 