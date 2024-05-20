# Requisitos Elicitados

## Introdução

Essa página contém todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [brainstorming](tecnicas/brainstorming.md), [observação](tecnicas/observacao.md) e [questionário](tecnicas/questionario.md).

## Metodologia

A tabela 1 apresenta os requisitos funcionais e a tabela 2 os não funcionais, cada uma com uma coluna para: o ID do requisito - identificando por qual técnica ele foi elicitado - uma para sua descrição, outra para o seu código de identificação dentre a categoria de requisito (funcional ou não) e uma coluna para identificar se ele está implementado ou não.

Legenda para elementos da tabela 1 e 2:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- BSx: Requisito nºx elicitado pelo Brainstorming
- OBSx: Requisito nºx elicitado pela Observação
- Qx: Requisito nºx elicitado pelo Questionário

## Requisitos funcionais

<font size="3"><p style="text-align: center">Tabela 1 - Requisitos funcionais.</p></font>

| ID | Descrição    | Código | Implementado |
| ----------- | --------------- | :------: | :------: |
| BS01 | O usuário deve poder realizar cadastro pelo app     | RF01   | Sim |
| BS02 | O usuário deve poder realizar login pelo app   | RF02   | Sim |
| BS03 | O usuário deve poder acessar o histórico de notificações do objeto  | RF03   | Não |
| BS04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo  | RF04   | Não |
| BS05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda  | RF05   | Não |
| BS06 | O usuário deve visualizar a estipulação de prazo de entrega  | RF06   | Sim |
| BS07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações	  | RF07   | Não |
| BS08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda	 | RF08   | Não |
| BS09 | O usuário deve receber notificação push pelo aplicativo		  | RF09   | Sim |
| BS10 | O usuário deve receber notificação SMS		  | RF10   | Sim |
| BS11 | O usuário deve receber notificação pelo Whatsapp		  | RF11   | Não |
| BS12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente			  | RF12   | Não |
| BS13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento	  | RF13   | Não |
| BS14 | O usuário deve poder receber o status pelo WhatsApp		  | RF14   | Não |
| BS15 | O usuário deve poder aumentar e diminuir a fonte		  | RF15   | Não |
| BS16 | O usuário deve ter a opção de ser redirecionado a um atendente para auxílio do uso do app			  | RF16   | Não |
| BS17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes)  | RF17   | Não |
| BS18 | O usuário deve poder visualizar sua encomenda no mapa  | RF18   | Não |
| BS19 | O usuário deve poder visualizar detalhes da situação do produto	  | RF19   | Sim |
| BS20 | O usuário deve poder realizar o rastreio por código mais simples	  | RF20   | Não |
| BS21 | O usuário deve poder realizar o rastreio por QR Code	  | RF21   | Sim |
| BS22 | O usuário deve receber notificação pelo e-mail		  | RF22   | Não |
| BS23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo		  | RF23   | Não |
| BS24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | RF24   | Sim |
| OBS01 | O aplicativo permite realizar login com sua conta | RF25 | Sim |
| OBS02 | O aplicativo permite rastreamento de encomendas por código. | RF26 | Sim |
| OBS03 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | RF27 | Sim |
| OBS04 | O aplicativo possibilite ver seus pagamentos | RF28 | Sim |
| OBS05 | O aplicativo oferece uma busca por agências próximas ao seu endereço | RF29 | Sim |
| OBS06 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | RF30 | Sim |
| OBS07 | O aplicativo possibilita a compra de certificados digitais dos correios | RF31 | Sim |
| OBS08 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | RF32 | Sim |
| OBS09 | O aplicativo permite visualização de mensagens | RF33 | Sim |
| OBS10 | O aplicativo oferece a visualização de vales postais | RF34 | Sim |
| OBS11 | O aplicativo oferece uma área de busca por objetos perdidos em envios | RF35 | Sim |
| OBS12 | O aplicativo fornece uma área de contato sobre violência contra a mulher | RF36 | Sim |
| Q01 | As informçãoes na página de reastreio | RF37 | Sim |
| Q02 | Filtrar o tipo de encomenda pelo tipo de entrega | RF38 | Não |
| Q03 | Assistente virtual dos correios | RF39 | Não |
| Q04 | Chat para se comunicar diretamente com o fornecedor | RF40 | Não |
| Q05 | Chat para se comunicar diretamente com o entregador | RF41 | Não |
| Q06 | Pagamento de tributos e taxas de importação | RF42 | Não |
| AD01 | O usuário deve poder escolher a opção de recebimento dentro do aplicativo antes de sua encomenda ser enviada. | RF43 | Não |
| AD02 | O usuário deve escolher o método de recebimento em até 3 cliques desde iniciar a ação. | RF44 | Não |
| AD03 | O sistema deve permitir que o usuário reserve o locker mais próximo de sua casa com base no CEP informado, de acordo com a disponibilidade. | RF45 | Não |
| AD04 | O usuário deve ser notificado quando o recebimento for efetuado. | RF46 | Não |

<font size="3"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

## Requisitos não funcionais

<font size="3"><p style="text-align: center">Tabela 2 - Requisitos não funcionais.</p></font>

| ID | Descrição    | Código | Implementado |
| ----------- | --------------- | :------: | :------: |
| BS25 | O app deve bloquear as funções em caso de furto/roubo     | RNF01 | Não |
| BS26 | O app deverá mostrar a localização da entrega em tempo real     | RNF02 | Não |
| BS27 | O app deverá identificar encomendas através de código QR Code   | RNF03 | Sim |
| BS28 | O app deverá identificar encomendas através de um e-mail     | RNF04 | Não |
| BS29 | O app deverá mostrar informação mais clara e menos poluída na Home    | RNF05 | Não |
|  BS30 | O app deverá mostrar informações de rastreio por email    | RNF06 | Não |
|  BS31 | O app deverá possui um código de rastreio mais eficiente e simples    | RNF07 | Não |
|  BS32 | O app deverá possuir um sistema de chat bot com opção de redirecionar a um atendente  | RNF10| Não |
|  BS33 | O app deverá tela de ajuda e pop-up "Precisa de ajuda?"   | RNF11 | Não |
|  BS34 | O app deverá possuir tutoriais e ou melhor informação sobre como rastrear uma encomenda  | RNF12 | Não |
|  BS35 | O app deverá ter um menor delay nas notificações de entrega  | RNF13 | Não |
|  BS36 | O app deverá ter uma melhor acessibilidade   | RNF14 | Não |
|  BS37 | O app deverá ter uma interface fluída e estável    | RNF15 | Sim |
| OBS13 | O aplicativo deve manter a privacidade dos dados do usuário. | RNF16 | Sim |
| OBS14 | O sistema de rastreamento de encomendas deve ser rápido e eficiente | RNF17 | Sim |
| OBS15 | O sistema de envio de encomendas deve ser robusto o suficiente para lidar com diferentes tipos de objetos | RNF18 | Sim |
| OBS16 | O acesso aos pagamentos deve ser protegido por autenticação do usuário | RNF19 | Não |
| OBS17 | A busca por agências deve ser precisa e baseada na localização do usuário | RNF20 | Sim |
| OBS18 | O cálculo de preços e prazos de encomendas deve ser preciso e rápido | RNF21 | Sim |
| OBS19 | A compra de certificados digitais deve ser segura e protegida | RNF22 | Sim |
| OBS20 | O acompanhamento da conta e recargas devem ser realizados de forma segura e confiável | RNF23 | Sim |
| OBS21 | A visualização de mensagens deve ser rápida e fácil de usar | RNF24 | Sim |
| OBS22 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado | RNF25 | Sim |
| OBS23 | A busca por objetos perdidos deve ser eficiente e precisa | RNF26 | Sim |
| OBS24 | A área de contato sobre violência contra a mulher deve ser sensível e oferecer suporte adequado | RNF27 | Sim |
| OBS25 | O aplicativo requer uma interface amigável e fácil de usar. | RNF28 | Sim |
| OBS26 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones. | RNF29 | Sim |
| OBS27 | O aplicativo deve fornecer notificações sobre o status da entrega. | RNF30 | Sim |
| Q07 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | RNF31 | Sim |
| Q08 | O aplicativo deve notificar o usuário com eficácia (deve enviar uma notificação 100% das vezes em que houver uma atualização sobre qualquer encomenda) | RNF32 | Não |
| Q09 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | RNF33 | Sim |
| Q10 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | RNF34 | Sim |
| Q11 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | RNF35 | Sim |
| Q12 | O chat com o entregador deve ser confiável (as mensagens devem ser arquivadas por um período de até 1 ano) | RNF36 | Não |
| AD05 | A interface deve ser intuitiva para fácil realização do procedimento. | RNF38 | Não | 
| AD06 | A funcionalidade deve ser de fácil acesso pela página principal | RNF37 | Não |

<font size="3"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

## Bibliografia

>* Grupo 01 de Requisitos de Software 2023.1. Projeto do aplicativo  Bilheteria Digital. Disponível em :  <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/>. Acesso em: 24 de Abril de 2024

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`    | 24/04/2024 | Criação do documento | [Gabriel F. J. Silva](https://github.com/MMcLovin)   | [Ricardo Augusto](https://www.github.com/avmricardo) |