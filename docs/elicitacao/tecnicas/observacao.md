# Observação

## Introdução

A técnica de elicitação de requisitos _Observação_, também chamada de _etnografia_, é utilizada em áreas onde se sabe da importância de obter o entendimento das interações entre pessoas com outras pessoas, instituições, seu ambiente ou máquinas e softwares. Para esse entendimento, é preciso assimilar o que as pessoas conhecem sobre alguma área e como esse conhecimento é criado, transmitido, distribuído e aplicado <a id="a" href="#aa">[1]</a>.

Uma das variações dessa técnica é a abordagem por aprendiz, em que o analista de requisitos atua como um novato no sistema que será obervado pela equipe, com o intuito de aprender como executar o sistema. Essa será a técnica utilizada pelo grupo, em que um integrante irá representar um aprendiz do sistema, e outro irá ter a tarefa de observar o aprendiz utilizando o aplicativo.

## Metodologia

A aplicação da técnica de observação foi realizada por dois integrantes do grupo, e foi implementada a abordagem por aprendiz descrita no tópico anterior. Um integrante do grupo foi o representante de um aprendiz do sistema e outro foi o observador.

A reunião dos [integrantes](#tabelaIntegrantes) ocorreu no dia 16 de abril de 2024, às 17h, para implementarem a técnica de elicitação por observação. Previamente, foi definido que o aprendiz vai começar fazendo seu login no aplicativo, posteriormente ele irá passar pelas funcionalidades presentes na tela inicial do aplicativo, e para finalizar ele deverá acessar as funcionalidades presentes no menu da esquerda presente no aplicativo. Para essa técnica, o observador participou de maneira passiva da observação, não influenciando e não dando dicas/sugestões para o aprendiz.

Para a documentação da técnica, o aprendiz do sistema gravou a tela do celular mostrando as ações realizadas por ele dentro do aplicativo, o link para a gravação se encontra **aqui**. Durante a análise, foram levantados os requisitos observados, presentes nas tabelas [2](#tabelaRequisitosFuncionais) e [3](#tabelaRequisitosNaoFuncionais).

### Participantes

<center>
<a name="tabelaIntegrantes"></a>
<font size="2"><p>
    <b>Tabela 1</b> - Integrantes participantes da técnica
</p></font>

| Integrante | Tarefa |
|:-:|:-:|
| [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) | Representante do aprendiz |
| [Ricardo Augusto](https://github.com/avmricardo) | Observador |

<font size="2"><p>Fonte: [Ricardo Augusto](https://github.com/avmricardo), 2024.</p></font>
</center>

## Requisitos elicitados

Abaixo estão descritos os requisitos elicitados a partir da técnica de observação. Abaixo se encontra a legenda para as tabelas de requisitos:

Legenda:

- RFxx: Requisito funcional número xx;
- NFxx: Requisito não funcional número xx;
- OBSxx: Requisito elicitado pela técnica de observação número xx.

### Requisitos Funcionais (RF)

<center>
<font size="2"><p>
    <b>Tabela 2</b> - Requisitos Funcionais 
</p></font>

| Tipo | Descrição                                                                                          | ID    | Implementado |
|------|---------------------------------------------------------------------------------------------------|-------|--------------|
| RF01 | O aplicativo permite rastreamento de encomendas por código.                                       | OBS01 | Sim          |
| RF02 | O aplicativo oferece busca de CEPs e endereços.                                                   | OBS02 | Sim          |
| RF03 | O aplicativo possibilita o cálculo de frete e prazos de entrega.                                  | OBS03 | Sim          |
| RF04 | O aplicativo permite a compra de serviços e produtos oferecidos pelos Correios.                  | OBS04 | Sim          |
| RF05 | O aplicativo oferece opções de pré-postagem, permitindo preencher e imprimir etiquetas de envio. | OBS05 | Sim          |

<font size="2"><p>Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes), 2024.</p></font>
</center>

### Requisitos Não Funcionais (NF)

<center>
<a name="tabelaRequisitosNaoFuncionais"></a>
<font size="2"><p>
    <b>Tabela 3</b> - Requisitos Não Funcionais 
</p></font>


| Tipo | Descrição                                                                                          | ID    | Implementado |
|------|---------------------------------------------------------------------------------------------------|-------|--------------|
| NF01 | O aplicativo deve manter a privacidade dos dados do usuário.                                      | OBS06 | Sim          |
| NF02 | O aplicativo requer uma interface amigável e fácil de usar.                                        | OBS07 | Sim          |
| NF03 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones.                   | OBS08 | Sim          |
| NF04 | O aplicativo deve fornecer notificações em tempo real sobre o status da entrega.                  | OBS09 | Sim          |
| NF05 | O aplicativo deve garantir a segurança das transações realizadas dentro dele.                    | OBS10 | Sim          |

<font size="2"><p>Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes), 2024.</p></font>
</center>

## Bibliografia 

> <a id="a" href="#aa">[1]</a> CARLOS EDUARDO VAZQUEZ; GUILHERME SIQUEIRA SIMÕES. Engenharia de Requisitos. [s.l.] Brasport, 2016.

## Histórico de Versão

| Versão | Data | Autor | Descrição | Revisor
|:-:|:-:|:-:|:-:|:-:|
|`1.0`| 16/04/2024 | [Ricardo Augusto](https://www.github.com/avmricardo), [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) | Criação do documento | 
