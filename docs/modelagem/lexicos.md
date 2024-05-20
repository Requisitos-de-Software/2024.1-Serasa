## Introdução

O léxico é uma notação utilizada para apresentar os símbolos de uma linguagem através da descrição de termos, o principal uso dos léxicos na engenharia de requisitos é encontrar palavras ou frases que são peculiares no meio social do estudo em questão. Nos léxicos cada símbolo é caracterizado com noção e impacto, onde noção denota o significado do símbolo, já o impacto representa: o efeito, uso ou ocorrência do símbolo no sistema ou ainda o efeito de algo na aplicação sobre o símbolo.

## Metodologia

Tendo como base os [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) na etapa anterior identificamos e apresentamos os devidos léxicos separando em três tipos de classificação que são: Objeto, Verbo e Estado que são descritos logo abaixo. Na tabela 01 é mostrado o formato ao qual os léxicos estão estruturados, para a criação dos léxicos utilizamos o LAL (Léxico Ampliado da Imagem) que é uma maneira mais refinada de registro de termos próprios da aplicação.

<font size="3"><p style="text-align: center">**Tabela 01 - Formato do Léxico** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
|LXX - Nome. |Objeto, Verbo, Estado.|Significado do símbolo.|Efeito, uso ou ocorrência na aplicação.|Termo similar.|Integrante responsável pelo léxico.|

<center>**Fonte**:  [Elias Oliveira](https://github.com/EliasOliver21) e [Claudio Henrique](https://github.com/claudiohsc), 2024. </center>



## Objeto

Nos léxicos do tipo Objeto é definido: o objeto, outros objetos com os quais se relaciona e as ações que poderão ser empregadas ao objeto. Na tabela 02 logo abaixo estão descritos os léxicos do tipo objeto.

<font size="3"><p style="text-align: center">**Tabela 02 - Léxicos do tipo Objeto** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
| <a id="correios">**L01 - Correios**</a> | Objeto | Empresa pública federal responsável pela execução do sistema de envio e entrega de <a href="#encomenda">encomendas</a> no Brasil, assim como presta outros serviços de apoio ao Governo.  | Responsável pelo desenvolvimento e manutenção do aplicativo "Correios". | Empresa Brasileira de Correios e Telégrafos |[Claudio Henrique](https://github.com/claudiohsc) |
| <a id="documento-identificacao">**L02 - Documento**</a> | Objeto | Documento utilizado para identificar oficialmente uma pessoa, podendo ser RG, CPF, passaporte, entre outros. | Utilizado por órgãos públicos e privados para confirmação de identidade e acesso a serviços. | Documento de identificação |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
| <a id="encomenda">**L03 - Encomenda** </a> | Objeto | Objeto que é embalado e enviado de um local para outro, quando o <a href="#usuario">usuário</a> realiza um <a href="#enviar">envio</a> ou recebe alguma  <a href="#encomenda">encomenda</a>. | É possível realizar o <a href="#enviar">envio</a>, <a href="#adiamento">adiamento</a> ou <a href="#cancelamento">cancelamento</a> da entrega da encomenda. | Pacote |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
| **L04 -** | Objeto |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
| <a id="destinatario">**L05 - Destinatário**</a> | Objeto | Pessoa que recebe uma <a href="#encomenda">encomenda</a> <a href="#enviar">enviada</a> por um <a href="#remetente">remetente</a> | Tem suas informações preenchidas durante a <a href=#prepostagem>pré-postagem</a> | |[Gabriel Fernando](https://github.com/MMcLovin) |
| <a id="remetente">**L06 - Remetente**</a> | Objeto | Usuário do aplicativo dos <a href="#correios">Correios</a> que <a href="#enviar">envia</a> uma <a href="#encomenda">encomenda</a> | É o responsável por preencher as informações da <a href=#prepostagem>pré-postagem</a> | | [Gabriel Fernando](https://github.com/MMcLovin) |  
| <a id="alfandega">**L07 - Alfândega**</a> | Objeto | A alfândega é de uma repartição da Receita Federal, e um órgão governamental oficial responsável pelo controle das operações de entrada e saída de mercadorias do país. Além disso, a alfândega é encarregada de <a href="#taxar">cobrar os tributos e taxas aduaneiras</a> aplicáveis às mercadorias que cruzam as fronteiras. | Entidade responsável por informar e manter as situações alfandegárias das <a href="#encomenda">encomendas</a> internacionais nos <a href="#correios">Correios</a>. | Aduana | [Pablo Santos](https://github.com/pabloheika) |
| **L08 - Código de rastreio** | Objeto | Sequência de caracteres alfanuméricos que representa a <a href="#encomenda">encomenda</a> e permite rastrear e verificar seu status. | Acompanhar o status e localização da <a href="#encomenda">encomenda</a>. | Número de rastreio |[Ricardo Augusto](https://github.com/avmricardo) |
| <a id="cep">**L09 - CEP**</a> | Objeto | É a sigla de Código de Endereçamento Postal que serve para organizar e facilitar a postagem, <a href="#rastrear">rastreio</a> e distribuição das <a href="#encomenda">encomendas</a> de forma lógica. | O CEP é utilizado para identificar rapidamente o endereço que será utilizado para fins de <a href="#simular">simulação</a> e postagens das <a href="#encomenda">encomendas</a> e correspondências.  | Código de Endereçamento Postal |[Claudio Henrique](https://github.com/claudiohsc) |


<center>**Fonte**: Autores das descrições dos léxicos do tipo Objetos, 2024. </center>

## Verbo

Nos léxicos do tipo verbo deve-se descrever: quem realiza, quando realiza, quais os processos realizados e quais os reflexos da ação no ambiente. Abaixo na tabela 03 estão descritos os léxicos do tipo verbo.

<font size="3"><p style="text-align: center">**Tabela 03 - Léxicos do tipo Verbo** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
|<a id="simular">**L - Simular**</a> | Verbo | O usuário pode <a href="#simular">simular</a>, antes do envio, os preços e prazos de entrega de uma <a href="#encomenda">encomenda</a> a partir do CEP de origem e destino. |  | |[Claudio Henrique](https://github.com/claudiohsc) |
| <a id="buscar">**L - Buscar**</a> | Verbo | O usuário pode <a href="#buscar">buscar</a> informações ou objetos, como documentos, utilizando critérios específicos de pesquisa. | Facilita o acesso rápido a informações ou localização de itens. | Procurar, Pesquisar | [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
|<a id="enviar">**L - Enviar** </a> | Verbo | O envio pode ser realizado pelo <a href="#usuario">usuário</a> ao expedir uma <a href="#encomenda">encomenda</a> para um destinatário. | A <a href="#encomenda">encomenda</a> é enviada entregando ela em uma agência dos correios, e seu envio pode ser feito por diferentes meios de transporte chegando até ao <a href="#destinatario">destinatário</a>.  | expedir |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
|**L -** | Verbo |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
|<a id="prepostagem">**L - Pré-postar**</a> | Verbo | O <a href="#remetente">remetente</a> pode optar por fazer a maior parte do processo de postar uma <a href="#encomenda">encomenda</a> pelo próprio aplicativo dos <a href="#correios">Correios</a>| A página de <>Minhas Postagens<> deve ser atualizada com a <a href="#prepostagem">pré-postagem</a> na seção de <a href="#aguardando">espera</a>| |[Gabriel Fernando](https://github.com/MMcLovin) |
|<a id="taxar">**L - Taxar**</a> | Verbo | Ato de fazer a cobrança de um imposto, multa ou outros tributos monetários. | Possibilita o usuário implementar cobranças devidas de tributos e taxas aplicáveis às <a href="#encomenda">encomendas</a>.  | Tributar, Tarifar. |[Pablo Santos](https://github.com/pabloheika) |
|<a id="rastrear">**L - Rastrear**</a> | Verbo | O usuário pode consultar o status da entrega da <a href="#encomenda">encomenda</a> em tempo real, verificando sua localização, histórico de movimentações e eventuais problemas na entrega. | Permite ao usuário acompanhar o andamento da entrega, ter previsões de entrega e se preparar para recebê-la. | Acompanhar. |[Ricardo Augusto](https://github.com/avmricardo) |

<center>**Fonte**: Autores das descrições dos léxicos do tipo Verbo, 2024. </center>


## Estado

Nos léxicos do tipo estado são definidos: qual o significado das ações e quais levaram a esse estado, e mostrar quais outros estados e ações que pode-se chegar e realizar a partir do estado atual. Abaixo na tabela 04 são elencados os léxicos do tipo estado.

<font size="3"><p style="text-align: center">**Tabela 04 - Léxicos do tipo Estado** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
| <a id="logado">**L - Usuário logado**</a> | Estado | Ocorre quando o usuário faz o seu Login no aplicativo do <a href="#correios">Correios</a>.  | É possível realizar pré-postagem, ver mensagens, vales postais e sobre a conta. Quando o usuário desconecta da sua conta, ele sai do estado atual.  | Usuário conectado |[Claudio Henrique](https://github.com/claudiohsc) |
|<a id="logado">**L - Documento encontrado**</a> | Estado | Ocorre quando o <a href="#documento">Documento</a> é encontrado através da <a href="#buscar">busca</a> no aplicativo,o documento fica guardado em uma agência por um período de 60 dias. | Nesse momento cabe ao usário ir até a agência retirar o seu documento pagando uma taxa de 10 reais. | Localizado, Achado. |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
| <a id="embaraço_aduaneiro">**L18 - Embaraço Aduaneiro** </a> | Estado | A  <a href="#encomenda">encomenda</a> fica retida em uma sede de inspeção da receita federal para a averiguação do objeto e possível <a href="#taxar">tributação</a>.O objeto é levado para a <a id="alfandega">aduana</a> por ser identificado algum item que não foi <a href="#taxar">tributado</a> ou foi <a href="#taxar">tributado</a> de maneira incorreta. | Pode-se realizar o <a href="#taxar">pagamento de taxas</a> alfandegárias ou cancelar o recebimento da encomenda. | Restrição alfandegária |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
| **L -** | Estado |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
| <a id="aguardando">**L - Aguardando Postagem**</a> | Estado | Quando um <a href="#remetente">remetente</a> faz uma <a href="#prepostagem">pré-postagem</a>, a mesma ficará em aguardo na seção de minhas postagens do aplicativo dos <a href="#correios">Correios</a>, até que seja postada em uma <>agência<> | Após a <a href="#encomenda">encomenda</a> ter sido postada em uma agencia, ela sairá da página de "Em aguardo" | Em espera |[Gabriel Fernando](https://github.com/MMcLovin) |
| **L -** | Estado |  |  | |[Pablo Santos](https://github.com/pabloheika) |
| **L - Em Trânsito** | Estado | A <a href="#encomenda">encomenda</a> está se movimentando entre os Correios e ainda não chegou ao destinatário. | Indica que a entrega da <a href="#encomenda">encomenda</a> está em andamento e que o usuário pode acompanhar seu status através do código de rastreio. | Em transporte |[Ricardo Augusto](https://github.com/avmricardo) |
| **L - Entregue** | Estado | A <a href="#encomenda">encomenda</a> foi entregue ao destinatário e a entrega está finalizada. | Indica que o destinatário já recebeu a <a href="#encomenda">encomenda</a> e que o processo de entrega foi concluído com sucesso. | Objeto entregue ao destinatário |[Ricardo Augusto](https://github.com/avmricardo) |

<center>**Fonte**: Autores das descrições dos léxicos do tipo Estado, 2024. </center>



## Bibliografia

> 1. SERRANO, Milene. Requisitos – Aula 10. Apresentação de slides. Disponível em: [Requisitos Aula - 10](https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf). Acesso em: 16/05/2024.
> 2. SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 16/05/2024.

## Histórico de versões
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
` 1.0 `| 15/05/2024 | Criação do Documento | [Elias Oliveira](https://github.com/EliasOliver21) e [Claudio Henrique](https://github.com/claudiohsc) | []() |