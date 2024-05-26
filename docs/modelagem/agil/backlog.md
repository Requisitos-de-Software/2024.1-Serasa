# Backlogs

## Introdução

A metodologia ágil é uma abordagem flexível de gestão de projetos que foca na colaboração, adaptação e entrega contínua de valor ao cliente. Dentro dessa metodologia, o Product Backlog é fundamental, pois é uma lista priorizada de requisitos, funcionalidades e tarefas a serem executadas no projeto ou produto. Ele destaca a divisão de grandes tarefas em temas, épicos e histórias do usuário.

## Metodologia

A metodologia utilizada para a definição do Backlog da nossa equipe tira como base os [requisitos elicitados](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/requisitos_elicitados/), e por meio desses, é possível agrupar e dividir os requisitos em 3 grupos: [Temas](#temas), [Épicos](#épicos) e [Histórias do Usuário](). Os Temas são os conjuntos de épicos que se relacionam de alguma forma, já os Épicos são grandes partes de trabalho, e que por sua vez também são divididos em tarefas menores, que são as Histórias de Usuário.

A partir dessa divisão, na tabela 1, é possível ver os temas, épicos, histórias de usuário e a prioridade de cada história de usuário.

#### **Temas**

* **Tema 1:** Rastreamento e Envio de Encomendas
* **Tema 2:** Notificações e Alertas
* **Tema 3:** Suporte e Ajuda ao Usuário
* **Tema 4:** Serviços de Pagamento e Importação
* **Tema 5:** Busca e Contato

#### **Épicos**

**EP01 - Rastreamento no Mapa**
* Eu, como usuário, gostaria de rastrear minhas encomendas em tempo real no mapa para saber exatamente onde elas estão e quando chegarão.
* Eu, como usuário, gostaria de receber informações detalhadas sobre o status da minha encomenda, incluindo datas de envio, previsão de entrega e histórico de movimentação.

**EP02 - Informações de Entrega**
* Eu, como usuário, gostaria de acessar informações detalhadas sobre minhas entregas, incluindo o endereço de entrega, o nome do destinatário, e a confirmação de entrega com assinatura digital.
* Eu, como usuário, gostaria de ter a opção de reprogramar a entrega ou alterar o endereço de entrega em caso de imprevistos.

**EP03 - Ajuda ao Usuário**
* Eu, como usuário, gostaria de acessar um centro de ajuda com tutoriais e FAQs para resolver problemas comuns de forma rápida e eficiente.
* Eu, como usuário, gostaria de ter acesso a um chat de suporte ao vivo para resolver dúvidas e problemas em tempo real.

**EP04 - Pagamento e Importação**
* Eu, como usuário, gostaria de realizar pagamentos de taxas de importação diretamente pelo aplicativo para facilitar o processo de liberação de encomendas internacionais.
* Eu, como usuário, gostaria de acessar um histórico de pagamentos e importações para acompanhar todas as transações feitas através do aplicativo.

**EP05 - Busca e Contato**
* Eu, como usuário, gostaria de buscar informações sobre agências próximas, horários de funcionamento e serviços oferecidos para planejar visitas e envios.
* Eu, como usuário, gostaria de ter acesso rápido aos contatos do serviço de atendimento ao cliente para reportar problemas ou fazer perguntas diretamente aos Correios.

### Modelo da tabela:
<p align="center" > <strong> Tabela 1 - </Strong>Modelo do backlog</font> <gitbr></p>

|Épico|Tema|Histórias de Usuário|ID História de usuário|Prioridade|Rastreabilidade|
|:--|:--|:--|:--|:--|:--|
|Código do Épico|nome do tema|Descrição da História de Usuário|identificador da História de Usuário|Prioriade baseada na técnica do three level scale|Código do requisito referente a História de usuário|

<font size="3"><p style="text-align: center">Fonte: [Danilo Carvalho Antunes](https://github.com/Danilo-Carvalho-Antunes), 2024</p></font>

## Backlog

<p align="center" > <strong> Tabela 2 - </Strong>Backlog</font> <gitbr></p>

|Épico|Tema|Histórias de Usuário|ID História de Usuário|Prioridade|Rastreabilidade|
|:--|:--|:--|:--|:--|:--|
|EP01|Rastreamento e Envio de Encomendas|Como usuário, eu quero rastrear minhas encomendas em tempo real no mapa para saber exatamente onde elas estão e quando chegarão.|US01|Alta|RF18|
|EP01|Rastreamento e Envio de Encomendas|Como usuário, eu quero receber informações detalhadas sobre o status da minha encomenda, incluindo datas de envio, previsão de entrega e histórico de movimentação.|US02|Alta|RF19|
|EP02|Notificações e Alertas|Como usuário, eu quero receber notificações push pelo aplicativo para ser informado sobre atualizações da minha encomenda.|US03|Média|RF09|
|EP02|Notificações e Alertas|Como usuário, eu quero receber notificações por SMS para ser informado sobre atualizações da minha encomenda.|US04|Média|RF10|
|EP02|Notificações e Alertas|Como usuário, eu quero receber notificações pelo WhatsApp para ser informado sobre atualizações da minha encomenda.|US05|Baixa|RF11|
|EP02|Notificações e Alertas|Como usuário, eu quero receber notificações por e-mail para ser informado sobre atualizações da minha encomenda.|US06|Baixa|RF22|
|EP03|Suporte e Ajuda ao Usuário|Como usuário, eu quero acessar um centro de ajuda com tutoriais e FAQs para resolver problemas comuns de forma rápida e eficiente.|US07|Média|RF13|
|EP03|Suporte e Ajuda ao Usuário|Como usuário, eu quero ter acesso a um chat de suporte ao vivo para resolver dúvidas e problemas em tempo real.|US08|Alta|RF12|
|EP04|Serviços de Pagamento e Importação|Como usuário, eu quero realizar pagamentos de taxas de importação diretamente pelo aplicativo para facilitar o processo de liberação de encomendas internacionais.|US09|Alta|RF23|
|EP04|Serviços de Pagamento e Importação|Como usuário, eu quero acessar um histórico de pagamentos e importações para acompanhar todas as transações feitas através do aplicativo.|US10|Média|RF24|
|EP05|Busca e Contato|Como usuário, eu quero buscar informações sobre agências próximas, horários de funcionamento e serviços oferecidos para planejar visitas e envios.|US11|Média|RF29|
|EP05|Busca e Contato|Como usuário, eu quero ter acesso rápido aos contatos do serviço de atendimento ao cliente para reportar problemas ou fazer perguntas diretamente aos Correios.|US12|Alta|RF36|

<font size="3"><p style="text-align: center">Fonte: [Danilo Carvalho Antunes](https://github.com/Danilo-Carvalho-Antunes), 2024</p></font>

## Bibliografia

> Economia-DF. Backlog. Grupo Economia-DF da disciplina Requisitos de Software, dispoível em: <https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/>. Acesso em: 24 de maio de 2024.
>
> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 015): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2024. Disponível em: https://aprender3.unb.br/pluginfile.php/2845040/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf Acesso em: 24/05/2024.

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 25/05/2024 | Criação do documento | [Claudio Henrique][ClaudioGH] & [Danilo Carvalho][DaniloGH]|  |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
