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

| ID  | Descrição    | Código | Implementado | Versão |
| :-: | ------------ | :----: | :----------: |:----:|
| [BS01][BSRF] | O usuário deve poder realizar cadastro pelo app     | RF01   | Sim | `1.0` |
| [BS02][BSRF] | O usuário deve poder realizar login pelo app   | RF02   | Sim | `1.0` |
| [BS03][BSRF] | O usuário deve poder acessar o histórico de notificações do objeto  | RF03   | Não | `1.0` |
| [BS04][BSRF] | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo  | RF04   | Não | `1.0` |
| [BS05][BSRF] | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda  | RF05   | Não | `1.0` |
| [BS06][BSRF] | O usuário deve visualizar a estipulação de prazo de entrega  | RF06   | Sim | `1.0` |
| [BS07][BSRF] | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações	  | RF07   | Não | `1.0` |
| [BS08][BSRF] | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda| RF08   | Não | `1.0` |
| [BS09][BSRF] | O usuário deve receber notificações push pelo aplicativo		  | RF09   | Sim | `1.0` |
| [BS10][BSRF] | O usuário deve receber notificações SMS		  | RF10   | Sim | `1.0` |
| [BS11][BSRF] | O usuário deve receber notificações pelo Whatsapp		  | RF11   | Não | `1.0` |
| [BS12][BSRF] | O usuário deve ter acesso a um Chatbot para suporte ao cliente	| RF12   | Não | `1.0` |
| [BS13][BSRF] | O usuário deve poder visualizar um tutorial para realizar o rastreamento	  | RF13   | Não | `1.0` |
| [BS14][BSRF] | O usuário deve poder receber o status da encomenda pelo WhatsApp  | RF14   | Não |`1.1`|
| [BS15][BSRF] | O usuário deve poder aumentar e diminuir a fonte		  | RF15   | Não | `1.0` |
| [BS16][BSRF] | O usuário deve ter a opção de falar com um atendente para obter ajuda | RF16   | Não | `1.1` |
| [BS17][BSRF] | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes)  | RF17   | Não | `1.0` |
| [BS18][BSRF] | O usuário deve poder visualizar sua encomenda no mapa  | RF18   | Não | `1.0` |
| [BS19][BSRF] | O usuário deve poder visualizar detalhes da situação do produto	  | RF19   | Sim | `1.0` |
| [BS20][BSRF] | O usuário deve poder realizar o rastreio por código mais simples	  | RF20   | Não | `1.0` |
| [BS21][BSRF] | O usuário deve poder realizar o rastreio por QR Code	  | RF21   | Sim | `1.0` |
| [BS22][BSRF] | O usuário deve receber notificação pelo e-mail		  | RF22   | Não | `1.0` |
| [BS23][BSRF] | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo  | RF23   | Não | `1.0` |
| [BS24][BSRF] | O usuário deve poder realizar a simulação de envio com as informações do objeto | RF24   | Sim | `1.0` |
| [OBS01][OBSRF] | O aplicativo permite realizar login com sua conta | RF | Sim | `1.0` |
| [OBS02][OBSRF] | O aplicativo permite rastreamento de encomendas por código. | RF | Sim | `1.0` |
| [OBS03][OBSRF] | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | RF | Sim | `1.0` |
| [OBS04][OBSRF] | O aplicativo possibilite ver seus pagamentos | RF | Sim | `1.0` |
| [OBS05][OBSRF] | O aplicativo oferece uma busca por agências próximas ao seu endereço | RF | Sim | `1.0` |
| [OBS06][OBSRF] | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | RF | Sim | `1.0` |
| [OBS07][OBSRF] | O aplicativo possibilita a compra de certificados digitais dos correios | RF | Sim | `1.0` |
| [OBS08][OBSRF] | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | RF | Sim | `1.0` |
| [OBS09][OBSRF] | O aplicativo permite visualização de mensagens | RF | Sim | `1.0` |
| [OBS10][OBSRF] | O aplicativo oferece a visualização de vales postais | RF | Sim | `1.0` |
| [OBS11][OBSRF] | O aplicativo oferece uma área de busca por objetos perdidos em envios | RF | Sim | `1.0` |
| [OBS12][OBSRF] | O aplicativo fornece uma área de contato sobre violência contra a mulher | RF | Sim | `1.0` |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

### Requisitos Não-Funcionais

<font size="2"><p style="text-align: center">Tabela 1 - RFX.</p></font>

<Center>

| ID | Descrição | Tipo | Implementado | Versão |
| --- | --- | --- | --- | --- |
| [BS25][BSRNF] | O app deve bloquear todas as funções dentro de 5 minutos após ser reportado como furtado/roubado | RNF | Não | `2.0` |
| [BS26][BSRNF] | O app deve mostrar a localização da entrega com atualização em tempo real, com um atraso máximo de 10 segundos | RNF | Não | `2.0` |
| [BS27][BSRNF] | O app deve identificar encomendas através de QR Code em menos de 2 segundos após a leitura do código   | RNF | Sim |  `2.0` |
| [BS28][BSRNF] | O app deve identificar encomendas através de um e-mail enviado em até 5 segundos após a solicitação do usuário | RNF | Não | `2.0` |
| [BS29][BSRNF] | O app deve mostrar informações na Home com um layout que possua no máximo 3 elementos principais por seção e texto legível (tamanho mínimo de 14pt)| RNF | Não | `2.0` |
| [BS30][BSRNF] | O app deve enviar informações de rastreio por email dentro de 1 minuto após qualquer atualização no status da entrega| RNF | Não | `2.0` |
| [BS31][BSRNF] | O app deve gerar um código de rastreio único e simples, composto por no máximo 10 caracteres alfanuméricos | RNF | Não | `2.0` |
| [BS32][BSRNF] | O app deve possuir um sistema de chatbot com tempo de resposta inicial de no máximo 3 segundos e deve permitir redirecionamento a um atendente humano em no máximo 2 minutos | RNF | Não | `2.0` |
| [BS33][BSRNF] | O app deve ter uma tela de ajuda acessível a partir de qualquer tela em no máximo 2 cliques e um pop-up "Precisa de ajuda?" visível em todas as telas principais | RNF | Não | `2.0` |
| [BS34][BSRNF] | O app deve possuir tutoriais interativos com duração máxima de 3 minutos cada e/ou informações claras sobre como rastrear uma encomenda, acessíveis em no máximo 2 cliques  | RNF | Não | `2.0` |
| [BS35][BSRNF] | O app deve ter um delay nas notificações de entrega não superior a 10 segundos após qualquer atualização de status. | RNF | Não | `2.0` |
| [BS36][BSRNF] | O app deve estar em conformidade com as diretrizes WCAG 2.1, nível AA, para acessibilidade | RNF | Não | `2.0` |
| [BS37][BSRNF] | O app deve ter uma interface com tempo de resposta para qualquer interação do usuário não superior a 2 segundos e uma taxa de falha de operação inferior a 1% | RNF | Sim | `2.0` |
| [OBS13][OBSRNF] | O aplicativo deve criptografar todos os dados do usuário durante o armazenamento e transmissão. | RNF | Sim | `2.0` |
| [OBS14][OBSRNF] | O sistema de rastreamento de encomendas deve retornar o status da encomenda em menos de 5 segundos para 95% das consultas. | RNF | Sim | `2.0` |
| [OBS15][OBSRNF] | O sistema de envio de encomendas deve suportar o envio de objetos com pesos de 1 grama até 50 quilogramas e dimensões de até 200x200x200 cm. | RNF | Sim | `2.0` |
| [OBS16][OBSRNF] | O acesso aos pagamentos deve exigir autenticação do usuário utilizando um método de autenticação de dois fatores. | RNF | Não | `2.0` |
| [OBS17][OBSRNF] | A busca por agências deve retornar resultados baseados na localização do usuário com um raio de precisão de 200 metros. | RNF | Sim | `2.0` |
| [OBS18][OBSRNF] | O cálculo de preços e prazos de encomendas deve ser concluído em menos de 10 segundos para 95% das consultas. | RNF | Sim | `2.0` |
| [OBS19][OBSRNF] | A compra de certificados digitais deve utilizar protocolos HTTPS para todas as transações. | RNF | Sim | `2.0` |
| [OBS20][OBSRNF] | O acompanhamento da conta e recargas deve utilizar autenticação segura e confirmar a operação com um código enviado por SMS ou email. | RNF | Sim | `2.0` |
| [OBS21][OBSRNF] | A interface de visualização de mensagens deve carregar em menos de 5 segundos para 95% das operações. | RNF | Sim | `2.0` |
| [OBS22][OBSRNF] | A visualização de vales postais deve ser acessível apenas após autenticação do usuário com senha e um método adicional de autenticação. | RNF | Sim | `2.0` |
| [OBS23][OBSRNF] | A busca por objetos perdidos deve retornar resultados em menos de 5 segundos para 95% das consultas. | RNF | Sim | `2.0` |
| [OBS24][OBSRNF] | A área de contato sobre violência contra a mulher deve ter opção de chat ao vivo com tempo de resposta de menos de 10 minutos durante o horário de atendimento. | RNF | Sim | `2.0` |
| [OBS25][OBSRNF] | O aplicativo deve possuir uma interface que permita a navegação entre diferentes seções com no máximo 5 cliques a partir da tela inicial. | RNF | Sim | `2.0` |
| [OBS26][OBSRNF] | O aplicativo deve ser compatível com Android versão 8.0 ou superior e iOS versão 13.0 ou superior. | RNF | Sim | `2.0` |
| [OBS27][OBSRNF] | O aplicativo deve enviar notificações sobre o status da entrega via push notifications dentro de 30 minutos após a atualização do status. | RNF | Sim | `2.0` |
| [Q07][QRNF] | A opção de filtrar encomendas deve ser de fácil acesso (até 2 frames de ajuda a partir da página de encomendas) | RNF | Sim | 1.0 |
| [Q08][QRNF] | O aplicativo deve notificar o usuário com eficácia (deve haver um sistema de redundância,  para que a mesma notificação seja enviada por diferentes meios - SMS, email, Whatsapp e notificação pelo aplicativo -, de acordo com a preferência do usuário) | RFN | Não | 1.1 |
| [Q09][QRNF] | As informações sobre o rastreio de encomendas devem ser precisas (fornecem data, hora e local em cada atualização da encomenda) | RNF | Sim | 1.0 |
| [Q10][QRNF] | O usuário deve estar satisfeito com a aplicação (Caso seja solicitado, mais de 70% dos usuários devem atribuir uma nota igual ou maior que 3 - em uma escala de 1 a 5 - ao recomendar o aplicativo dos Correios a um amigo) | RNF | Não | 1.0 |
| [Q11][QRNF] | A opção de rastrear encomendas deve ser de fácil acesso (deve estar na página principal e o usuário não deve demorar mais de 2 minutos para achá-la) | RNF | Não | 1.0 |
| [Q12][QRNF] | O chat com o entregador deve ser confiável (deve atender às especificações de segurança do [Art. 46](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/#referencias-bibliograficas) da LGPD) | RNF | Não | 1.1 |

</Center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024.</p></font>

## Bibliografia

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 20 de junho de 2024.

> 2. TORANZO, M.; CASTRO, J; MELLO, E. **Uma proposta para melhorar o rastreamento de requisitos**. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf>. Acesso em: 20 de junho de 2024.

## Referências Bibliograficas

> 1. SAYÃO, Miriam; LEITE, Julio. **Rastreabilidade de Requisitos**. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 21 de junho de 2024.

> 2. TORANZO, M.; CASTRO, J; MELLO, E. **Uma proposta para melhorar o rastreamento de requisitos**. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf>. Acesso em: 20 de junho de 2024.

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
