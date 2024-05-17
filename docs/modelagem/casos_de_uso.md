# Casos de Uso

## Introdução

## Metodologia

<font size="2"><p style="text-align: center">Tabela 1 - Elementos do diagrama de casos de uso.</p></font>

<center>

| Símbolo | Nome | Descrição |
|:-:|:-:|:-|
| ![Ator](../assets/modelagem/use-case/ator.png) | Atores | <p>Atores representam algo ou alguém que utiliza o sistema para atingir um objetivo, podendo ser uma pessoa, organização, outro sistema ou dispositivo externo. Atores são objetos externos, que serão representados fora dos limites do projeto. Os atores também podem ser dividos em atores primários e secundários, os primários são aqueles que iniciam a utilização do sistema, que são representados do lado esquerdo do diagrama, e os secundários são os atores que reagem a uma certa ação, representados do lado direito do diagrama.</p> |
| ![Caso de uso](../assets/modelagem/use-case/caso-de-uso.png) | Casos de Uso | <p>Representa uma ação que realiza uma tarefa dentro do sistema, são representados dentro do retângulo do sistema pois são funcionalidades realizadas pelo projeto que está sendo implementado.</p> |
| ![Sistema](../assets/modelagem/use-case/sistema.png) | Sistema | <p>Projeto que está sendo desenvolvido. O retângulo que abrange o sistema representa os limites do projeto, o que ele deve realizar, separando os casos de uso, que podem ficar dentro do sistema, dos atores, que devem ficar do lado de fora do retângulo.</p> |
| ![Relacionamentos](../assets/modelagem/use-case/relacionamentos.png) | Relacionamentos | <p>São interações que acontecem entre os atores com os casos de uso ou entre os próprios casos de uso. </p> |

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

<font size="2"><p style="text-align: center">Tabela 2 - Modelo de especificação de caso de uso.</p></font>

<center>

| UCxx | Nome do caso de uso |
|-|-|
| **Descrição** | <p>Uma breve explicação do que o caso de uso faz ou descreve.</p> |
| **Atores** | <p>Os papéis ou entidades que interagem com o sistema.</p> |
| **Pré-condição** | <p> As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.</p> |
| **Pós-condição** | <p>As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.</p> |
| **Fluxo principal** | <p>A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.</p> |
| **Fluxo alternativo** | <p>Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal.</p> |
| **Fluxo de exceções** | <p>Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.</p> |

</center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo][RicardoGH], 2024.</p></font>

### 1. Calcular preços e prazos de entrega

### 2. Realizar compras na loja online

| UCxx | Nome do caso de uso |
|-|-|
| **Descrição** | <p>Uma breve explicação do que o caso de uso faz ou descreve.</p> |
| **Atores** | <p>Os papéis ou entidades que interagem com o sistema.</p> |
| **Pré-condição** | <p> As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.</p> |
| **Pós-condição** | <p>As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.</p> |
| **Fluxo principal** | <p>A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.</p> |
| **Fluxo alternativo** | <p>Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal.</p> |
| **Fluxo de exceções** | <p>Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.</p> |

<font size="2"><p style="text-align: center">Fonte: [Elias F. Oliveira](https://www.github.com/EliasOliver21), 2024.</p></font>

### 3. Emitir certificados digitais

### 4. Realizar pré-postagem

### 5. Gerenciar minhas importações

### 6. Rastrear encomendas

<font size="2"><p style="text-align: center">Tabela 8 - Rastrear encomendas.</p></font>

<center>

| UC06 | Rastrear Encomendas |
|-|-|
| **Descrição** | <p>Este caso de uso permite que os usuários do site dos correios rastreiem suas encomendas inserindo o número de rastreamento fornecido.</p> |
| **Atores** | <p>Usuário</p> |
| **Pré-condição** | <p>1. O usuário estar conectado à internet e acessando o site dos correios.<br> 2. O usuário ter em mãos o código de rastreamento da encomenda.</p> |
| **Pós-condição** | <p>O usuário recebe informações atualizadas sobre o status da sua encomenda.</p> |
| **Fluxo principal** | <p>1. O usuário acessa o site dos correios. <br> 2. O usuário acessa a página de rastreamento de encomendas. <br>3. O usuário insere o número de rastreamento da sua encomenda. <br>4. O sistema verifica o número de rastreamento e recupera as informações da encomenda. <br>5. O sistema exibe ao usuário o status atualizado da sua encomenda, incluindo sua localização e status de entrega.</p> |
| **Fluxo alternativo** | <p>1. Se o número de rastreamento fornecido pelo usuário for inválido, o sistema exibe uma mensagem de erro. <br> 2. O usuário pode corrigir o número de rastreamento e tentar novamente.</p> |
| **Fluxo de exceções** | <p>1. Se houver um problema ao recuperar as informações da encomenda, como falha de conexão com o serviço de rastreamento, o sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente mais tarde.</p> |




</center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto][RicardoGH], 2024.</p></font>

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