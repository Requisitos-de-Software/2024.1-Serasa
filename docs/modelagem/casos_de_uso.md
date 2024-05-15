# Casos de Uso

## Introdução

## Metodologia

<font size="2"><p style="text-align: center">Tabela 1 - Elementos do diagrama de casos de uso.</p></font>

<center>

| Símbolo | Nome | Descrição |
|:-:|:-:|:-|
| ![Ator](../assets/modelagem/ator.png) | Atores | <p>Atores representam algo ou alguém que utiliza o sistema para atingir um objetivo, podendo ser uma pessoa, organização, outro sistema ou dispositivo externo. Atores são objetos externos, que serão representados fora dos limites do projeto. Os atores também podem ser dividos em atores primários e secundários, os primários são aqueles que iniciam a utilização do sistema, que são representados do lado esquerdo do diagrama, e os secundários são os atores que reagem a uma certa ação, representados do lado direito do diagrama.</p> |
| ![Caso de uso](../assets/modelagem/caso-de-uso.png) | Casos de Uso | <p>Representa uma ação que realiza uma tarefa dentro do sistema, são representados dentro do retângulo do sistema pois são funcionalidades realizadas pelo projeto que está sendo implementado.</p> |
| ![Sistema](../assets/modelagem/sistema.png) | Sistema | <p>Projeto que está sendo desenvolvido. O retângulo que abrange o sistema representa os limites do projeto, o que ele deve realizar, separando os casos de uso, que podem ficar dentro do sistema, dos atores, que devem ficar do lado de fora do retângulo.</p> |
| ![Relacionamentos](../assets/modelagem/relacionamentos.png) | Relacionamentos | <p>São interações que acontecem entre os atores com os casos de uso ou entre os próprios casos de uso. </p> |

</center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto][RicardoGH], 2024.</p></font>

Existem alguns tipos de relacionamento: 

- Associação: indica que existe uma comunicação ou interação simples entre os dois elementos do relacionamento. É representada por uma linha simples.
- Inclusão: indica uma dependência entre um caso de uso base para um caso de uso incluído, indica que um caso de uso base só irá ocorrer quando esse caso de uso incluído for finalizado. É representado por uma seta tracejada que aponta do caso base para o caso de uso incluído; 
- Extensão: indica que um caso de uso estendido será realizado somente algumas vezes em que um caso de uso base for realizado, só irá ocorrer quando alguns critérios forem cumpridos. É representado por uma seta tracejada apontando do caso estendido para o caso de uso base;
- Generalização (ou herança): indica uma hierarquia entre os casos de uso. Isso significa que um caso de uso especializado (secundário) herda comportamentos e características de um caso de uso geral (primário), mas também cada caso de uso secundário acrescenta algo novo ao caso de uso. É representado por uma seta simples, apontado do caso de uso secundário para o primário.



## Diagrama de Casos de Uso

## Especificação dos casos de uso

Modelo:

<font size="2"><p style="text-align: center">Tabela N - Nome do caso de uso.</p></font>

<center>

| UCxx | Nome do caso de uso |
|-|-|
| Descrição | <p></p> |
| Atores | <p></p> |
| Pré-condição | <p></p> |
| Pós-condição | <p></p> |
| Fluxo principal | <p></p> |
| Fluxo alternativo | <p></p> |
| Fluxo de exceções | <p></p> |

</center>

<font size="2"><p style="text-align: center">Fonte: [Fulano][], 2024.</p></font>

## Bibliografia

> 1. Tutorial de Caso de Uso UML. Disponível em: <https://www.youtube.com/watch?v=ab6eDdwS3rA>. Acesso em: 15 maio 2024.
‌

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 14/05/2024 | Criação do documento | [Ricardo Augusto][RicardoGH]  |  |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo