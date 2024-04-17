# Observação

## Introdução

A técnica de elicitação de requisitos _Observação_, também chamada de _etnografia_, é utilizada em áreas onde se sabe da importância de obter o entendimento das interações entre pessoas com outras pessoas, instituições, seu ambiente ou máquinas e softwares. Para esse entendimento, é preciso assimilar o que as pessoas conhecem sobre alguma área e como esse conhecimento é criado, transmitido, distribuído e aplicado <a id="a" href="#aa">[1]</a>.

Uma das variações dessa técnica é a abordagem por aprendiz, em que o analista de requisitos atua como um novato no sistema que será observado pela equipe, com o intuito de aprender como executar o sistema. Essa será a técnica utilizada pelo grupo, em que um integrante irá representar um aprendiz do sistema, e outro irá ter a tarefa de observar o aprendiz utilizando o aplicativo.

## Metodologia

A aplicação da técnica de observação foi realizada por dois integrantes do grupo, e foi implementada a abordagem por aprendiz descrita no tópico anterior. Um integrante do grupo foi o representante de um aprendiz do sistema e outro foi o observador.

A reunião dos [integrantes](#tabelaIntegrantes) ocorreu no dia 16 de abril de 2024, às 17h, para implementarem a técnica de elicitação por observação. Previamente, foi definido que o aprendiz vai começar fazendo seu login no aplicativo, posteriormente ele irá passar pelas funcionalidades presentes na tela inicial do aplicativo, e para finalizar ele deverá acessar as funcionalidades presentes no menu da esquerda presente no aplicativo. Para essa técnica, o observador participou de maneira passiva da observação, não influenciando e não dando dicas/sugestões para o aprendiz.

Para a documentação da técnica, o aprendiz do sistema gravou a tela do celular mostrando as ações realizadas por ele dentro do aplicativo, o link para a gravação se encontra [aqui](#video). Durante a análise, foram levantados os requisitos observados, presentes nas tabelas [2](#tabelaRequisitosFuncionais) e [3](#tabelaRequisitosNaoFuncionais).

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

### Gravação

A execução da técnica foi documentada por meio de vídeo que se encontra abaixo.

<center>
<a name="video"></a>
<iframe width="560" height="315" src="https://www.youtube.com/embed/PVUJ4Stf4pU?si=6RG3A9vCvF-DiJwX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

Após a execução, os integrantes se reuniram para poder fazer a análise do vídeo e realizar a elicitação dos requisitos.

## Requisitos elicitados

Neste tópico estão descritos os requisitos elicitados a partir da técnica de observação. Abaixo se encontra a legenda para as tabelas de requisitos:

Legenda:

- RFxx: Requisito funcional número xx;
- RNFxx: Requisito não funcional número xx;
- OBSxx: Requisito elicitado pela técnica de observação número xx.

### Requisitos Funcionais (RF)

<center>
<font size="2"><p>
    <b>Tabela 2</b> - Requisitos Funcionais 
</p></font>

| Tipo | Descrição | ID | Implementado |
|-|-|-|-|
| RF01 | O aplicativo permite realizar login com sua conta | OBS01 | Sim |
| RF02 | O aplicativo permite rastreamento de encomendas por código. | OBS02 | Sim |
| RF03 | O aplicativo permite enviar encomendas (envelope, caixa, cilindro) | OBS03 | Sim |
| RF04 | O aplicativo possibilite ver seus pagamentos | OBS04 | Sim |
| RF05 | O aplicativo oferece uma busca por agências próximas ao seu endereço | OBS05 | Sim |
| RF06 | O aplicativo possibilita o cálculo de preços e prazos de encomendas nacionais e internacionais | OBS06 | Sim |
| RF07 | O aplicativo possibilita a compra de certificados digitais dos correios | OBS07 | Sim |
| RF08 | O aplicativo oferece o acompanhamento da sua conta e realizar recargas pelo aplicativo | OBS08 | Sim |
| RF09 | O aplicativo permite visualização de mensagens | OBS09 | Sim |
| RF10 | O aplicativo oferece a visualização de vales postais | OBS10 | Sim |
| RF11 | O aplicativo oferece uma área de busca por objetos perdidos em envios | OBS11 | Sim |
| RF12 | O aplicativo fornece uma área de contato sobre violência contra a mulher | OBS12 | Sim |


<font size="2"><p>Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes), [Ricardo Augusto](https://www.github.com/avmricardo), 2024.</p></font>
</center>

### Requisitos Não Funcionais (RNF)

<center>
<a name="tabelaRequisitosNaoFuncionais"></a>
<font size="2"><p>
    <b>Tabela 3</b> - Requisitos Não Funcionais 
</p></font>


| Tipo | Descrição | ID | Implementado |
|-|-|-|-|
| RNF01 | O aplicativo deve manter a privacidade dos dados do usuário. | OBS13 | Sim |
| RNF02 | O sistema de rastreamento de encomendas deve ser rápido e eficiente | OBS14 | Sim |
| RNF03 | O sistema de envio de encomendas deve ser robusto o suficiente para lidar com diferentes tipos de objetos | OBS15 | Sim |
| RNF04 | O acesso aos pagamentos deve ser protegido por autenticação do usuário | OBS16 | Não |
| RNF05 | A busca por agências deve ser precisa e baseada na localização do usuário | OBS17 | Sim |
| RNF06 | O cálculo de preços e prazos de encomendas deve ser preciso e rápido | OBS18 | Sim |
| RNF07 | A compra de certificados digitais deve ser segura e protegida | OBS19 | Sim |
| RNF08 | O acompanhamento da conta e recargas devem ser realizados de forma segura e confiável | OBS20 | Sim |
| RNF09 | A visualização de mensagens deve ser rápida e fácil de usar | OBS21 | Sim |
| RNF10 | A visualização de vales postais deve ser protegida e acessível apenas pelo usuário autorizado | OBS22 | Sim |
| RNF11 | A busca por objetos perdidos deve ser eficiente e precisa | OBS23 | Sim |
| RNF12 | A área de contato sobre violência contra a mulher deve ser sensível e oferecer suporte adequado | OBS24 | Sim |
| RNF13 | O aplicativo requer uma interface amigável e fácil de usar. | OBS25 | Sim |
| RNF14 | O aplicativo deve funcionar em diferentes sistemas operacionais de smartphones. | OBS26 | Sim |
| RNF15 | O aplicativo deve fornecer notificações sobre o status da entrega. | OBS27 | Sim |


<font size="2"><p>Fonte: [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes), [Ricardo Augusto](https://www.github.com/avmricardo), 2024.</p></font>
</center>

## Bibliografia 

> <a id="a" href="#aa">1.</a> CARLOS EDUARDO VAZQUEZ; GUILHERME SIQUEIRA SIMÕES. Engenharia de Requisitos. [s.l.] Brasport, 2016.

> <a id="b" href="#bb">2.</a> Correios. Disponível em: <https://apps.apple.com/br/app/correios/id1399617917>. Acesso em: 17 abr. 2024.

## Histórico de Versão

| Versão | Data | Autor | Descrição | Revisor
|:-:|:-:|:-:|:-:|:-:|
|`1.0`| 17/04/2024 | [Ricardo Augusto](https://www.github.com/avmricardo), [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) | Criação do documento | [Pablo S. Costa](https://www.github.com/pabloheika) |
