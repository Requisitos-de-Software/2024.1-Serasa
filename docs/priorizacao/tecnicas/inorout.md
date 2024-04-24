# Introdução
Após a elicitação de diversos requisitos pelos métodos de  observação, brainstorm e questionário se faz necessário o uso de meios para priorizar tais requisitos, de maneira a intender o grau de importância de cada um deles. Com isso, nessa seção a técnica utilizada para a priorização dos requisitos é a In or Out.

# Metodologia
O método consiste em classificar os requisitos em duas categorias: "In" ou "Out" (Que seria uma definição para "Dentro" ou "Fora") do escopo do projeto. O objetivo é identificar as funcionalidades que são essenciais para o projeto e as que não são. Os requisitos "In" são aqueles que o projeto não pode ser concluído sem eles, enquanto os "Out" são aqueles que são desejáveis, mas não são obrigatórios para o sucesso do projeto.

# Requisitos
A Tabela 1 a seguir contém a priorização dos Requisitos elicitados. Nem todos os requisitos estão presentes na tabela pois diferentes métodos elicitaram requisitos semelhantes.

Legenda:

- BSxx: Requisitos do Brainstorming
- OBSxx: Requisitos da Observação
- Qxx: Requisitos Questionário

<font size="2"><p style="text-align: center;">
    <b>Tabela 1</b> - Priorização dos **requisitos funcionais** de acordo com método IN or OUT 
</p></font>

| Tipo | Descrição                                                                                          | Tipo de Prioridade |
|------|----------------------------------------------------------------------------------------------------|--------------|
| BS01 | O usuário deve poder realizar cadastro pelo app                                                    |  IN  | 
| BS02, OBS01 | O usuário deve poder realizar login pelo app                                                |  IN  | 
| BS03 | O usuário deve poder acessar o histórico de notificações do objeto                                 |  OUT |
| BS04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo                 |  IN  |
| BS05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda     |  IN  |
| BS06 | O usuário deve visualizar a estipulação de prazo de entrega                                        |  IN  | 
| BS07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações	                |  IN  |
| BS08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda	        |  IN  |
| BS09 | O usuário deve receber notificação push pelo aplicativo		                                    |  IN  | 
| BS10 | O usuário deve receber notificação SMS		                                                        |  IN  | 
| BS11 | O usuário deve receber notificação pelo Whatsapp		                                            |  IN  |
| BS12, Q03 | O usuário deve ter acesso a um Chatbot para suporte ao cliente			                    |  IN  |
| BS13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento	                        |  IN  |
| BS14 | O usuário deve poder receber o status pelo WhatsApp		                                        |  IN  |
| BS15 | O usuário deve poder aumentar e diminuir a fonte		                                            |  IN  |
| BS16 | O usuário deve ter a opção de ser redirecionado a um atendente para auxílio do uso do app			|  IN  |
| BS17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes)                               |  IN  |
| BS18 | O usuário deve poder visualizar sua encomenda no mapa                                              |  IN  |
| BS19, Q01 | O usuário deve poder visualizar detalhes da situação do produto	                            |  IN  | 
| BS20, OBS02 | O usuário deve poder realizar o rastreio por código mais simples	                        |  IN  |
| BS21 | O usuário deve poder realizar o rastreio por QR Code	                                            |  IN  | 
| BS22 | O usuário deve receber notificação pelo e-mail		                                                |  IN  |
| BS23, Q06 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo     |  IN  |
| BS24, OBS06 | O usuário deve poder realizar a simulação de envio com as informações do objeto             |  IN  |
| OBS03 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro)                                |  IN  |
| OBS04 | O aplicativo possibilite ver seus pagamentos                                                      |  OUT |
| OBS05 | O aplicativo oferece uma busca por agências próximas ao seu endereço                              |  IN  |
| OBS07 | O aplicativo possibilita a compra de certificados digitais dos correios                           |  OUT |
| OBS08 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo            |  IN  |
| OBS09 | O aplicativo permite visualização de mensagens                                                    |  IN  |
| OBS10 | O aplicativo oferece a visualização de vales postais                                              |  OUT |
| OBS11 | O aplicativo oferece uma área de busca por objetos perdidos em envios                             |  IN  |
| OBS12 | O aplicativo fornece uma área de contato sobre violência contra a mulher                          |  IN  |
| Q02 | Filtrar o tipo de encomenda pelo tipo de entrega                                                    |  OUT |
| Q04 | Chat para se comunicar diretamente com o fornecedor                                                 |  IN  |
| Q05 | Chat para se comunicar diretamente com o entregador                                                 |  OUT |


<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) & [Claúdio Henrique dos Santos Carvalho](https://github.com/claudiohsc), 2024.</p></font>

<font size="2"><p style="text-align: center;">
    <b>Tabela 2</b> - Priorização dos **requisitos não funcionais** de acordo com método Ir or Out 
</p></font>

| Tipo | Descrição                                                                                          | Tipo de Prioridade |
|------|----------------------------------------------------------------------------------------------------|--------------|
| BS25 | O app deve bloquear as funções em caso de furto/roubo                                              |  IN  |
| BS27 | O app deverá identificar encomendas através de código QR Code                                      |  IN  |
| BS28 | O app deverá identificar encomendas através de um e-mail                                           |  IN  |
| BS29 | O app deverá mostrar informação mais clara e menos poluída na Home                                 |  IN  |
| BS30 | O app deverá mostrar informações de rastreio por e-mail                                            |  IN  |
| BS31 | O app deverá possui um código de rastreio mais eficiente e simples                                 |  OUT |
| BS32 | O app deverá possuir um sistema de chat bot com opção de redirecionar a um atendente               |  IN  |
| BS33 | O app deverá tela de ajuda e pop-up "Precisa de ajuda?"                                            |  IN  |
| BS34 | O app deverá possuir tutoriais e/ou melhor informação sobre como rastrear uma encomenda            |  IN  |
| BS35 | O app deverá ter um menor delay nas notificações de entrega                                        |  IN  |
| BS36 | O app deverá ter uma melhor acessibilidade                                                         |  IN  |
| BS37, OBS25 | O app deverá ter uma interface fluída, estável, amigável e fácil de usar.                   |  IN  |
| OBS13 | O aplicativo deve manter a privacidade dos dados do usuário.                                      |  IN  |
| OBS14, BS26, Q09 | O sistema de rastreamento de encomendas deve ser rápido e eficiente.                   |  IN  |
| OBS15 | O sistema de envio de encomendas deve ser robusto para lidar com diferentes tipos de objetos      |  IN  |
| OBS16 | O acesso aos pagamentos deve ser protegido por autenticação do usuário                            |  IN  |
| OBS17 | A busca por agências deve ser precisa e baseada na localização do usuário                         |  IN  |
| OBS18 | O cálculo de preços e prazos de encomendas deve ser preciso e rápido                              |  IN  |
| OBS19 | A compra de certificados digitais deve ser segura e protegida                                     |  IN  |
| OBS20 | O acompanhamento da conta e recargas devem ser realizados de forma segura e confiável             |  IN  |
| OBS21 | A visualização de mensagens deve ser rápida e fácil de usar                                       |  IN  |
| OBS22 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado     |  IN  |
| OBS23 | A busca por objetos perdidos deve ser eficiente e precisa                                         |  IN  |
| OBS24 | A área de contato sobre violência contra a mulher deve ser sensível e oferecer suporte adequado   |  IN  |
| OBS26 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones.                   |  IN  |
| OBS27, Q08 | O aplicativo deve fornecer notificações sobre o status da entrega com eficácia.              |  IN  |
| Q07 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) |  IN  |
| Q10 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | IN  |
| Q11 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) |  IN  |
| Q12 | O chat com o entregador deve ser confiável (as mensagens devem ser arquivadas por um período de até 1 ano) | IN   |


<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) & [Claúdio Henrique dos Santos Carvalho](https://github.com/claudiohsc), 2024.</p></font>

# Gravação

<iframe width="560" height="315" src="https://www.youtube.com/embed/llUlPcUKiRY?si=9KnvmFMw5kOjaLE9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[Link direto no Youtube](https://www.youtube.com/watch?v=llUlPcUKiRY)

# Blibiografia
> <a id="a" href="#aa">[1]</a> GRASSHOPPER, Disponível em: <https://github.com/Requisitos-de-Software/2022.2-Grasshopper/blob/main/docs/elicitacao/priorizacao/in-or-out.md> acessado em 16 de abril de 2024.



# Histórico de Versões
| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `1.0`  | 22/04/2024  | Criação do artefato/Preechimento | [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) & [Claúdio Henrique dos Santos Carvalho](https://github.com/claudiohsc)|[Gabriel F. J. Silva](https://github.com/MMcLovin)|
