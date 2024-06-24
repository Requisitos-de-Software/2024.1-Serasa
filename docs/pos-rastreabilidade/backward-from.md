# Backward-From

## Introdução

A rastreabilidade tem como objetivo identificar e conectar requisitos durante a fase de desenvolvimento, juntamente rastreá-los ao longo do ciclo de vida do sistema.

Este documento aborda a aplicação da técnica de rastreabilidade backward-from, que tem por objetivo ligar os requisitos às suas fontes (SAYÃO; LEITE, 2005). Essa técnica possibilita simplificar a validação e verificação dos sistemas, contribuindo, assim, para a identificação de possíveis problemas.

## Metodologia

### Classificação das Informações

(apenas requisitos que foram usados, né?) -> definir metamodelo (metamodelo de toranzo + elo de evolução e responsabilidade que são do metamodelo de ramesh) -> informações sendo rastreadas -> elos usados 

Tabelas de 1 a infitio apresentam a rastreabilidade backward-from para os requisitos usados dentro do projeto.

Toranzo (2002) propõe uma classificação que comporta 4 níveis de informação: ambiental, organizacional, gerencial e de desenvolvimento. Esses níveis e suas descrições estão presentes na tabela 1.

<font size="2"><p style="text-align: center">Tabela 1 - Níveis de informação segundo Toranzo.</p></font>

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

A partir das informações descritas no tópico anterior, Toranzo (2002) define um meta-modelo descrevendo os tipos de relacionamento usados para rastrear informações, sendo eles descritos na tabela 2.

<font size="2"><p style="text-align: center">Tabela 2 - Relacionamentos entre infomações segundo Toranzo.</p></font>

<Center>

| Relacionamento | Descrição |
| --- | --- |
| Satisfação | Representa uma associação de dependência em que a classe origem requer a satisfação da classe destino para cumprir seus objetivos. Por exemplo, um requisito específico pode depender da satisfação de outro requisito para ser atendido. |
| Recurso | Refere-se a uma associação de dependência em que a classe origem tem uma dependência de recurso com a classe destino. Essa relação visa manter a consistência das informações nas instâncias da classe origem, utilizando elementos físicos ou informações como recursos. Por exemplo, um requisito pode depender de um documento de especificação como recurso. |
| Responsabilidade | Captura a participação, responsabilidade e ação das pessoas sobre artefatos ou elementos do processo de software. Por exemplo, a participação de um analista e programador em relação a um subsistema específico. |
| Representação | Essa associação visa capturar a representação dos requisitos em linguagens de modelagem ou programação. É natural no processo de desenvolvimento de software e permite expressar os requisitos de maneira mais detalhada. Por exemplo, um requisito pode ser representado por meio de diagramas UML ou código-fonte. |
| Alocado | Expressa que a classe origem está relacionada com uma instância da classe destino, que representa um subsistema. Indica a alocação de responsabilidades ou recursos entre as partes do sistema. Por exemplo, um requisito pode estar alocado a um subsistema específico. |
| Agregação | Ajuda a expressar que um elemento está composto de outros elementos. É usado para representar a estrutura hierárquica ou composição de partes em um sistema. Por exemplo, um requisito pode ser agregado a outros requisitos para formar um conjunto funcional. |


</Center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto][RicardoGH], 2024.</p></font>

## Rastreabilidade

SUGESTÃO DE COMO FAZER ESSA PORRA
### Requisitos Funcionais

Legendas:

> - RFx: Requisito Funcional n°X.
> - RNFx: Requisito Não Funcional n°X 
> - AD: Análise Documental
> - BS: Brainstorm 
> - OB: Observação
> - QS: Questionário

<font size="2"><p style="text-align: center">Tabela 1 - RFX.</p></font>

<Center>

| ID | Descrição | Fonte | Implementado | Versão |
| --- | --- | --- | --- | --- |
| RF01 | O usuário deve poder realizar cadastro pelo app | [BS01][BSRF] | Sim | `1.0` |
| RF02 | O usuário deve poder realizar login pelo app | [BS02][BSRF] | Sim | `1.0` |
| RF03 | O usuário deve poder acessar o histórico de notificações do objeto | [BS03][BSRF] | Não | `1.0` |
| RF04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo | [BS04][BSRF] | Não | `1.0` |
| RF05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda | [BS05][BSRF] | Não | `1.0` |
| RF06 | O usuário deve visualizar a estipulação de prazo de entrega | [BS06][BSRF] | Sim | `1.0` |
| RF07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações | [BS07][BSRF] | Não | `1.0` |
| RF08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda | [BS08][BSRF] | Não | `1.0` |
| RF09 | O usuário deve receber notificações push pelo aplicativo | [BS09][BSRF] | Sim | `1.0` |
| RF10 | O usuário deve receber notificações SMS | [BS10][BSRF] | Sim | `1.0` |
| RF11 | O usuário deve receber notificações pelo Whatsapp | [BS11][BSRF] | Não | `1.0` |
| RF12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente | [BS12][BSRF] | Não | `1.0` |
| RF13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento | [BS13][BSRF] | Não | `1.0` |
| RF14 | O usuário deve poder receber o status da encomenda pelo WhatsApp | [BS14][BSRF] | Não | `1.1` |
| RF15 | O usuário deve poder aumentar e diminuir a fonte | [BS15][BSRF] | Não | `1.0` |
| RF16 | O usuário deve ter a opção de falar com um atendente para obter ajuda | [BS16][BSRF] | Não | `1.1` |
| RF17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes) | [BS17][BSRF] | Não | `1.0` |
| RF18 | O usuário deve poder visualizar sua encomenda no mapa | [BS18][BSRF] | Não | `1.0` |
| RF19 | O usuário deve poder visualizar detalhes da situação do produto | [BS19][BSRF] | Sim | `1.0` |
| RF20 | O usuário deve poder realizar o rastreio por código mais simples | [BS20][BSRF] | Não | `1.0` |
| RF21 | O usuário deve poder realizar o rastreio por QR Code | [BS21][BSRF] | Sim | `1.0` |
| RF22 | O usuário deve receber notificação pelo e-mail | [BS22][BSRF] | Não | `1.0` |
| RF23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo | [BS23][BSRF] | Não | `1.0` |
| RF24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | [BS24][BSRF] | Sim | `1.0` |
| RF25 | O aplicativo permite realizar login com sua conta | [OBS01][OBSRF] | Sim | `1.0` |
| RF26 | O aplicativo permite rastreamento de encomendas por código. | [OBS02][OBSRF] | Sim | `1.0` |
| RF27 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | [OBS03][OBSRF] | Sim | `1.0` |
| RF28 | O aplicativo possibilite ver seus pagamentos | [OBS04][OBSRF] | Sim | `1.0` |
| RF29 | O aplicativo oferece uma busca por agências próximas ao seu endereço | [OBS05][OBSRF] | Sim | `1.0` |
| RF30 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | [OBS06][OBSRF] | Sim | `1.0` |
| RF31 | O aplicativo possibilita a compra de certificados digitais dos correios | [OBS07][OBSRF] | Sim | `1.0` |
| RF32 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | [OBS08][OBSRF] | Sim | `1.0` |
| RF33 | O aplicativo permite visualização de mensagens | [OBS09][OBSRF] | Sim | `1.0` |
| RF34 | O aplicativo oferece a visualização de vales postais | [OBS10][OBSRF] | Sim | `1.0` |
| RF35 | O aplicativo oferece uma área de busca por objetos perdidos em envios | [OBS11][OBSRF] | Sim | `1.0` |
| RF36 | O aplicativo fornece uma área de contato sobre violência contra a mulher | [OBS12][OBSRF] | Sim | `1.0` |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

### Requisitos Não-Funcionais

<font size="2"><p style="text-align: center">Tabela 1 - RFX.</p></font>

<Center>

| ID | Descrição | Fonte | Implementado | Versão |
| --- | --- | --- | --- | --- |
| RNF01 | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | [BS25][BSRNF] | Não | `2.0` |
| RNF02 | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | [BS26][BSRNF] | Não | `2.0` |
| RNF03 | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código | [BS27][BSRNF] | Sim | `2.0` |
| RNF04 | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | [BS28][BSRNF] | Não | `2.0` |
| RNF05 | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt) | [BS29][BSRNF] | Não | `2.0` |
| RNF06 | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega | [BS30][BSRNF] | Não | `2.0` |
| RNF07 | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | [BS31][BSRNF] | Não | `2.0` |
| RNF08 | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | [BS32][BSRNF] | Não | `2.0` |
| RNF09 | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | [BS33][BSRNF] | Não | `2.0` |
| RNF10 | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques | [BS34][BSRNF] | Não | `2.0` |
| RNF11 | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status. | [BS35][BSRNF] | Não | `2.0` |
| RNF12 | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | [BS36][BSRNF] | Não | `2.0` |
| RNF13 | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | [BS37][BSRNF] | Sim | `2.0` |
| RNF14 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão. | [OBS13][OBSRNF] | Sim | `2.0` |
| RNF15 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas. | [OBS14][OBSRNF] | Sim | `2.0` |
| RNF16 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm. | [OBS15][OBSRNF] | Sim | `2.0` |
| RNF17 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores. | [OBS16][OBSRNF] | Não | `2.0` |
| RNF18 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros. | [OBS17][OBSRNF] | Sim | `2.0` |
| RNF19 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas. | [OBS18][OBSRNF] | Sim | `2.0` |
| RNF20 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações. | [OBS19][OBSRNF] | Sim | `2.0` |
| RNF21 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email. | [OBS20][OBSRNF] | Sim | `2.0` |
| RNF22 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações. | [OBS21][OBSRNF] | Sim | `2.0` |
| RNF23 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação. | [OBS22][OBSRNF] | Sim | `2.0` |
| RNF24 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas. | [OBS23][OBSRNF] | Sim | `2.0` |
| RNF25 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento. | [OBS24][OBSRNF] | Sim | `2.0` |
| RNF26 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial. | [OBS25][OBSRNF] | Sim | `2.0` |
| RNF27 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior. | [OBS26][OBSRNF] | Sim | `2.0` |
| RNF28 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status. | [OBS27][OBSRNF] | Sim | `2.0` |
| RNF29 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | [Q07][QRNF] | Sim | 1.0 |
| RFN30 | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância, para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | [Q08][QRNF] | Não | 1.1 |
| RNF31 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | [Q09][QRNF] | Sim | 1.0 |
| RNF32 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | [Q10][QRNF] | Não | 1.0 |
| RNF33 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | [Q11][QRNF] | Não | 1.0 |
| RNF34 | O chat com o entregador deve ser confiável (deve atender às especificações de segurança do [Art. 46](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#referencias-bibliograficas) da LGPD) | [Q12][QRNF] | Não | 1.1 |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

## Elos

<font size="2"><p style="text-align: center">Tabela x - Elos dos Requisitos Funcionais.</p></font>

<center>

| ID  | Descrição|Tipo de Relacionamento | Descrição do Relacionamento|
| - | -| - | - | 
| RF01 | O usuário deve poder realizar cadastro pelo app |  Satisfação | Este requisito depende de uma base de dados para armazenar as informações do usuário. |
| RF02 | O usuário deve poder realizar login pelo app |  Satisfação | Depende do cadastro de usuários (RF01) para funcionar. |
| RF03 | O usuário deve poder acessar o histórico de notificações do objeto |  Recurso | Requer um banco de dados que armazena o histórico de notificações. |
| RF04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo | Recurso | Necessita integração com funcionalidades de segurança do sistema operacional do dispositivo. |
| RF05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda |  Recurso | Depende da disponibilidade de hardware (chip de localização) para ser implementado. |
| RF06 | O usuário deve visualizar a estipulação de prazo de entrega |  Representação | Este requisito pode ser representado por meio de uma interface de usuário detalhando prazos. |
| RF07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações |  Representação | Requer integração com o sistema de logística para obter e mostrar atualizações. |
| RF08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda | Agregação | Faz parte de um conjunto de funcionalidades de suporte ao cliente. |
| RF09 | O usuário deve receber notificações push pelo aplicativo |  Responsabilidade | Depende da configuração de serviços de notificação push, geralmente responsabilidade do administrador do sistema. |
| RF10 | O usuário deve receber notificações SMS |  Responsabilidade | Similar ao RF09, mas com foco em serviços de SMS, responsabilizando o administrador de telecomunicações. |
| RF11 | O usuário deve receber notificações pelo WhatsApp |  Responsabilidade | Depende da integração com a API do WhatsApp e a configuração por parte do administrador de serviços. |
| RF12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente |  Alocado | Este requisito está alocado ao subsistema de suporte ao cliente. |
| RF13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento |  Representação | Pode ser representado por meio de vídeos ou textos explicativos na interface do usuário. |
| RF14 | O usuário deve poder receber o status da encomenda pelo WhatsApp |  Responsabilidade | Similar ao RF11, mas focado em enviar informações de status especificamente. |
| RF15 | O usuário deve poder aumentar e diminuir a fonte |  Representação | Requer ajustes na interface de usuário para permitir controle de tamanho de fonte. |
| RF16 | O usuário deve ter a opção de falar com um atendente para obter ajuda |  Alocado | Está alocado ao subsistema de suporte ao cliente. |
| RF17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes) |  Agregação | Parte do subsistema de suporte ao cliente, agregando várias perguntas e respostas. |
| RF18 | O usuário deve poder visualizar sua encomenda no mapa |  Representação | Requer integração com APIs de mapas para exibir a localização da encomenda. |
| RF19 | O usuário deve poder visualizar detalhes da situação do produto |  Recurso | Requer acesso a dados detalhados sobre a encomenda. |
| RF20 | O usuário deve poder realizar o rastreio por código mais simples |  Representação | Requer uma interface de entrada simplificada para códigos de rastreamento. |
| RF21 | O usuário deve poder realizar o rastreio por QR Code | Representação | Necessita uma interface que permita a leitura de QR Codes. |
| RF22 | O usuário deve receber notificação pelo e-mail |  Responsabilidade | Depende de integração com serviços de e-mail e configuração adequada. |
| RF23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo | Recurso | Requer integração com sistemas de pagamento e bancos. |
| RF24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | Representação | Simulação de envio depende de um subsistema que calcula tarifas e prazos. |
| RF25 | O aplicativo permite realizar login com sua conta |  Satisfação | Depende da funcionalidade de cadastro de usuário (RF01). |
| RF26 | O aplicativo permite rastreamento de encomendas por código |  Representação | Requer interface de rastreamento integrada com base de dados de encomendas. |
| RF27 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) |  Agregação | Parte das funcionalidades principais do aplicativo, agregando várias formas de envio. |
| RF28 | O aplicativo possibilita ver seus pagamentos |  Representação | Requer uma interface para visualizar histórico e detalhes de pagamentos. |
| RF29 | O aplicativo oferece uma busca por agências próximas ao seu endereço |  Recurso | Integração com serviços de localização e base de dados de agências. |
| RF30 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais |  Recurso | Integração com sistemas de cálculo de tarifas e prazos de entrega. |
| RF31 | O aplicativo possibilita a compra de certificados digitais dos correios | Recurso | Integração com sistemas de venda e emissão de certificados digitais. |
| RF32 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo |  Recurso | Integração com sistemas de gerenciamento de contas e serviços de recarga. |
| RF33 | O aplicativo permite visualização de mensagens | Representação | Requer uma interface que exibe mensagens recebidas pelo usuário. |
| RF34 | O aplicativo oferece a visualização de vales postais | Representação | Necessita de uma interface que permita ao usuário visualizar informações sobre vales postais. |
| RF35 | O aplicativo oferece uma área de busca por objetos perdidos em envios |  Agregação | Parte de um conjunto de funcionalidades de suporte ao cliente, agregando a busca por objetos perdidos. |
| RF36 | O aplicativo fornece uma área de contato sobre violência contra a mulher |  Responsabilidade | Depende de um subsistema específico para gerenciar informações e contatos relacionados a violência contra a mulher. |

</center>

<font size="2"><p style="text-align: center">Fonte: [Ricardo Augusto][RicardoGH], 2024.</p></font>

<font size="2"><p style="text-align: center">Tabela x - Elos dos requisitos não funcionais.</p></font>

<center>

| ID Requisito | Descrição | Tipo de Relacionamento | Descrição do relacionamento |
| --- | --- | --- | --- |
| RNF01 | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | Responsabilidade | Responsabilidade de implementar bloqueio após reporte de furto/roubo |
| RNF02 | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | Recurso | Utilização de tecnologia de atualização em tempo real |
| RNF03 | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código | Responsabilidade | Responsabilidade de identificar encomendas por QR Code rapidamente |
| RNF04 | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | Recurso | Dependência de sistemas de e-mail para identificação de encomendas |
| RNF05 | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt) | Representação | Representação de layout com elementos principais e texto legível |
| RNF06 | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega | Responsabilidade | Responsabilidade de envio de informações de rastreio por e-mail |
| RNF07 | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | Representação | Representação de código de rastreio simples e único |
| RNF08 | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | Responsabilidade | Responsabilidade de implementar e gerenciar sistema de chatbot |
| RNF09 | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | Responsabilidade | Responsabilidade de implementar tela de ajuda acessível e pop-up |
| RNF10 | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques | Representação | Representação de tutoriais interativos e informações claras |
| RNF11 | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status. | Responsabilidade | Responsabilidade de minimizar delay nas notificações |
| RNF12 | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | Recurso | Dependência de diretrizes WCAG 2.1 para acessibilidade |
| RNF13 | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | Recurso | Dependência de tecnologias para garantir tempo de resposta e taxa de falha |
| RNF14 | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão. | Recurso | Dependência de criptografia para dados de usuário |
| RNF15 | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas. | Recurso | Dependência de sistemas de rastreamento eficientes |
| RNF16 | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm. | Recurso | Dependência de capacidade de suporte para diferentes pesos e dimensões |
| RNF17 | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores. | Recurso | Dependência de sistema de autenticação de dois fatores |
| RNF18 | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros. | Recurso | Dependência de tecnologia de localização precisa |
| RNF19 | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas. | Recurso | Dependência de sistemas rápidos para cálculo de preços e prazos |
| RNF20 | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações. | Recurso | Dependência de protocolos HTTPS para segurança |
| RNF21 | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email. | Recurso | Dependência de autenticação segura para operações financeiras |
| RNF22 | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações. | Recurso | Dependência de sistemas rápidos para carregamento de mensagens |
| RNF23 | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação. | Recurso | Dependência de sistemas de autenticação para acesso seguro |
| RNF24 | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas. | Recurso | Dependência de sistemas rápidos para busca de objetos perdidos |
| RNF25 | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento. | Responsabilidade | Responsabilidade de atendimento rápido em casos de violência |
| RNF26 | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial. | Representação | Representação de interface de navegação eficiente |
| RNF27 | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior. | Recurso | Dependência de compatibilidade com versões específicas de sistemas operacionais |
| RNF28 | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status. | Responsabilidade | Responsabilidade de envio rápido de push notifications |
| RNF29 | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | Representação | Representação de opção de filtro de encomendas acessível |
| RFN30 | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância, para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | Representação | Representação de sistema de notificação redundante |
| RNF31 | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | Recurso | Dependência de sistemas precisos para rastreamento de encomendas |
| RNF32 | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | Satisfação | Satisfação do usuário com a aplicação |
| RNF33 | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | Representação | Representação de opção de rastreamento acessível |
| RNF34 | O chat com o entregador deve ser confiável (deve atender às especificações de segurança do Art. 46 da LGPD) | Responsabilidade | Responsabilidade de segurança no chat com o entregador |

</center>

<font size="2"><p style="text-align: center">Fonte: [Cláudio Henrique][ClaudioGH], 2024.</p></font>

## Bibliografia

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 20 de junho de 2024.

> 2. TORANZO, M.; CASTRO, J; MELLO, E. **Uma proposta para melhorar o rastreamento de requisitos**. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf>. Acesso em: 20 de junho de 2024.

## Referências Bibliograficas

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 21 de junho de 2024.

> 2. TORANZO, M.; CASTRO, J; MELLO, E. **Uma proposta para melhorar o rastreamento de requisitos**. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf>. Acesso em: 20 de junho de 2024.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 23/06/2024 | Criação do documento | [Cláudio Henrique](https://github.com/pabloheika), [Gabriel Fernando][GabrielFGH], [Ricardo Augusto][RicardoGH]  |   |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo

<Links das seções da análise documental>
[ADRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/#requisitos-funcionais
[ADRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/analise-documental/#requisitos-nao-funcionais

<Links das seções do brainstorm>
[BSRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/#requisitos-elicitados
[BSRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/#requisitos-elicitados

<Links das seções da observação>
[OBSRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/#requisitos-nao-funcionais-rnf
[OBSRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/#requisitos-funcionais-rf

<Links das seções do questionário>
[QRF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#funcionais
[QRNF]: https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#nao-funcionais
