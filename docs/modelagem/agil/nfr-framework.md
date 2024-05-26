# NFR Framework

## Introdução

O NFR Framework é uma abordagem conceitual projetada para representar e analisar os Requisitos Não-Funcionais (RNFs) em sistemas de software. Utilizando o conceito de "softgoals", que são objetivos que não possuem uma clara definição nem critérios de satisfação precisos, o framework permite a representação das características do sistema e do domínio, considerando inter-relações entre esses softgoals. Além disso, oferece um método qualitativo para analisar o status dos softgoals, com base na satisfação de outros softgoals relacionados.

Com catálogos de requisitos organizados, o NFR Framework auxilia os desenvolvedores na escolha de alternativas de desenvolvimento, considerando interdependências e trade-offs entre os RNFs específicos. Essa estrutura flexível contribui para a implementação de soluções personalizadas que atendam às necessidades do sistema e do usuário.

### Tipos de softgoals

- Softgoals NFR: Característica abstrata, a qual se deseja considerar na análise, visando saber se a mesma será cumprida ou não cumprida. Representam requisitos não-funcionais em um sistema de software. Eles geralmente não possuem critérios de satisfação precisos e são expressos de forma qualitativa.

- Softgoals de Operacionalização: Representam as soluções de implementação de forma concreta para vibilizar ou não as características abstratas, como os softgoals NFR ou outros softgoals de operacionalização. Essencialmente os softgoals de operacionalização são as funcionalidades.

- Softgoals de Afirmação: Anotações que podem ser acrescentadas ao modelo, argumentando algo sobre um ponto específico da modelagem. Os softgoals de afirmação fornecem as razões para as decisões de desenvolvimento, facilitando a revisão, a justificativa e a mudança do sistema, bem como o aprimoramento da rastreabilidade.

<font size="2"><p style="text-align: center">Figura 1 - Tipos de softgoals.</p></font>

<center>

![Tipos de softgoals](../../assets/modelagem/agil/tipos-softgoals.png)

</center>

<font size="2"><p style="text-align: center">Fonte: (CHUNG et al., 2000)</p></font>

A figura 1 ilustra as representações dos tipos de softgoals utilizados no nfr framework, eles são representados por nuvens podendo ter linhas mais claras, mais escuras e linhas tracejadas.

## Interdependências

As interdependências representam as ligações entre os softgoals e os tipos de interdependência utilizadas pelo framework são: os refinamentos e as contribuições(CHUNG et al., 2000).Os refinamentos são o tipo de interdependência que se sucede de cima para baixo com um softgoal pai que produz softgoals filhos aos quais se conectam com seu ancestral. Os tipos de refinamento são: decomposição, operacionalização e afirmação.

### Decomposições
As decomposições realizam o refinamento dos softgoals obtendo softgoals mais específicos e especializados contribuindo para o projeto. Os quatro tipos de decomposição são descritos abaixo:

* **Decomposição de Softgoal NFR:** Realiza o refinamento de softgoals subdivindindo em softgoals mais específicos, o que auxilia a separar problemas grandes em tarefas menores.
* **Decomposição de Operacionalização:** Refina um softgoal de operacionalização dividindo-o em softgoals menores. Operacionalizações são adequadas para criar uma solução geral e a refinar em soluções menores.
* **Decomposição de Afirmação:** Refina um softgoal de afirmação em softgoals menores. A decomposição de afirmação é útil para afirmar ou negar justificativas mais específicas do projeto.
* **Priorização**: Sendo um tipo especial de decomposição, a priorização aprimora um softgoal em outro com as mesmas características e tópicos, mas com uma prioridade associada.

### Contribuições

No NFR Framework pode-se utilizar de vários tipos de contribuições que explicam de que maneira a satisfação ou não de um softgoal descendente auxilia a satisfação do softgoal ascendente. Abaixo estão os tipo de contribuições:

* **AND:** Define que se os softgoals descendentes são satisfeitos os ascendentes também serão.
* **OR:** Afirma que se pelomenos um softgoal descendente for satisfeito o ascendente também será.
* **MAKE(++):** Denota uma contribuição razoavelmente positiva entre o softgoal ascendente e o descendente. Assim, em caso de utilizar MAKE se o softgoal descendente for satisfeito o ascendente também será.
* **BREAK(--):** 
* **HELP(+):**
* **HURT(-):**
* **UNKNOWN(?):**
* **EQUALS:**
* **SOME:**

## Propagação de Impactos

## Metodologia

## 

## Subtitulo

<font size="2"><p style="text-align: center">Tabela 1 - Tabela sobre isso.</p></font>

<center>

| Coluna 1 | Coluna 2 | Coluna 3 |
|:--------:|----------|---------:|
|1.1|1.2|1.2|
|2.1|2.2|2.3|
|3.1|3.2|3.3|

</center>

<font size="2"><p style="text-align: center">Fonte: [Person](https://github.com/person), 2024.</p></font>

## Bibliografia

> 1. SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Dissertação (Mestrado em Ciência da Computação) - Centro de Informática da Universidade Federal de Pernambuco, [S. l.], 2019.


## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 23/05/2024 | Criação do documento | [Ricardo Augusto][RicardoGH] e [Elias F. Oliveira][EliasGH] |   |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
