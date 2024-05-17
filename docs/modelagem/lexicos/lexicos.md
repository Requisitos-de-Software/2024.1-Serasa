## Introdução

O léxico é uma notação utilizada para apresentar os símbolos de uma linguagem através da descrição de termos, o principal uso dos léxicos na engenharia de requisitos é encontrar palavras ou frases que são peculiares no meio social do estudo em questão. Nos léxicos cada símbolo é caracterizado com noção e impacto, onde noção denota o significado do símbolo, já o impacto representa: o efeito, uso ou ocorrência do símbolo no sistema ou ainda o efeito de algo na aplicação sobre o símbolo.

## Metodologia

Tendo como base os [Requisitos Elicitados](../elicitacao/requisitos_elicitados.md) na etapa anterior identificamos e apresentamos os devidos léxicos separando em três tipos de sujeito que são: Objeto, Verbo e Estado que são descritos logo abaixo. Na tabela 01 é mostrado o formato ao qual os léxicos estão estruturados, para a criação dos léxicos utilizamos o LAL (Léxico Ampliado da Imagem) que é uma maneira mais refinada de registro de termos próprios da aplicação.

<font size="3"><p style="text-align: center">**Tabela 01: Formato do Léxico** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
|LXX - Nome. |Objeto,Verbo,Estado.|Significado do símbolo.|Efeito, uso ou ocorrência na aplicação.|Termo similar.|Integrante responsável pelo léxico.|

## Objeto

Nos léxicos do tipo Objeto é definido: o objeto, outros objetos com os quais se relaciona e as ações que poderão ser empregadas ao objeto. Na tabela 02 logo abaixo estão descritos os léxicos do tipo objeto.

<font size="3"><p style="text-align: center">**Tabela 02: Léxicos do tipo Objeto** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
| L01 - | Objeto |  |  | |[Claudio Henrique](https://github.com/claudiohsc) |
| L02 - | Objeto |  |  | |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
| <a id="encomenda">L03 - Encomenda </a> | Objeto | Objeto que é embalado e enviado de um local para outro, quando o <a href="#usuario">usuário</a> realiza um <a href="#enviar">envio</a> ou recebe alguma  <a href="#encomenda">encomenda</a>. | É possível realizar o <a href="#enviar">envio</a>, <a href="#adiamento">adiamento</a> ou <a href="#cancelamento">cancelamento</a> da entrega da encomenda. | Pacote |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
| L04 - | Objeto |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
| L05 - | Objeto |  |  | |[Gabriel Fernando](https://github.com/MMcLovin) |
| L06 - | Objeto |  |  | |[Pablo Santos](https://github.com/pabloheika) |
| L07 - | Objeto |  |  | |[Ricardo Augusto](https://github.com/avmricardo) |


## Verbo

Nos léxicos do tipo verbo deve-se descrever: quem realiza, quando realiza, quais os processos realizados e quais os reflexos da ação no ambiente. Abaixo na tabela 03 estão descritos os léxicos do tipo verbo.

<font size="3"><p style="text-align: center">**Tabela 03: Léxicos do tipo Verbo** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
|L08 - | Verbo |  |  | |[Claudio Henrique](https://github.com/claudiohsc) |
|L09 - | Verbo |  |  | |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
|<a id="enviar">L10 - Enviar </a> | Verbo | O envio pode ser realizado pelo <a href="#usuario">usuário</a> ao expedir uma <a href="#encomenda">encomenda</a> para um destinatário. | A encomenda é enviada entregando ela em uma agência dos correios, e seu envio pode ser feito por diferentes meios de transporte chegando até ao <a href="#destinatário">destinatário</a>.  | expedir |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
|L11 - | Verbo |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
|L12 - | Verbo |  |  | |[Gabriel Fernando](https://github.com/MMcLovin) |
|L13 - | Verbo |  |  | |[Pablo Santos](https://github.com/pabloheika) |
|L14 - | Verbo |  |  | |[Ricardo Augusto](https://github.com/avmricardo) |

## Estado

Nos léxicos do tipo estado são definidos: qual o significado das ações e quais levaram a esse estado, e mostrar quais outros estados e ações que pode-se chegar e realizar apartir do estado atual. Abaixo na tabela 04 são elencados os léxicos do tipo estado.

<font size="3"><p style="text-align: center">**Tabela 04: Léxicos do tipo Estado** </p></font>

|Léxico|Classificação|Noção|Impacto|Sinônimo|Autor|
|:------:|:-------------:|:-----:|:-------:|:--------:|:-----:|
| L15 - | Estado |  |  | |[Claudio Henrique](https://github.com/claudiohsc) |
| L16 - | Estado |  |  | |[Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) |
| <a id="embaraço_aduaneiro">L17 - Embaraço Aduaneiro </a> | Estado | A  <a href="#encomenda">encomenda</a> fica retida em uma sede de inspeção da receita federal para a averiguação do objeto e possível tributação.O objeto é levado para a aduana por ser identificado algum item que não foi tributado ou foi tributado de maneira incorreta. | Pode-se realizar o <a href="#pagamentodetaxas">pagamento de taxas</a> alfandegárias ou <a href="#cancelar_o_recebimento">cancelar o recebimento</a> da encomenda. | Restrição alfandegária |[Elias F. Oliveira](https://www.github.com/EliasOliver21) |
| L18 - | Estado |  |  | |[Gabriel Basto](https://github.com/Bertolazi) |
| L19 - | Estado |  |  | |[Gabriel Fernando](https://github.com/MMcLovin) |
| L20 - | Estado |  |  | |[Pablo Santos](https://github.com/pabloheika) |
| L21 - | Estado |  |  | |[Ricardo Augusto](https://github.com/avmricardo) |


## Bibliografia

> 1. SERRANO, Milene. Requisitos – Aula 10. Apresentação de slides. Disponível em: [Requisitos Aula - 10](https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf). Acesso em: 16/05/2024.
> 2. SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 16/05/2024.

## Histórico de versões
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
` 1.0 `| 15/05/2024 | Criação do Documento | [Elias Oliveira](https://github.com/EliasOliver21) | []() |