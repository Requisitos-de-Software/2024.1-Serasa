# Backward-From

## Introdução

A rastreabilidade tem como objetivo identificar e conectar requisitos durante a fase de desenvolvimento, juntamente rastreá-los ao longo do ciclo de vida do sistema.

Este documento aborda a aplicação da técnica de rastreabilidade backward-from, que tem por objetivo ligar os requisitos às suas fontes (SAYÃO; LEITE, 2005). Essa técnica possibilita simplificar a validação e verificação dos sistemas, contribuindo, assim, para a identificação de possíveis problemas.

## Metodologia

### Classificação das Informações

(apenas requisitos que foram usados, né?) -> definir metamodelo (metamodelo de toranzo + elo de evolução e responsabilidade que são do metamodelo de ramesh) -> informações sendo rastreadas -> elos usados 

Tabelas de 1 a infitio apresentam a rastreabilidade backward-from para os requisitos usados dentro do projeto.

Toranzo (2002) propõe uma classificação que comporta 4 níveis de informação: ambiental, organizacional, gerencial e de desenvolvimento. Esses níveis e suas descrições estão presentes na tabela 1.

<font size="2"><p style="text-align: center">Tabela 1 - Níveis de informação segundo Toranzo..</p></font>

<Center>

| Nível de Informação | Descrição |
| --- | --- |
| Ambiental | Compreende conceitos relacionados ao contexto político, econômico e padrões que podem afetar uma organização. Essas informações são expressas em termos de objetivos e regras políticas e econômicas que precisam ser atendidas. |
| Organizacional | Refere-se aos conceitos que impulsionam o desenvolvimento e crescimento de uma organização. Inclui a compra e uso de sistemas computacionais para agregar valor aos serviços da organização. |
| Gerencial | Concentra-se no relacionamento entre tarefas e requisitos do sistema, permitindo um melhor acompanhamento e controle dos requisitos. Contribui para o sucesso do projeto e a satisfação dos requisitos. |
| Desenvolvimento | Representa os elementos/artefatos produzidos nas diferentes atividades do desenvolvimento de software, como documentos de requisitos, diagramas e programas. Esse nível é essencial para o rastreamento de requisitos. |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto][RicardoGH], 2024.</p></font>

Essa categorização definida por Toranzo tem o intuito de definir quais informações serão identificadas, assim como classificar elas para entender melhor o processo de rastreabilidade. Para o contexto desse trabalho, destaca-se que todas as informações estão presentes dentro do nível de desenvolvimento, visto que todos os artefatos produzidos são documentos de requisitos de software.

### Meta-Modelo para o Rastreamento de Requisitos

## Rastreabilidade

SUGESTÃO DE COMO FAZER ESSA PORRA
### Requisitos Funcionais

Legendas:

> - RFx: Requisito Funcional n°X.
> - RNFx: Requisito Não Funcional n°X 
> - AD: Análise Documental
> - BS: Brainstorm 
> - OBS: Observação
> - Q: Questionário

#### RFX

<font size="2"><p style="text-align: center">Tabela 1 - tabela de elos e relacionamentos do RFX.</p></font>

<Center>

| Tipo de elo | Ligação/Relacionamentos | 
| ----------- | ----------------------- |
| *<a href="link pro artefato">RFX</a>* | |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

### Requisitos Não-Funcionais

#### RNFX

<font size="2"><p style="text-align: center">Tabela X - tabela de elos e relacionamentos do RNFX.</p></font>

<Center>

| Tipo de elo | Ligação/Relacionamentos | 
| ----------- | ----------------------- |
| *<a href="link pro artefato">RNFX</a>* | |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

## Bibliografia

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 20 de junho de 2024.
>
> 2. TORANZO, M.; CASTRO, J; MELLO, E. **Uma proposta para melhorar o rastreamento de requisitos**. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf>. Acesso em: 20 de junho de 2024.

## Referências Bibliograficas

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 21 de junho de 2024.
>

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 15/03/2024 | Criação do documento | [Cláudio Henrique](https://github.com/pabloheika)  |   |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo

