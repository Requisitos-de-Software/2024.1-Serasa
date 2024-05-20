# Casos de Uso

## Introdução

O diagrama de casos de uso ilustra as funcionalidades que um sistema oferece e como os usuários externos interagem com ele. Essas funcionalidades, conhecidas como casos de uso, representam as ações executadas pelo sistema. Esse diagrama é útil para detalhar as operações principais do sistema e como os usuários se envolvem com essas operações.

## Metodologia

A elaboração deste artefato seguiu uma metodologia clássica, consistindo na representação dos casos de uso por intermédio de um diagrama UML. Os componentes deste diagrama e as respectivas explicações estão detalhados na **Tabela 1**. Para a confecção do diagrama, utilizou-se o **Draw.io**, um aplicativo online especializado na criação de diagramas.

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

A especificação dos casos de uso é uma técnica utilizada para descrever detalhadamente as interações entre os usuários e o sistema. Ela documenta os passos seguidos em cada caso de uso, incluindo os eventos que desencadeiam a interação, as ações realizadas e as respostas esperadas do sistema, na tabela 2 temos o modelo base usado em nossas especificações dos casos de uso.

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

<font size="2"><p style="text-align: center">Tabela 3 - Calcular preços e prazos de entrega.</p></font>

<center>

| UC01 | Calcular preços e prazos de entrega |
|-|-|
| **Descrição** | Permite o usuário simular os preços e prazos de uma entrega antes de postá-la. |
| **Atores** | Usuário |
| **Pré-condição** | 1. Estar conectado à internet<br>2.Usuário estar na tela inicial ou menu. |
| **Pós-condição** | O usuário deve visualizar as comparações de serviços de entrega. |
| **Fluxo principal** | 1.  Na seção Preços e Prazos, o usuário seleciona a opção Nacional.<br>3. O aplicativo exibe uma tela com as informações de CEP, formato do 	objeto, peso e o valor declarado.<br>4. O usuário cadastra todas as informações e clica em "Simular".<br>5. O aplicativo exibe uma tela com as comparações dos tipos de serviços. |
| **Fluxo alternativo** | <p>Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal.</p> |
| **Fluxo de exceções** | <p>Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.</p> |

</center>

<font size="2"><p style="text-align: center">Fonte: [Claudio Henrique][ClaudioGH], 2024.</p></font>

### 2. Realizar compras na loja online

<font size="2"><p style="text-align: center">Tabela 4 - Realizar Compras na Loja Online.</p></font>
<center>

| UC02 | Realizar compras na loja online |
|-|-|
| **Descrição** | <p>Neste caso de uso é possível realizar compras de diversos itens na loja online.</p> |
| **Atores** | <p>Usuário</p> |
| **Pré-condição** | <p> 1. É necessário que o usuário acesse a página da loja online dos correios e esteja logado. </p> |
| **Pós-condição** | <p>O usuário realiza uma compra na loja online.</p> |
| **Fluxo principal** | <p>1.O usuário navega até a opção compras e logo em seguida loja online. <br>2. O usuário realiza o seu cadastro/login.<br>3.O usuário escolhe um ou mais produtos clicando neles e prosseguindo através da opção "Comprar". <br>4. O usuário edita a quantidade de itens antes de fechar a compra.<br>5. O usuário insere o CEP ou edita ele. <br>6. O usuário prossegue para a etapa de pagamento clicando em fechar pedido. <br> 7.O Usuário escolhe a forma de pagamento e finaliza a compra.  <p> |
| **Fluxo alternativo** |  |
| **Fluxo de exceções** |  |

</center>
<font size="2"><p style="text-align: center">Fonte: [Elias F. Oliveira][EliasGH], 2024.</p></font>

### 3. Emitir certificados digitais

### 4. Realizar pré-postagem

| UC04 | Realizar pré-postagem |
|-|-|
| **Descrição** | <p>Usuário realiza o processo de postagem pelo app</p> |
| **Atores** | <p>Usuário</p> |
| **Pré-condição** | <ul> <li> Ter acesso ao app <li> Possuir conexão com a internet <li> Estar logado na conta dos Correios <ul> |
| **Pós-condição** | Usuário recebe um código de confirmação da pré-postagem |
| **Fluxo principal** | <ol> <li> **Usuário faz o login** <li> **Usuário acessa a funcionalidade de pré-postagem** <li> **Usuário insere informações sobre endereço e objeto** <li> **Usuário adiciona pré-postagem ao carrinho** <li> **Usuário realiza pagamento** <ol> |
| **Fluxo alternativo** | <ol> <li value = "4"> **Usuário adiciona pré-postagem ao carrinho** <ul> <li> Usuário decide adicionar mais uma postagem ao carrinho <li> usuário decide remover uma, ou mais, postagens do carrinho </ul> <li value = "5"> **Usuário realiza pagamento** <ul> <li> Usuário escolhe pagar com pix <li> Usuário escolhe pagar com boleto </ul> <ol> |
| **Fluxo de exceções** | <ol> <li> **Usuário faz o login** <ul> <li> Usuário fornece informações de login incorretas </ul> <li value = "3"> **Usuário insere informações sobre endereço e objeto** <ul> <li> Usuário desconhece informações de preechimento obrigatório </ul> <li> **Usuário realiza pagamento** <ul> <li> **Usuário escolhe pagar com pix** <ul> <li> Opção não pode ser escolhida </ul> <li> **Usuário escolhe pagar com boleto** <ul> <li> Opção não pode ser escolhida </ul> </ul> <ol> |

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva][GabrielfGH], 2024.</p></font>

### 5. Gerenciar minhas importações
<font size="2"><p style="text-align: center">Tabela 7 - Especificação de caso de uso para gerenciar minhas importações.</p></font>

<center>

| UCxx | Gerenciar minhas importações |
|-|-|
| **Descrição** | <p>Neste caso de uso o usuario pode consultar e resolver situações alfandegarias.</p> |
| **Atores** | <p></p> |
| **Pré-condição** | <p>Acesso a internet<br>App instalado<br>Usuario autenticado</p> |
| **Pós-condição** | <p>Usuario sem pendencias alfandegarias.</p> |
| **Fluxo principal** | <p>A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.</p> |
| **Fluxo alternativo** | <p>Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal.</p> |
| **Fluxo de exceções** | <p>Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.</p> |

</center>

<font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024.</p></font>

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

### 7. Buscar por documentos perdidos:

<font size="2"><p style="text-align: center">Tabela 9 - Buscar por documentos perdidos em envios.</p></font>

<center>

| UC07 | Buscar por documentos perdidos|
|-|-|
| **Descrição** | <p>Este caso de uso permite que os usuários do site dos correios busquem pelo seus documentos caso tenham perdido algum deles, escolhendo o tipo do documento e o colocando o seu nome completo.</p> |
| **Atores** | <p>Usuário.</p> |
| **Pré-condição** | <p> 1. O usuário estar conectado à internet e acessando o site dos correios.<br> 2. O usuário ter perdido algum dos seus documentos.</p> |
| **Pós-condição** | <p> 1. O usuário recebe informações atualizadas se o seu documento está com os correios.</p> |
| **Fluxo principal** | <p>1. O usuário acessa o site dos correios. <br> 2. O usuário acessa a página de achados e perdidos. <br>3. O usuário insere o seu nome e seleciona o tipo de documento. <br>4. O sistema verifica se possui o documento do usuário. <br>5. O sistema exibe ao usuário a agência que o documento se encontra. <br>6. o usuário vai buscar o seu documento. <br>7. o usuário paga um taxa de 10 reais na agência para retirar o seu documento</p> |
| **Fluxo alternativo** | <p>1. Se o documento selecionado pelo usuário não for o documento perdido ou se o nome do usuário for preenchido de forma errada o sistema exibe uma mensagem de erro. <br> 2. O usuário pode selecionar novamente o tipo de documento que foi perdido ou corrigir o nome preenchido e tentar novamente.</p> |
| **Fluxo de exceções** | <p>1. Se houver um problema ao recuperar as informações das agências, como falha de conexão com o serviço de busca, o sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente mais tarde.</p> |

</center>

<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho Antunes][DaniloGH], 2024.</p></font>

## Bibliografia

> 1. Tutorial de Caso de Uso UML. Disponível em: <https://www.youtube.com/watch?v=ab6eDdwS3rA>. Acesso em: 15 de Maio de 2024.
>
> 2. SERRANO M., SERRANO M. Requisitos - Aula 13. Disponível em: <https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acessado em 14 de Maio de 2024.
>
> 3. Grupo 01 de Requisitos de Software 2023.1. Projeto do aplicativo Bilheteria Digital. Disponível em : https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/. Acesso em: 19 de Maio de 2024
‌

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 14/05/2024 | Criação do documento | [Ricardo Augusto][RicardoGH] & [Pablo S. Costa][PabloGH] |  |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo