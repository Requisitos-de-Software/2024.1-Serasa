## Introdução

O termo Brainstorming, traduzido do inglês significa "Chuva de ideias", e na elicitação de requisitos podemos realizar um brainstorming das necessidades e desejos do usuário, com os participantes alçando ideias e opniões de maneira livre entorno de um tema que é colocado.É possível utilizar esta técnica em qualquer tipo de serviço ou produto, tendo como objetivo catalogar quais aspectos e ações os usuários anseiam que o aplicativo possua.Essa técnica é utilizada dessa forma e normalmente apresenta mais resultados quando executada na fase de conceituação do desenvolvimento do aplicativo.


## Metodologia

Os participantes se reuniram de maneira remota através da plataforma Teams e Google Meet, documentando toda a reunião contendo os temas colocados, respostas dos participantes. Escolhemos um membro da equipe para ser o moderador da conversa mantendo o foco e consistência da reunião centrado no nosso objetivo.


## Participantes


<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome | Função | 
|:-----:|:--------:|
| [Claudio Henrique](https://github.com/claudiohsc)|Moderador |
| [Elias F. Oliveira](https://github.com/EliasOliver21) |Secretário|
| Henrique Camelo Quenino |Usuário|
| Renato Medeiros |Usuário|


</center>


<font size="3"><p style="text-align: center">Fonte: [Elias F. Oliveira](https://github.com/EliasOliver21), 2024.</p></font>


## Perguntas/Respostas

#### Quais são as funcionalidades que você considera essenciais em um aplicativo de entregas, como o Correios?

<span style = "color: yellow"> Henrique </span>- Possua um feedback constante do produto, mais detalhes da situação do objeto. Que eu seja informado caso ocorra adiamento de entrega, e que o usuário possa contactar a empresa responsável pela venda;

<span style = "color: yellow"> Renato </span>- Facilidade para o usuário em apresentar as informações de maneira simples, rastreio completo, segurança do aplicativo no caso do equipamento ser furtado, nesse caso acontecer um bloqueio das funções.

#### Qual a melhor forma de rastrear uma encomenda dentro de um app de entregas?
<span style = "color: yellow"> Henrique </span>- A melhor forma é que a pessoa mesmo preencha as informações no aplicativo, e que o produto tenha chip de localização que forneça informações constantes;

<span style = "color: yellow"> Renato </span>- A melhor forma seria utilizando funcionalidades aliadas as tecnologias atuais como Whatsapp bots, avisos direto no Whatsapp. O uso de QR code também é interessante, assim como visualizar as informações inserindo somente o e-mail no aplicativo.


#### Relacionado com as entregas, que tipo de informações você gostaria de ver sobre elas no aplicativo?

<span style = "color: yellow"> Henrique </span>- Um prazo previsto de entrega, caso varie que seja reformulado a tempo de poder receber a encomenda;

<span style = "color: yellow"> Renato </span>- Prazo o mais atualizado possível. Rastreio em tempo real ou notificações periódicas.


#### Como os usuários podem acessar as suas entregas/objetos dentro do app?

<span style = "color: yellow"> Henrique </span>- Poderiam estar logo de cara na parte inicial do aplicativo, sem competir com outras informações;

<span style = "color: yellow"> Renato </span>- Uma lista de rastreio dos objetos sendo mostrado em redes como Whatsapp ou e-mail.

#### Que sugestões você tem para tornar o aplicativo do Correios mais intuitivo, com um design amigável e uma navegação mais simples, que geraria uma navegação agradável?

<span style = "color: yellow"> Henrique </span>- A própria parte do rastreio dos objetos, em vez de estar no menu poderia estar home(inicio) do aplicativo. Aba para contatos.
Rastreio pelo código ser mais simplificado, possuir um design mais intuitivo para busca;

<span style = "color: yellow"> Renato </span>- Opção de aumento da fonte, mais responsividade dos ícones, Chatbot para auxiliar o usuário, e opção para redirecionar para um atendente real para auxiliar o usuário.


#### Como o aplicativo pode te notificar sobre o status da sua entrega? Explique a melhor forma.

<span style = "color: yellow"> Henrique </span>- Notificação(Push) do aplicativo eficiente ou por mensagem SMS pelo número de telefone.

<span style = "color: yellow"> Renato </span>- Notificações Push do aplicativo atualizada corretamente. Notificar pelo email e também Whatsapp.



#### Qual seria a forma ideal do aplicativo fornecer suporte ao cliente?

<span style = "color: yellow"> Henrique </span>- Chat bot e uma opção de conversar com atendente para ser respondido naquele exato momento.

<span style = "color: yellow"> Renato </span>- Tela de ajuda e um pop-up de "Precisa de Ajuda??", incluindo um Chat bot que auxilie também no processo.


#### Quais são as principais reclamações ou desafios que vocês enfrentariam utilizando o app, e como podemos resolvê-los?

<span style = "color: yellow"> Henrique </span>- Não possui tutorial para realizar o rastreio de forma fácil, o que poderia ser resolvido com simples pop-ups na tela indicando os locais.

A página de acompanhamento não é intuitiva, e poderia ser melhor organizada diminuindo a quantidade de informações na tela.

Atualização ineficaz das etapas do objeto até a minha casa, onde poderiam diminuir esse delay de atualizações ou apresentar um acompanhamento em tempo real.

<span style = "color: yellow"> Renato </span>- Opção de suporte escondida no aplicativo, dificultando o acesso, onde ela também é mal documentada.
Usabilidade mediana e confusa.
Falta de clareza nas informações.
Falta de acessibilidade (Aumentar e diminuir fonte).

Poderiam ser corrigidas implementando um bom suporte por chats ou pop-ups, corrigindo o design para uma opção mais limpa e intuitiva, melhorar a acessibilidade em geral do app.

## Requisitos Elicitados

Legenda Requisitos das tabelas:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- BSx: Requisito nºx elicitado pelo Brainstorming.

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

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



</center>

<font size="3"><p style="text-align: center">Fonte: [Elias F. Oliveira](https://github.com/EliasOliver21) e [Claudio Henrique](https://github.com/claudiohsc) </p></font>

<!-- ****************************        Tabela 2        ****************************** -->

<font size="3"><p style="text-align: center">Tabela 3 : Requisitos não funcionais.</p></font>

<center>

| ID | Descrição    | Código | Implementado |
| -------------- | --------------- | :------: | :------: |
| BS22 | Requisito      | RNF22  | Sim |

</center>

<font size="3"><p style="text-align: center">Fonte: [Elias F. Oliveira](https://github.com/EliasOliver21) e [Claudio Henrique](https://github.com/claudiohsc) </p></font>


## Bibliografia

>1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

>2. 2023.1-BilheteriaDigital.
    Disponível em :  <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/>

## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :----: | :--: | --------- | ----------- | ------ |
| `1.0`  | 15/04/2024 | Criação do documento | [Elias F. Oliveira](https://github.com/EliasOliver21) | [Ricardo Augusto](https://www.github.com/avmricardo)  |
| `1.1`  | 15/04/2024 | Preenchimento de requisitos | [Elias F. Oliveira](https://github.com/EliasOliver21) | [Revisor](https://www.github.com/)  |