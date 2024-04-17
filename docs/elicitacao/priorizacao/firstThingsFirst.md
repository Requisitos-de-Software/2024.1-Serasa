# First Things First

## Introdução

Após a elicitação de requisitos pelos métodos de questionário, brainstorm e observação, é necessário utilizar técnicas com o intuito de priorizar os requisitos identificados. A priorização eficaz dos requisitos é essencial para direcionar os esforços de desenvolvimento de software para os elementos que agregam mais valor ao produto final. Neste contexto, a técnica "First Things First" (Primeiro as Coisas Mais Importantes) emerge como uma abordagem valiosa para ordenar os requisitos de acordo com sua importância e impacto nos objetivos do projeto. Este artefato explora os princípios e a metodologia da técnica "First Things First" na priorização de requisitos de software.

## Metodologia

Para a aplicação da técnica First Things First, é necessária a particiáção dos seguintes participantes:

- Gerente: Quem lidera o processo e apresenta os requisitos;
- Representante dos clientes: Responsável por classificar os benefícios e penalidades de cada requisito;
- Representantes de desenvolvimento: Responsável pela avaliação dos custos e riscos do desenvolvimento.

Os participantes estão descritos na tabela [1](#participantes).

<center>
<a name="participantes"></a>
<font size="2"><p>
    <b>Tabela 1</b> - Participantes.
</p></font>

| Participante | Papel |
|:-:|:-:|
| [Ricardo Augusto][RicardoGH] | |
| [Pablo S. Costa][PabloGH] | |
| Pessoa | Representante dos clientes | 

<font size="2"><p>Fonte: [Ricardo Augusto](https://github.com/avmricardo), 2024.</p></font>
</center>

A divisão das etapas foi feita da seguinte forma:

1. Listar todos os requisitos;
2. Estimar o valor de cada requisito para o cliente: Usando uma escala de 1 a 9, onde 1 é pouco valoroso e 9 é muito valoroso.
3. Estimar uma penalidade que o negócio sofreria na falta daquele requisito: Seguindo a mesma escala anterior.
4. Criar uma coluna valor total, calculada da seguinte forma:

    `Valor total =  (Benefício relativo * Peso benefício relativo) + (Penalidade relativa * Peso penalidade relativa)`

5. Estimar o custo relativo de implementação: Levando em conta a complexidade de implementação, UI necessária, reúso de telas, etc.
6. Estimar o risco da implementação de um requisito.
7. Calcular a prioridade dos requisitos com: Prioridade = Valor% / (Custo% * PesoCusto + Risco% * PesoRisco).
8. Ordenar a lista de forma decrescente de prioridade: Os requisitos do topo têm maior prioridade de implementação.

## Requisitos elicitados

Abaixo está a tabela com os requisitos elicitados nas técnicas de elicitação realizadas pelo grupo.


Legenda:

- OBSxx: Requisito número xx elicitado pela técnica de observação;
- BSxx: Requisito número xx elicitado pela técnica de brainstorming.

<center>
<a name="requisitosElicitados"></a>
<font size="2"><p>
    <b>Tabela 2</b> - Requisitos elicitados
</p></font>

| Identificação | Descrição |
|:-:|:-:|
| OBS01 | 

<font size="2"><p>Fonte: [Ricardo Augusto](https://github.com/avmricardo), 2024.</p></font>
</center>

## Resultados

Para a montagem da tabela 3 de priorização, o grupo utilizou os seguintes pesos:

- Peso benefício relativo: 2;
- Peso penalidade relativa: 1;
- Peso custo relativo: 1;
- Peso risco relativo: 0.5.

<center>
<a name="requisitosElicitados"></a>
<font size="2"><p>
    <b>Tabela 3</b> - tabela de priorização
</p></font>

<iframe class="ftf" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSPircPZBxv9AqS807qMxn-chgSU31OBT9kMPrgaXLG6-brUNsvzBGsBxeDCwjPRIorb4KbkRAMQAx8/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" ></iframe>

<font size="2"><p>Fonte: [Pablo S. Costa](PabloGH), [Ricardo Augusto](RicardoGH), 2024.</p></font>
</center>

## Bibliografia

> <a id="a" href="#aa">1.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 7: Elicitação, Modelagem, Análise. Disponível em: <https://aprender3.unb.br/pluginfile.php/2844991/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 16 abr. 2024.

| Versão | Data | Autor | Descrição | Revisor
|:-:|:-:|:-:|:-:|:-:|
|`1.0`|  | [Ricardo Augusto](https://www.github.com/avmricardo) | Criação do documento | 

[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo