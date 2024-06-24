## Introdução

A rastreabilidade é a técnica utilizada para apresentar o relacionamento entre os requisitos, arquitetura e implementação final do sistema, em suma a rastreabilidade conta a história do requisito desde sua fonte na fase de elicitação até a implementação final e o gerenciamento na pre e  pós-rastreabilidade. A rastreabilidade nos ajuda a entender e compreender melhor os relacionamentos já existentes entre os requisitos ou artefatos de requisitos, arquitetura e implementação. A pós-rastreabilidade liga os requisitos ao desenho e implementação do sistema.A rastreabilidade forward-from conecta os requisitos a artefatos de desenho e implementação.

## Metodologia

O método utilizado para fazer o gerenciamento dos requisitos será utilizando o meta-modelo de Toranzo, onde ele elenca quatro níveis de classificação que são:

- Ambiental
- Organizacional
- Gerencial
- Desenvolvimento

Será utilizada somente a classificação a nível de desenvolvimento, visto que estamos realizando um projeto para a disciplina de Requisitos de software analisando um aplicativo, então será utilizado somente teremos como base de informações os artefatos produzidos pelo grupo para a estruturação dos requisitos e suas relações com o material analisado. Será utilizado como descrito por Toranzo a criação de elos que irão interligar os requisitos aos artefatos criados pelo grupo. Abaixo temos a classificação dos tipos de elos elencados por Toranzo:

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
    - Casos de uso - CU
    - Tema - TM
    - Épico - EP
    - Histórias de Usuário - HU
    - NFR Framework - NFR

## Requisitos Funcionais

Na tabela 01 abaixo temos os requisiitos funcionais elicitados e suas ligações com os artefatos que foram produzidos na fase de desenvolvimento.

<font size="2"><p style="text-align: center">Tabela 01 : Requisitos Funcionais </p></font>
<center>

Requisito | Descrição | Implementado | Persona | Cenário | Léxico | Caso de Uso | Tema | Épico | História de Usuário | NFR Framework|
|  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |  :---:  |
| INT01 | O usuário deve poder realizar cadastro pelo app | Sim | | | | | | | | |
| INT02 | O usuário deve poder realizar login pelo app | Sim | | | | | | | | |
| INT03 | O usuário deve poder acessar o histórico de notificações do objeto | Não | | | | | | | | |
| INT04 | O usuário deve poder ativar bloqueio do aplicativo em caso de furto do dispositivo | Não | | | | | | | | |
| INT05 | O usuário deve ter a opção de utilização de chip de localização para rastreamento da encomenda | Não | | | | | | | | |
| INT06 | O usuário deve visualizar a estipulação de prazo de entrega | Sim | | | | | | | | |
| INT07 | O usuário deve visualizar a atualização do prazo de entrega caso ocorram variações | Não | | | | | | | | |
| INT08 | O usuário deve ter acesso a uma aba para contatos das empresas que postaram a encomenda | Não | | | | | | | | |
| INT09 | O usuário deve receber notificações push pelo aplicativo | Sim | | | | | | | | |
| INT10 | O usuário deve receber notificações SMS | Sim | | | | | | | | |
| INT11 | O usuário deve receber notificações pelo Whatsapp | Não | | | | | | | | |
| INT12 | O usuário deve ter acesso a um Chatbot para suporte ao cliente | Não | | | | | | | | |
| INT13 | O usuário deve poder visualizar um tutorial para realizar o rastreamento | Não | | | | | | | | |
| INT14 | O usuário deve poder receber o status da encomenda pelo WhatsApp | Não | | | | | | | | |
| INT15 | O usuário deve poder aumentar e diminuir a fonte | Não | | | | | | | | |
| INT16 | O usuário deve ter a opção de falar com um atendente para obter ajuda | Não | | | | | | | | |
| INT17 | O usuário deve ter acesso a uma página de FAQ (Perguntas Frequentes) | Não | | | | | | | | |
| INT18 | O usuário deve poder visualizar sua encomenda no mapa | Não | | | | | | | | |
| INT19 | O usuário deve poder visualizar detalhes da situação do produto | Sim | | | | | | | | |
| INT20 | O usuário deve poder realizar o rastreio por código mais simples | Não | | | | | | | | |
| INT21 | O usuário deve poder realizar o rastreio por QR Code | Sim | | | | | | | | |
| INT22 | O usuário deve receber notificação pelo e-mail | Não | | | | | | | | |
| INT23 | O usuário deve poder realizar o pagamento de impostos/taxas de importação pelo aplicativo | Não | | | | | | | | |
| INT24 | O usuário deve poder realizar a simulação de envio com as informações do objeto | Sim | | | | | | | | |
| INT25 | O aplicativo permite realizar login com sua conta | Sim | | | | | | | | |
| INT26 | O aplicativo permite rastreamento de encomendas por código. | Sim | | | | | | | | |
| INT27 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | Sim | | | | | | | | |
| INT28 | O aplicativo possibilite ver seus pagamentos | Sim | | | | | | | | |
| INT29 | O aplicativo oferece uma busca por agências próximas ao seu endereço | Sim | | | | | | | | |
| INT30 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | Sim | | | | | | | | |
| INT31 | O aplicativo possibilita a compra de certificados digitais dos correios | Sim | | | | | | | | |
| INT32 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | Sim | | | | | | | | |
| INT33 | O aplicativo permite visualização de mensagens | Sim | | | | | | | | |
| INT34 | O aplicativo oferece a visualização de vales postais | Sim | | | | | | | | |
| INT35 | O aplicativo oferece uma área de busca por objetos perdidos em envios | Sim | | | | | | | | |
| INT36 | O aplicativo fornece uma área de contato sobre violência contra a mulher | Sim | | | | | | | | |

</center>
<font size="2"><p style="text-align: center"> Fonte: [Elias F. Oliveira][EliasGH]</p></font>


## Requisitos Não-Funcionais

## Bibliografia

> 1. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 23 de jun de 2024.

## Histórico de versões
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0`| 23/06/2024 | Criação do Documento | [Elias Oliveira](https://github.com/EliasOliver21) e [Claudio Henrique](https://github.com/claudiohsc) |  |

[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
