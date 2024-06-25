## Introdução

A rastreabilidade é a técnica utilizada para apresentar o relacionamento entre os requisitos, arquitetura e implementação final do sistema, em suma a rastreabilidade conta a história do requisito desde sua fonte na fase de elicitação até a implementação final e o gerenciamento na pre e  pós-rastreabilidade. A rastreabilidade nos ajuda a entender e compreender melhor os relacionamentos já existentes entre os requisitos ou artefatos de requisitos, arquitetura e implementação. A pós-rastreabilidade liga os requisitos ao desenho e implementação do sistema.A rastreabilidade forward-from conecta os requisitos a artefatos de desenho e implementação.

## Metodologia

O método utilizado para fazer o gerenciamento dos requisitos será utilizando o meta-modelo de Toranzo, onde ele elenca quatro níveis de classificação que são:

- Ambiental
- Organizacional
- Gerencial
- Desenvolvimento

Será utilizada somente a classificação a nível de desenvolvimento, visto que estamos realizando um projeto para a disciplina de Requisitos de software analisando um aplicativo, então será utilizado somente teremos como base de informações os artefatos produzidos pelo grupo para a estruturação dos requisitos e suas relações com o material analisado. Será utilizado como descrito por Toranzo a criação de elos que irão interligar os requisitos aos artefatos criados pelo grupo. Abaixo temos a classificação dos tipos para a classificaçãp dos elos criados:

- **Satisfação:** indica que a classe de origem tem dependência de satisfação com classe de destino; 

- **Recurso**: indica que a classe de origem tem dependência de recurso com classe de destino;

- **Responsabilidade**: registra a participação, responsabilidade e ação de pessoas sobre artefatos; 

- **Representação**: captura a representação ou modelagem dos requisitos em outras linguagens; 

- **Alocado**: classe de origem está relacionada à classe de destino, que representa um subsistema; 

- **Agregação**: indica composição de elementos.

Teremos abaixo na tabela 01 a listagem dos requisitos elicitados com a relação de cada artefato produzido pelo grupo, e com suas respectivas siglas para melhormente serem identificados nas tabelas:  

- Legenda:
    - Personas - PS
    - Cenários - CN
    - Léxicos - LX
    - Casos de uso - CSO
    - Tema - TM
    - Épico - EP
    - Histórias de Usuário - US
    - NFR Framework - NFR

## Requisitos Funcionais

Na tabela 01 abaixo temos os requisitos funcionais elicitados e suas relações com os artefatos que foram produzidos na fase de desenvolvimento.

<font size="2"><p style="text-align: center">Tabela 01 : Requisitos Funcionais </p></font>
<center>

Requisito | Descrição | Implementado | Cenário | Léxico | Caso de Uso | Tema | Épico | História de Usuário | NFR Framework |
|  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |
| INT01 | O usuário deve poder realizar cadastro pelo app | Sim | | | | | | | | 
| INT02 | O usuário deve poder realizar login pelo app | Sim | | | | | | | | 
| INT03 | O usuário deve poder acessar o histórico de notificações do objeto | Não | | | | | | | | 
| INT04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo | Não | | | | | | | | 
| INT05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda | Não | | | | | | | | 
| INT06 | O usuário deve visualizar a estipulação de prazo de entrega | Sim | | | | | | | | 
| INT07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações | Não | | | | | | | | 
| INT08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda | Não | | | | | | | | 
| INT09 | O usuário deve receber notificações push pelo aplicativo | Sim | | | | | | | | 
| INT10 | O usuário deve receber notificações SMS | Sim | | | | | | | | 
| INT11 | O usuário deve receber notificações pelo Whatsapp | Não | | | | | | | | 
| INT12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente | Não | | | | | | | | 
| INT13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento | Não | | | | | | | | 
| INT14 | O usuário deve poder receber o status da encomenda pelo WhatsApp | Não | | | | | | | | 
| INT15 | O usuário deve poder aumentar e diminuir a fonte | Não | | | | | | | | 
| INT16 | O usuário deve ter a opção de falar com um atendente para obter ajuda | Não | | | | | | | | 
| INT17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes) | Não | | | | | | | | 
| INT18 | O usuário deve poder visualizar sua encomenda no mapa | Não | | | | | | | | 
| INT19 | O usuário deve poder visualizar detalhes da situação do produto | Sim | | | | | | | | 
| INT20 | O usuário deve poder realizar o rastreio por código mais simples | Não | | | | | | | | 
| INT21 | O usuário deve poder realizar o rastreio por QR Code | Sim | | | | | | | | 
| INT22 | O usuário deve receber notificação pelo e-mail | Não | | | | | | | | 
| INT23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo | Não | | | | | | | | 
| INT24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | Sim | | | | | | | | 
| INT25 | O aplicativo permite realizar login com sua conta | Sim | | | | | | | | 
| INT26 | O aplicativo permite rastreamento de encomendas por código. | Sim | | | | | | | | 
| INT27 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | Sim | | | | | | | | 
| INT28 | O aplicativo possibilite ver seus pagamentos | Sim | | | | | | | | 
| INT29 | O aplicativo oferece uma busca por agências próximas ao seu endereço | Sim | | | | | | | | 
| INT30 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | Sim | | | | | | | | 
| INT31 | O aplicativo possibilita a compra de certificados digitais dos correios | Sim | | | | | | | | 
| INT32 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | Sim | | | | | | | | 
| INT33 | O aplicativo permite visualização de mensagens | Sim | | | | | | | | 
| INT34 | O aplicativo oferece a visualização de vales postais | Sim | | | | | | | | 
| INT35 | O aplicativo oferece uma área de busca por objetos perdidos em envios | Sim | | | | | | | | 
| INT36 | O aplicativo fornece uma área de contato sobre violência contra a mulher | Sim | | | | | | | | 

</center>
<font size="2"><p style="text-align: center"> Fonte: [Elias Oliveira](https://github.com/EliasOliver21) e [Gabriel .B][GabrielBGH], 2024.</p></font>


## Requisitos Não-Funcionais

Na tabela 02 abaixo temos os requisitos não-funcionais elicitados e suas relações com os artefatos que foram produzidos na fase de desenvolvimento.

<font size="2"><p style="text-align: center">Tabela 02 - Requisitos Não-Funcionais.</p></font>

<Center>

| Requisito | Descrição | Implementado | Cenário | Léxico | Caso de Uso | Tema | Épico | História de Usuário | NFR Framework |
|  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |
| REQ37 | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | Não | | | | [TM-04][TM]| | |[NFR- Desempenho][NFR] |
| REQ38 | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | Não |[CN-05][CN] | |[CSU-6][CSO] |[TM-01][TM] |[EP-01][EP] | [US-02][HU]| [NFR- Desempenho][NFR]|
| REQ39 | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código | Sim | [CN-05][CN] | [L-08][LX] | [CSO-06][CSO]| [TM-01][TM] | [EP-02][EP] | [US-01][HU] | [NFR- Desempenho][NFR] |
| REQ40 | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | Não |[CN-05][CN]| |[CSU-6][CSO] |[TM-01][TM] | | | [NFR- Desempenho][NFR]|
| REQ41 | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt) | Não | | | | | | | [NFR- Desempenho][NFR]|
| REQ42 | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega | Não |[CN-05][CN] | | [CSU-6][CSO]|[TM-03][TM] |[EP-07][EP] | [US-12][HU]|[NFR- Desempenho][NFR] |
| REQ43 | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | Não |[CN-05][CN] | [L-08][LX] |[CSU-6][CSO] |[TM-01][TM] | | | [NFR- Desempenho][NFR]|
| REQ44 | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | Não | | | |[TM-04][TM] |[EP-08][EP] | [US-13][HU]|[NFR- Suportabilidade][NFR] |
| REQ45 | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | Não | | | | [TM-04][TM]|[EP-09][EP] | |[NFR- Suportabilidade][NFR] |
| REQ46 | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques | Não |[CN-05][CN] | | |[TM-04][TM] |[EP-08][EP] | [US-15][HU]| [NFR- Suportabilidade][NFR] |
| REQ47 | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status | Não | | | | [TM-03][TM]| | | [NFR- Desempenho][NFR]|
| REQ48 | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | Não | | | | [TM-04][TM]| | |[NFR- Suportabilidade][NFR] |
| REQ49 | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | Sim | | | | | | | [NFR- Desempenho][NFR]|
| REQ50 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão | Sim | | | | | | | [NFR- Confiabilidade][NFR]|
| REQ51 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas | Sim | [CN-05][CN]| [L-017][LX] |[CSU-6][CSO] |[TM-01][TM] | | | [NFR- Desempenho][NFR]|
| REQ52 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm | Sim | | [L-13][LX] | |[TM-02][TM] | | |[NFR- Desempenho][NFR] |
| REQ53 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores | Não | | | | |[EP-10][EP]| | [NFR- Confiabilidade][NFR]|
| REQ54 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros | Sim | | | | |[EP-12][EP] |[US-19][HU] | [NFR- Desempenho][NFR]|
| REQ55 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas | Sim | | [L-11][LX]|[CSU-01][CSO] | |[EP-03][EP] | [US-05][HU]|[NFR- Desempenho][NFR] |
| REQ56 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações | Sim | | | | | | | [NFR- Confiabilidade][NFR]|
| REQ57 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email | Sim | | | | |[EP-17][EP]| |[NFR- Confiabilidade][NFR] |
| REQ58 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações | Sim | | | | | | | [NFR- Desempenho][NFR]|
| REQ59 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação | Sim | | | | | | | [NFR- Confiabilidade][NFR]|
| REQ60 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas | Sim |[CN-06][CN] |  [L-02][LX]|[CSU-07][CSO] | | |[US-21][HU] | [NFR- Desempenho][NFR]|
| REQ61 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento | Sim | | | | |[EP-08][EP]|[US-22][HU] |[NFR- Desempenho][NFR] e [NFR- Suportabilidade][NFR]|
| REQ62 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial | Sim | | | | | | | [NFR- Desempenho][NFR]|
| REQ63 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior | Sim | | | | | | | [NFR- Desempenho][NFR]|
| REQ64 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status | Sim | | | |[TM-03][TM] |[EP-07][EP] |[US-03][HU] | [NFR- Desempenho][NFR]|
| REQ65 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | Sim | | | | | | | [NFR- Desempenho][NFR]|
| REQ66 | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância, para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | Não | | | |[TM-03][TM] |[EP-07][EP] |[US-11][HU] e [US-12][HU] | [NFR- Desempenho][NFR]|
| REQ67 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | Sim | [CN-05][CN]| |[CSU-06][CSO]|[TM-01][TM] | [EP-01][EP]| | [NFR- Desempenho][NFR]|
| REQ68 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | Não | | | | | | | |
| REQ69 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | Não | | [L-17][LX]|[CSU-06][CSO]|[TM-01][TM] | | |[NFR- Desempenho][NFR] |
| REQ70 | O chat com o entregador deve ser confiável (deve atender às especificações de segurança do [Art. 46](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#referencias-bibliograficas) da LGPD) | Não | | | |[TM-07][TM] |[EP-08][EP] | [US-13][HU]|[NFR- Confiabilidade][NFR] |



</Center>

<font size="2"><p style="text-align: center">Fonte: [Elias Oliveira](https://github.com/EliasOliver21) e [Gabriel .B][GabrielBGH], 2024.</p></font>

## Elos

Na tabela 03 abaixo são apresentadas as relações entre os requisitos definidos nos forward-from definidos acima e os artefatos desenvolvidos no projeto.

<font size="2"><p style="text-align: center">Tabela 03 - Elos dos Requisitos Funcionais.</p></font>

|Elo| Requisito | Satisfação | Recurso |Representação| Alocado | Agregação |
|:----:| :----: | :----: | :----: | :----: | :----: | :----: |


<font size="2"><p style="text-align: center">Fonte: [Gabriel .B][GabrielBGH], 2024. </p></font>

<font size="2"><p style="text-align: center">Tabela 04 - Elos dos Requisitos Não - Funcionais.</p></font>

| Elo | Requisito | Satisfação | Recurso | Representação | Alocado | Agregação |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Elo01 | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | Não | | | | |
| Elo02 | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | Não | | | | |
| Elo03 | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código | Sim | | | | |
| Elo04 | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | Não | | | | |
| Elo05 | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt) | Não | | | | |
| Elo06 | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega | Não | | | | |
| Elo07 | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | Não | | | | |
| Elo08 | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | Não | | | | |
| Elo09 | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | Não | | | | |
| Elo10 | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques | Não | | | | |
| Elo11 | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status | Não | | | | |
| Elo12 | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | Não | | | | |
| Elo13 | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | Sim | | | | |
| Elo14 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão | Sim | | | | |
| Elo15 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas | Sim | | | | |
| Elo16 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm | Sim | | | | |
| Elo17 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores | Não | | | | |
| Elo18 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros | Sim | | | | |
| Elo19 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas | Sim | | | | |
| Elo20 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações | Sim | | | | |
| Elo21 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email | Sim | | | | |
| Elo22 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações | Sim | | | | |
| Elo23 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação | Sim | | | | |
| Elo24 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas | Sim | | | | |
| Elo25 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento | Sim | | | | |
| Elo26 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial | Sim | | | | |
| Elo27 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior | Sim | | | | |
| Elo28 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status | Sim | | | | |
| Elo29 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | Sim | | | | |
| Elo30 | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância, para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | Não | | | | |
| Elo31 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | Sim | | | | |
| Elo32 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | Não | | | | |
| Elo33 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | Não | | | | |
| Elo34 | O chat com o entregador deve ser confiável (deve atender às especificações de segurança do [Art. 46](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#referencias-bibliograficas) da LGPD) | Não | | | | |


<font size="2"><p style="text-align: center">Fonte: [Elias F. Oliveira][EliasGH], 2024. </p></font>

## Bibliografia

> 1. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 23 de jun de 2024.
> 2. Marco Toranzo; Jaelson F. B. Castro; Elton Mello . Uma Proposta para Melhorar o Rastreamento de Requisitos. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acessado em: 23 de jun de 2024.

## Histórico de versões
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0`| 23/06/2024 | Criação do Documento | [Elias Oliveira](https://github.com/EliasOliver21) e [Gabriel .B][GabrielBGH]|  |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo

[CN]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/cenarios/
[LX]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/lexicos/
[CSO]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/casos_de_uso/
[TM]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/backlog/
[EP]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/backlog/
[HU]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/historias_de_usuario/
[NFR]: https://requisitos-de-software.github.io/2024.1-Correios/modelagem/agil/nfr-framework/