# Análise Documental

## Introdução

A análise de documentos na elicitação de requisitos é uma técnica que envolve a revisão sistemática de documentação existente, tanto impressa quanto digital, identificando as necessidades de um projeto. Este método analítico requer a examinação e interpretação dos dados para derivar significados, compreensões e desenvolvimento de conhecimento empírico.

O processo começa com uma análise preliminar para selecionar os documentos mais relevantes. Entre os tipos de documentos comumente analisados estão: Documentação já existente do sistema; Documentos de outros projetos relacionados; Legislação aplicável; Editais; Planos de negócios; Contratos (Retraining Requirements Enginereeing, 2024).

## Metodologia

A partir da análise documental do projeto realizado pelo Grupo 03 da disciplina de Interação Humano-Computador, foram identificadas funcionalidades presentes no site dos correios (realizar uma pré-postagem, receber encomendas, gerenciar importações e busca por documentos perdidos) que ou estavam implementadas ou também poderiam ser implementadas no aplicativo, mas que passaram desapercebidas pelas técnicas de elicitação utilizadas até então ([Brainstorming](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/brainstorming/), [Observação](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/observacao/) e [Questionário](https://requisitos-de-software.github.io/2024.1-Correios/elicitacao/tecnicas/questionario/)), logo, elicitamos os requisitos relacionados às respectivas funcionalidades, seguindo a estrutura proposta por Vazquez et. al (2016), onde, presente na Tabela 01, temos uma pergunta que queremos responder, uma resposta à ela, o requisito proveniente dessa resposta, o ID desse requisito e o seu tipo. Ao final da página, também temos as tabelas 6 e 7 que, respectivamente, agrupam os requisitos funcionais e não-funcionais elicitados.

## Requisitos Elicitados

Legenda para as tabelas:

- RF: Requisito Funcional
- RNF: Requisito Não-Funcional
- ADxx: Requisito nºx elicitado pelo questionário.

<center>

<font size="2"><p><b>Tabela 1</b> - Modelo de estrutura. </p></font>

| Pergunta | Respondida | Requisito elicitado | ID | Código |
| - | - | - | - | - |
| Pergunta levantada para o requisito. | A pergunta foi respondida? Sim/Não | Expecificação do requisito. | Identificação do requisito. | Tipo do requisito. |

<font size="2"><p style="text-align: center">Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi) e [Pablo S. Costa][PabloGH], 2024 </p></font>

</center>

### Recebimento de encomendas

Abaixo, na tabela 2, está os requisitos elicitados para  o Recebimento de encomendas.

<center>

<font size="2"><p><b>Tabela 2</b> - Requisitos elicitados para o Recebimento de encomendas. </p></font>

| Pergunta | Respondida | Requisito elicitado | ID | Código |
|--|--|--|--|--|
| Qual a importância da funcionalidade em questão? | Sim | O usuário deve conseguir mudar a opção de recebimento dentro do aplicativo, antes da sua encomenda for enviada. | AD01 |  |
| Essa funcionalidade tem opções dentro dela? | Sim | O usuário deve poder escolher o método de recebimento em até 3 cliques desde iniciar a ação. | AD02 |  |
| O usuário é avisado quando a entrega é realizada? | Sim | O usuário deve ser notificado quando o recebimeto for efetuado. | AD03 |  |
| A opção de locker é útil? | Sim | O sistema deve permitir que o usuário reserve o locker mais perto de sua casa baseado no CEP informado, de acordo com a disponibilidade | AD04 |  |
| É possível mudar o endereço de entrega de uma encomenda? | Sim | O usuário deve poder mudar  local de de rebimento da encomenda | AD05 |  |
| Existem outras opções sem ser residencial ou locker | Sim | O usuário pode optar por retirar em uma agência ou caixa postal | AD06 |  |
| O tempo de resposta nessa área é bom? | Não |   |   |   |
| Essa funcionalidade já existe no site, sua interface é útil? | Sim | A interface deve ser intuitiva para fácil realização do procedimento. | AD07 |   |
| É simples achar essa funcionalidade no site? | Sim | A funcionalidade deve ser de fácil acesso, pela página principal. | AD08 |   |

<font size="2"><p style="text-align: center">Fonte: [Gabriel B. Bertolazi](https://github.com/Bertolazi), 2024 </p></font>

</center>

### Realizar uma pré-postagem

Na tabela 3 está os requisitos elicitados para a funcionalidade de Pré-postagem.

<center>
<font size="2"><p>
    <b>Tabela 3</b> - Requisitos elicitados para realizar uma pré-postagem.
</p></font>

| Pergunta| Respondida | Requisito elicitado | ID | Código |
|--|--|--|--|--|
| O usuário é capaz de realizar, no aplicativo, a funcionalidade presente no site?  | Sim | O usuário deve ser capaz de realizar uma pré-postagem pelo aplicativo | AD09 | RF |
| O usuário possui mais de um meio de pagamento para a pré-postagem?  | Não | O usuário poderá pagar uma pré-postagem com cartão de crédito, boleto ou pix | AD10 | RF |
| O usuário é capaz de escolher endereços pré-cadastrados para os campoos de remetente e destinatário? | Não | O usuário deve ser capaz de adicionar endereços pré-cadastrados ao preencher uma pré-postagem | AD11 | RF |
| O aplicativo protege o usuário em operações criticas como exclusão de itens?  | Sim | O usuário deve ser perguntado sobre a confirmação de operações críticas | AD12 | RNF |
| O aplicativo agiliza o processo de realizar pagamento com cartão de crédito?  | Sim | O usuário pode escolher salvar as informações do cartão de crédito para pagamentos futuros | AD13 | RF |

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

</center>

### Busca por documentos perdidos

Na tabela 4 está os requisitos elicitados para a funcionalidade de Busca por documentos perdidos.

<center>

<font size="2"><p><b>Tabela 4</b> - Requisitos elicitados para a Busca por documentos perdidos. </p></font>

| Pergunta | Respondida | Requisito elicitado | ID | Código |
|--|--|--|--|--|
| O aplicativo fornece algum meio de localização de documentos perdidos? | Não | O usuário deve ser capaz de consultar uma seção de achados e perdidos para encontrar documentos | AD14 | RF |

<font size="2"><p style="text-align: center">Fonte: [Danilo Carvalho][DaniloGH], 2024 </p></font>

</center>

### Minhas importações

Na tabela 5 está os requisitos elicitados para a funcionalidade de Minhas Importações.

<center>

<font size="2"><p><b>Tabela 5</b> - Requisitos elicitados para o Minhas Importações. </p></font>

| Pergunta | Respondida | Requisito elicitado | ID | Código |
|----------|------------|---------------------|----|--------|
| Como o usuário deseja organizar suas importações no sistema? Quais informações específicas o usuário precisa rastrear para cada importação? | Sim | O Usuário deve ser capaz de gerenciar suas importações? | AD15 | RF |
| Quais tipos de problemas ou questões alfandegárias o usuário pode encontrar? Como o usuário espera resolver essas situações? | Sim | O Usuário deve ser capaz de resolver situações alfandegárias | AD16 | RF |
| O usuário deseja visualizar um histórico completo de todas as situações anteriores? Quais detalhes específicos o usuário gostaria de ver no histórico? | Sim | O usuário deve ser capaz de visualizar histórico de situações alfandegárias | AD17 | RF |
| Como o usuário pretende adicionar novas importações ao sistema? Quais campos ou informações são essenciais para cada nova importação? | Sim | O usuário deve ser capaz de inserir novas importações | AD18 | RF |
| Quais métodos de pagamento o usuário espera encontrar no aplicativo? O usuário precisa de informações detalhadas sobre como efetuar os pagamentos? | Sim | O usuário deve ter acesso a meios de pagamento de taxas | AD19 | RF |
| Como o usuário deseja ser notificado sobre mudanças em suas importações? Quais eventos específicos devem acionar uma notificação? | Sim | O usuário deve ser notificado sobre atualizações de importações | AD20 | RF |
| Quais procedimentos o usuário gostaria de seguir para contestar taxas? Quais documentos ou evidências o usuário pode fornecer durante o processo de contestação? | Sim | O usuário deve poder contestar taxas e tributações | AD21 | RF |
| Como deve ser a comprovação da situação da encomenda? | Sim | O Usuário deve ser capaz de emitir comprovante | AD22 | RF |
| O usuário precisa de comprovantes impressos ou digitais? Quais informações devem constar nos comprovantes? | Sim | O usuário deve ser capaz de emitir DIS | AD23 | RF |
| O usuário precisa de prontidão nas informações alfandegarias? | Sim | As informações devem ser atualizadas em tempo de execução | AD24 | RNF |
| Quanto tempo leva para receber uma importação? | Sim | A liberação das encomendas deve ser automática | AD25 | RNF |
| As encomendas costumam ter o documento pessoal ou empresarial? | Sim | Sempre que presente o documento destinatário na encomenda, as importações devem ser inseridas automaticamente | AD26 | RNF |


<font size="2"><p style="text-align: center">Fonte: [Pablo S. Costa][PabloGH], 2024 </p></font>

</center>

### Minhas importações

Na tabela 6 estão os requisitos elicitados para a funcionalidade da loja online dos correios.

<center>

<font size="2"><p><b>Tabela 6</b> - Requisitos elicitados para a loja online. </p></font>

| Pergunta | Respondida | Requisito elicitado | ID | Código |
|----------|------------|---------------------|----|--------|
||||||


<font size="2"><p style="text-align: center">Fonte: [Elias F. Oliveira][EliasGH], 2024 </p></font>

</center>

### Requisitos Funcionais

Na tabela 8, está especificado os Requisitos Funcionais e se estão implementados no aplicativo.

<center>

<font size="2"><p> **Tabela 8** - Requisitos Funcionais elicitados. </p></font>


### Requisitos Funcionais

Na tabela 8, está especificado os Requisitos Funcionais e se estão implementados no aplicativo.

<center>

<font size="2"><p> **Tabela 8** - Requisitos Funcionais elicitados. </p></font>

| ID | Descrição    | Código | Implementado |
| -------------- | --------------- | :------: | :------: |
| AD01 | O usuário deve poder escolher a opção de recebimento dentro do aplicativo antes de sua encomenda ser enviada. | RF | Não |
| AD02 | O usuário deve escolher o método de recebimento em até 3 cliques desde iniciar a ação. | RF | Não |
| AD03 | O sistema deve permitir que o usuário reserve o locker mais próximo de sua casa com base no CEP informado, de acordo com a disponibilidade. | RF | Não |
| AD04 | O usuário deve ser notificado quando o recebimento for efetuado. | RF | Não |
| AD05 | O usuário deve poder mudar local de de rebimento da encomenda | RF | Não |
| AD06 | O usuário pode optar por retirar em uma agência ou caixa postal | RF | Não |
| AD09 | O usuário deve ser capaz de realizar uma pré-postagem pelo aplicativo | RF |  Sim|
| AD10 | O usuário poderá pagar uma pré-postagem com cartão de crédito, boleto ou pix | RF |  Não|
| AD11 | O usuário deve ser capaz de adicionar endereços pré-cadastrados ao preencher uma pré-postagem | RF | Não |
| AD12 | O usuário deve ser perguntado sobre a confirmação de operações críticas | RNF | Sim |
| AD13 | O usuário pode escolher salvar as informações do cartão de crédito para pagamentos futuros | RF |  Sim|
| AD14 | O usuário deve ser capaz de consultar uma seção de achados e perdidos para encontrar documentos | RF | Não|
| AD15 | O Usuário deve ser capaz de gerenciar suas importações | RF | Sim |
| AD16 | O Usuário deve ser capaz de resolver situações alfandegárias | RF | sim |
| AD17 | O usuário deve ser capaz de visualizar histórico de situações alfandegárias | RF | Sim |
| AD18 | O usuário deve ser capaz de inserir novas importações | RF | Sim |
| AD19 | O usuário deve ter acesso a meios de pagamento de taxas | RF | Sim |
| AD20 | O usuário deve ser notificado sobre atualizações de importações | RF | Sim |
| AD21 | O usuário deve poder contestar taxas e tributações | RF | Sim |
| AD22 | O Usuário deve ser capaz de emitir comprovante | RF | Sim |
| AD23 | O usuário deve ser capaz de emitir DIS | RF | Sim |


</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

### Requisitos Não-Funcionais

Abaixo, na tabela 8, está especificado os Requisitos Não-funcionais e se estão implementados ou não.

<center>

<font size="2"><p> **Tabela 8** - Requisitos Não-Funcionais elicitados. </p></font>

| ID | Descrição    | Código | Implementado |
| -------------- | --------------- | :------: | :------: |
| AD07 | A interface deve ser intuitiva para fácil realização do procedimento. | RNF38 | Não | 
| AD08 | A funcionalidade deve ser de fácil acesso pela página principal | RNF37 | Não |
| AD24 | As informações devem ser atualizadas em tempo de execução | RNF | Sim |
| AD25 | A liberação das encomendas deve ser automática | RNF | Sim |
| AD26 | Sempre que presente o documento destinatário na encomenda, as importações devem ser inseridas automaticamente | RNF | Sim |

</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel F. J. Silva](https://github.com/MMcLovin), 2024 </p></font>

## Referências
> 1. Retraining Requirements Enginereeing. Análise de Documentos, 2024. Disponível em: https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos. Acesso em: 20 de maio de 2024.
> 2. Vazquez, Carlos. Simões, Guilherme. Engenharia de Requisitos. Brasport, 2016. Disponível em: .Acesso em: 20 de maio de 2024

## Bibliografia

> 1. GitHub. Disponível em: [https://docs.github.com/pt](https://docs.github.com/pt). Acesso em: 20 de Maio de 2024.
>
> 2. Microsoft Teams. Disponível em: [https://www.microsoft.com/pt-br/microsoft-teams/group-chat-software](https://www.microsoft.com/pt-br/microsoft-teams/group-chat-software). Acesso em: 20 de Maio de 2024.
>
> 3. Grupo 03 de Interação Humano-Computador 2024.1. Projeto do site Correios. Disponível em : [Correios IHC](https://github.com/Interacao-Humano-Computador/2024.1-Correios). Acesso em: 20 de Maio de 2024
>
> 4. Retraining Requirements Enginereeing. Análise de Documentos, 2024. Disponível em: [URL](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos). Acesso em: 20 de maio de 2024.
>
> 5. Vazquez, Carlos. Simões, Guilherme. Engenharia de Requisitos. Brasport, 2016. Disponível em: .Acesso em: 20 de maio de 2024

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 20/05/2024 | Criação do documento | [Gabriel B. Bertolazi][GabrielBGH], [Gabriel F. J. Silva][GabrielFGH] e [Pablo S. Costa][PabloGH]  | [Claudio Henrique](ClaudioGH)  |


[ClaudioGH]: https://github.com/claudiohsc
[DaniloGH]: https://github.com/Danilo-Carvalho-Antunes
[EliasGH]: https://github.com/EliasOliver21
[GabrielBGH]: https://github.com/Bertolazi
[GabrielFGH]: https://github.com/MMcLovin
[PabloGH]: https://github.com/pabloheika
[RicardoGH]: https://www.github.com/avmricardo
