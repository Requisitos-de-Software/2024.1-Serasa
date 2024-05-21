## Introdução
Os cenários são parte da composição de um caso de uso. Em um cenário temos diferentes passos que os desdobram a partir de um evento que o inicia e das condições que afetam seu comportamento. Sua descrição explora alguns pontos, são eles: como e quando um caso de uso começa, quando um caso de uso interage com os autores e quais dados eles trocam entre si, quando os casos de uso referencia ou mantém dados, como e quando os casos de uso terminam. Na descrição do cenário não abordamos aspectos de interface gráfica com o usuário, ou qualquer requisito funcional. Com isso identificaremos os cenários para identificar os os casos de uso em nosso trabalho sobre os sites dos correios.

## Metodologia
Como metodologia, usamos o método em que um cenário deve ter os seguintes elementos característicos: contexto, atores, objetivos, planejamento, ações, eventos e avaliações (CARROLL, 2002; COOPER, 1999), sendo feito da maneira apresentada na Tabela 01, com o título de cada atributo e uma descrição do mesmo.

<font ><p style="text-align: center">Tabela 01 - Estrutura de um cenário.</p></font>

| **Elemento** | **Descrição** |
|-------------|----------------|
| **Título** | Um nome que identifica o cenário. |  
| **Objetivo** | A finalidade do cenário.  |
| **Contexto** | Descreve o estado inicial do cenário, suas pré-condições e locais físicos e tempo. |
| **Atores** | Pessoa ou estruturaorganizacional que tem o papel no cenário. |
| **Recursos** | Identifica os objetos passivos com os quais lidam os atores. |
| **Episódios** | Cada episódio apresenta uma ação realizada por um ator, na qual participam outros atores utilizando os recursos disponíveis. Um episódio pode pertencer a outro cenário, e neles podemos ter restrições e exceções. As restrições são qualquer coisa que limite um episódio em um cenário. Uma exceção é o tratamento para uma ação excepcional ou de erro.  |
| **Restrição**   | As características que o cenário deve seguir  |
| **Exceção**     | O que impedem a realização do cenário  |


<font><p style="text-align: center">Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi), 2024</p></font>

## Cenários 

### 1. Calcular preços e prazos de entrega

O cenário mencionado refere-se ao objetivo de "Calcular preços e prazos de entrega". Sua descrição detalhada pode ser encontrada na tabela 2.

<font><p style="text-align: center">Tabela 02 - Cenário para Cálculo de preços e prazos de entrega.</p></font>

| **Elemento**    | **Descrição**                                                                           |
|-------------|-------------------------------------------------------------------------------------|
| **Objetivo**    |  Calcular preços e prazos através do aplicativo Correios  |
| **Contexto**    | Local: em casa<br>Tempo: Durante o dia, aproximadamente 2 minutos<br> Pré-condições: ter o CEP de origem e destino, saber o formato e peso da 	encomenda, possuir um celular com sistema Android ou IOS, ter o 	aplicativo Correios Instalado. |
| **Atores**      |  Usuário do aplicativo dos Correios  |
| **Recursos**    |  Internet, Sistema Android ou IOS, aplicativo Correios  |
| **Episódios**   | Na seção Preços e Prazos, o usuário seleciona a opção Nacional. <br> O aplicativo exibe uma tela com as informações de CEP, formato do 	objeto, peso e o valor declarado. <br>O usuário cadastra todas as informações e clica em "Simular". <br> O aplicativo exibe uma tela com as comparações dos tipos de serviços.   |
| **Restrição**   |  CEP deve existir <br> Dimensões da encomenda devem estar dentro dos padrões dos Correios.  |
| **Exceção**     | Celular sem conexão com a internet   |


<font><p style="text-align: center">Fonte: [Claudio Henrique](https://github.com/claudiohsc), 2024.</p></font>

### 2. Realizar compras na loja online

<font><p style="text-align: center">Tabela 03 - Cenário para Realizar compras na loja online dos Correios.</p></font>


| **Elemento** | **Descrição** |
| | |
| **Título** | Realizar uma compra na loja online. |  
| **Objetivo** |  Comprar selos na loja online dos correios. |
| **Contexto**| **Local**: Escritório do trabalho. <br><br> **Tempo** Meio da tarde.:  <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> Possuir um celular com conexão à internet. <li>Possuir um cadastro e estar logado no app dos correios. <li> Acessar a loja online dos correios. <li> Possuir um endereço para o recebimento de uma encomenda. <li> Possuir meios para realizar o pagamento do valor referente ao produto escolhido. </ul>|
| **Atores** | Usuário do aplicativo e site dos correios. |
| **Recursos** | Celular. <br>Acesso à internet. <br> CEP e informações do endereço para a entrega.  |
| **Episódios** | O usuário acessa a o ambiente da loja online dos correios; <br><br> Busca pelos selos desejados inserindo a temática deles no campo de busca; <br><br> Encontra os selos desejados e clica no item; <br><br> Adiciona ao carrinho clicando em comprar; <br><br> Altera a quantidade de itens e insere o CEP do destinatári; <br><br> Confere os dados de envio e dos itens escolhidos; <br><br> Escolhe a opção de pagamento por cartão de crédito; <br><br> Insere as informações do cartão e finaliza a compra.|
| **Exceções** | Usuário não consegue finalizar a compra devido a problemas com o servidor. <br><br> Informações do cartão de crédito são rejeitadas pelo sistema de pagamento. <br><br> O item desejado não está disponível em estoque no momento da compra. |
| **Restrições** | O aplicativo e o site precisam estar operacionais e acessíveis. <br><br> O usuário deve possuir uma conexão estável à internet. <br><br> O método de pagamento escolhido deve ser aceito pelo sistema. |

<font><p style="text-align: center">Fonte: [Elias F. Oliveira](https://www.github.com/EliasOliver21), 2024.</p></font>

### 3. Realizar pré-postagem

O cenário de criar e pagar uma pré-postagem utilizando o aplicativo dos Correios, é ilustrado na Tabela 05, detalhando os elementos envolvidos no processo, desde o objetivo até as exceções e restrições encontradas pelo usuário.

<font><p style="text-align: center">Tabela 04 - Cenário para realizar pré-postagem.</p></font>

| **Elemento** | **Descrição** |
| | |
| **Título** |Realizar pré-postagem |  
| **Objetivo** | Abrir o aplicativo dos correios e realizar a tarefa de fazer uma pré-postagem |
| **Contexto** | **Local**: casa do usuário <br><br> **Tempo**: início da noite <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li>Aplicativo instalado <li>Acesso à internet <li>Possuir conta no aplicativo <li>Conhecimento das informações de preenchimento obrigatório <li>Dinheiro para pagar a pré-postagem </ul>|
| **Atores** | Usuário do aplicativo dos Correios e sistema do aplicativo dos Correios |
| **Recursos** | Aparelho celular <br><br> Internet <br><br> Conta no aplicativo dos Correios <br><br> Informações sobre o endereço do remetente e do destinatário <br><br> Informações sobre a encomenda <br><br> Meio de pagamento |
| **Episódios** | Usuário acessa a tela de pré-postagem <br><br> Usuário realiza login <br><br> Aplicativo carrega endereço do remetente a partir do endereço principal na conta do usuário <br><br> Usuário insere CEP do destinatário <br><br> Apliativo carrega informações do destinatário a partir do CEP fornecido <br><br> Usuário insere nome, email e número do endereço do destinatário <br><br> Usuário informa tipo da embalagem <br><br> Usuário fornece dimensões da embalagem <br><br> Usuário escolhe serviço SEDEX <br><br> Usuário fornece dados da nota fiscal eletrônica do produto da encomenda <br><br> Usuário confere informações e adiciona postagem ao carrinho <br><br> Usuário escolhe pagar com cartão <br><br> Aplicativo gera pop-up de confirmação do meio de pagamento <br><br> Usuário confirma meio de pagamento, preenche dados do cartão e finaliza a compra |
| **Exceções** | Usuário não consegue escolher outro meio de pagamento além de cartão de crédito <br><br> Usuário fecha o app antes de terminar o pagamento e ao voltar, não consegue mais editar o carrinho |
| **Restrições** | Aplicativo não está fora do ar <br><br> Pelo menos um meio de pagamento deve estar disponível |

<font><p style="text-align: center">Fonte: [Gabriel F. J. Silva](GabrielfGH), 2024.</p></font>

### 4. Gerenciar minhas importações

<font><p style="text-align: center">Tabela 05 - Cenário para gerenciar minhas importações</p></font>

| **Elemento** | **Descrição** |
|-------------|----------------|
| **Título** | Gerenciamento de Importações |
| **Objetivo** | Permitir que o usuário gerencie suas importações, resolva pendências alfandegárias e mantenha-se atualizado sobre o status de suas encomendas. |
| **Contexto** | **Local**:  Qualquer local com acesso ao aplicativo dos Correios <br><br> **Tempo**:  Qualquer horário<br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> Aplicativo instalado <li> Acesso à internet <li>Possuir conta no aplicativo dos Correios <li> Código de rastreio <li> Ter realizado importações </ul> |
| **Atores** | Usuário, Sistema de Gerenciamento de Importações, Alfândega |
| **Recursos** | Aplicativo de gerenciamento de importações, Banco de dados de importações, Interface de usuário responsiva, Notificações push, Métodos de pagamento integrados |
| **Episódios** | 1. O usuário acessa a lista de importações.<br>2. O usuário seleciona uma importação para resolver pendências.<br>3. O usuário fornece documentos necessários ou realiza pagamentos.<br>4. O usuário recebe confirmação de que a pendência foi resolvida.<br>5. O usuário visualiza o histórico de importações e pendências resolvidas. |
| **Restrição**   | O aplicativo deve estar em conformidade com as regulamentações alfandegárias e proteger a privacidade e segurança dos dados do usuário. |
| **Exceção**     | Falhas de conexão com a internet, problemas de autenticação do usuário, indisponibilidade do sistema de gerenciamento de importações ou falhas no processamento de pagamentos. |

<font><p style="text-align: center">Fonte: [Pablo S. Costa](PabloGH), 2024.</p></font>

### 5. Rastrear encomendas

<font><p style="text-align: center">Tabela 06 - Cenário para rastrear encomendas.</p></font>

| **Elemento** | **Descrição** |
| | |
| **Título** | Rastrear encomendas |
| **Objetivo** | Permitir ao usuário do aplicativo dos Correios rastrear suas encomendas. |
| **Contexto**| **Local**:  Qualquer local com acesso ao aplicativo dos Correios <br><br> **Tempo**:  Qualquer horário<br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li> Aplicativo instalado <li> Acesso à internet <li>Possuir conta no aplicativo dos Correios <li> Código de rastreio </ul> |
| **Atores** | Usuário do aplicativo dos Correios |
| **Recursos** | Aparelho celular <br><br> Internet <br><br> Conta no aplicativo dos Correios <br><br> Código de rastreamento da encomenda |
| **Episódios** | Usuário acessa a função de rastreamento de encomendas no aplicativo dos Correios <br><br> Usuário acessa aba "Em Trânsito" <br><br> Usuário insere o código de rastreamento da encomenda <br><br> Aplicativo exibe as informações de rastreamento para o usuário |
| **Exceções** | Falha na conexão com a internet <br><br> Código de rastreamento inválido <br><br> Falha no sistema dos Correios ao buscar informações  |
| **Restrições** | Aplicativo deve ter acesso à internet <br><br> Código de rastreamento válido deve ser fornecido |

<font><p style="text-align: center">Fonte: [Ricardo Augusto](RicardoGH), 2024.</p></font>

### 6. Buscar por documentos perdidos:

<font><p style="text-align: center">Tabela 07 - Cenário para buscar por documentos perdidos.</p></font>

| **Elemento** | **Descrição** |
| | |
| **Título** | Buscar por Documentos Perdidos |
| **Objetivo** | Permitir ao usuário do aplicativo dos Correios verificar se seus documentos perdidos foram encontrados e estão disponíveis para retirada. |
| **Contexto** | **Local**: Qualquer local com acesso ao aplicativo dos Correios <br><br> **Tempo**: Qualquer horário <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li>Aplicativo instalado <li>Acesso à internet <li>Possuir conta no aplicativo <li>Informações sobre o tipo de documento e nome completo </ul>|
| **Atores** | Usuário do aplicativo dos Correios <br><br>Sistema do aplicativo dos Correios |
| **Recursos** | Aparelho celular <br><br> Internet <br><br> Conta no aplicativo dos Correios <br><br> Informações sobre os documentos perdidos |
| **Episódios** | Usuário acessa a tela de busca por documentos perdidos <br><br> Usuário seleciona o tipo de documento <br><br> Usuário insere o nome completo <br><br> Usuário clica no botão "Buscar" <br><br> Aplicativo verifica nos registros de achados e perdidos <br><br> Aplicativo exibe resultados indicando se o documento foi encontrado ou não <br><br> Caso encontrado, aplicativo fornece informações sobre a agência onde o documento pode ser retirado <br><br> Usuário pode optar por mais informações ou instruções de retirada |
| **Exceções** |  <br><br>Dados de preenchimento inválidos <br><br> Falha na conexão de internet <br><br>O nome digitado é inválido <br><br>O documento selcionado não foi encontrado |
| **Restrições** | Aplicativo deve ter acesso à internet <br><br> Os dados precisam ser preenchido de forma correta <br><br> A agência deve estar ao alcance do usuário. |

<font><p style="text-align: center"> Fonte: [Danilo Carvalho Antunes](DaniloGH), 2024.</p></font>

### 7. Mudar endereço de recebimento

<font><p style="text-align: center">Tabela 08 - Cenário para mudar endereço de recebimento.</p></font>

| **Elemento** | **Descrição** |
| | |
| **Título** | Mudar endereço de recebimento |
| **Objetivo** | Conseguir mudar onde a entrega será recebida |
| **Contexto**| **Local**: Em uma viagem <br><br> **Tempo**:  <br>Qualquer horário do dia<br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li>O pacote ainda não foi enviado <li>O aparelho telefônico usado deve ter conexão com a internet <li>Usuário logado corretamente para alterar o destino do recebimento </ul>|
| **Atores** | Usuário do sistema de recebimento dos Correios <br><br>O aplicativo dos Correios |
| **Recursos** | Usuário do aplicativo dos Correios <br><br>Aparelho telefônico <br><br>Internet disponível <br><br>Ter um recebimento pelo sistema de Correios <br><br>Conta no aplicativo dos Correios |
| **Episódios** | Usuário acessa a página principal do aplicativo dos Correios <br><br>Acessa a opção de mudar endereço de recebimento <br><br>Usuário efetua o login <br><br>Seleciona a opção endereço residencial <br><br>Digita o código do pacote que deseja mudar o endereço <br><br>Digita o novo CEP de recebimento <br><br>Aperta a tecla confirma <br><br>Digite a senha para confirmar <br><br>Aplicativo retorna uma mensagem de sucesso <br><br>Quando a encomenda chega ele recebe uma mensagem no próprio aplicativo |
| **Exceções** | Encomenda já postada <br><br>Dados de login inválidos <br><br> Falha na conexão de internet <br><br>Novo CEP digitado é inválido <br><br>CEP digitado não é cadastrado como residencial |
| **Restrições** | O prazo de alteração, somente até a encomenda ser postada <br><br>Restrição de localidades de difícil acesso, ou remotas |

<font><p style="text-align: center"> Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi), 2024.</p></font>

### 8. Receber em um local não residencial

<font><p style="text-align: center">Tabela 09 - Cenário para receber em um local não residencial.</p></font>

| **Elemento** | **Descrição** |
| | |
| **Título** | Retirar em um local não residencial |
| **Objetivo** | Conseguir receber uma encomenda em um local não-residencial |
| **Contexto**| **Local**: Em uma viagem <br><br> **Tempo**: A qualquer hora do dia <br><br> **Pré-condição**: <ul style="list-style; padding-left: 70px;"> <li>O pacote ainda não ter saído para entrega <li>Ter um aparelho telefônico com o aplicativo dos Correios <li>Ter acesso a internet <li>Uma conta no sistema do Correios </ul>|
| **Atores** | Usuário do sistema dos Correios <br><br>O aplicativo dos Correios |
| **Recursos** | Usuário do aplicativo dos Correios <br><br>Aparelho telefônico <br><br>Internet disponível <br><br>Ter um recebimento pelo sistema de Correios <br><br>Conta no aplicativo dos Correios |
| **Episódios** | Usuário entra na página principal do aplicativo dos Correios <br><br>Seleciona a opção mudar endereço de entrega <br><br>Usuário efetua o login <br><br>Seleciona a opção endereço não residencial <br><br>Escolhe a melhor opção entre locker caixa postal, ou agência mais próxima <br><br>Confirma com senha <br><br>Digita seu CEP para verificar melhores opções <br><br>Aplicativo retorna uma mensagem de sucesso na operação <br><br>Quando a encomenda chega ele recebe uma mensagem no próprio aplicativo |
| **Exceções** | Encomenda já saiu para entrega <br><br>Não há nenhuma dessas opções disponíveis para o seu CEP <br><br>Falha na conexão de internet ou com servidores dos Correios <br><br>Falha no login do usuário |
| **Restrições** | Encomendas grandes que não cabem nos lockers ou caixas postais <br><br>Disponibilidade de locais onde as opções estão disponíveis <br><br>Disponibilidade de lockers e caixas postais <br><br>Prazo que as entregas podem ficar nos locais como agências <br><br> Horário de funcionamento das agências |

<font><p style="text-align: center"> Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi), 2024.</p></font>

## Bibliografia
> 1. Engenharia de Requisitos - Sheila Reinehr. Acesso 15 de maio de 2024.
> 2. BERGMANN, Ulf; LEITE, Julio Cesar S. do Prado; BREITMAN, Karin Koogan. Um Mecanismo de Rastreamento da Evolução de Cenários Baseado em Transformações. Anais do Simpósio Brasileiro de Engenharia de Software (SBES), [S.l.], p. 63-78, out. 2003. ISSN 0000-0000. Disponível em: <https://sol.sbc.org.br/index.php/sbes/article/view/23853>. Acesso em: 18 maio 2024.
> 3. Slides professora Milene presente no site do aprender da matéria de requisitos, disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1218860>. Acesso em: 18 de maio de 2024.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  |18/05/2024 | Criação do documento | [Gabriel B. Bertolazi](https://github.com/Bertolazi) e [Gabriel F. J. Silva](https://github.com/MMcLovin) | [Ricardo Augusto][RicardoGH] |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
