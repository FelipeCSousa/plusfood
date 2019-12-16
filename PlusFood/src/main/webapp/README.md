<img src="offshore.jpg" style="display: block; margin-left: auto; margin-right: auto; width: 15%"/>
<h3 style="text-align: center; margin-top: 0px">OffShore Sistemas</h3>

**OffShore Sistemas** � uma empresa fict�cia com sede na cidade de S�o Lu�s do Maranh�o especializada no desenvolvimento de aplica��es para com�rcio eletr�nico (E-commerce). Seu marco inicial foi o desenvolvimento de um sistema de folha de pagamentos no ano de 1997. Atualmente possui um portf�lio de clientes nas mais variadas �reas, dentre elas: gastronomia, vestu�rio e bebidas.

Este documento trata dos requisitos do Sistemas de Vendas On-line +Food (Plus Food) por solicita��o do grupo Acme Gastronomius, parceiro de longa data da OSS.

>*Os requisitos foram simplificados para os prop�sitos deste projeto

#### Especifica��o de Requisitos

1. O Sistema dever� exibir uma mensagem de boas vindas em sua home-page e a partir desta ser�o apresentados ao usu�rio os estabelecimentos do grupo<p/>

1. A lista de restaurantes conter� informa��es resumidas do estabelecimento em quest�o: logomarca, nome empresarial, categoria, tempo m�dio de entrega e a m�dia da avalia��o dos clientes<p/>

1. Ap�s a escolha de um restaurante pelo usu�rio, dever�o ser mostrados os produtos/card�pio comercializados pelo estabelecimento escolhido contendo: a imagem do item, nome, descri��o e pre�o, al�m de mais informa��es sobre o estabelecimento: nome de fantasia, logomarca, categoria, m�dia da avalia��o dos clientes, texto institucional e hor�rio de funcionamento<p/>

1. O Sistema tamb�m dever� mostrar as avalia��es mais recentes dos clientes contendo *avatar* do usu�rio, nome de usu�rio, avalia��o/nota e um texto, opcional,  justificando tal avalia��o. Dever� ser avisado que a avalia��o ser� publicada em at� 7 dias ap�s modera��o<p/>

1. Dever� ser fornecido um "carrinho de compras" que armazenar� provisoriamente os itens selecionados para compra pelo usu�rio. O carrinho mostrar� o produto escolhido (nome, quantidade comprada, pre�o unit�rio, subtotal do item), valor da taxa de entrega e total da compra. O usu�rio poder� "limpar" o carrinho, caso desista da compra, ou confirmar a compra<p/>

1. Quando um item for adicionado ao carrinho sua quantidade dever� ser incrementada, caso seja retirado, a quantidade dever� ser decrementada at� a remo��o do mesmo. O Sistema dever� informar quando o carrinho de compras estiver vazio<p/>

1. Na confirma��o da compra o Sistema fornecer� um meio de o usu�rio informar dados relativos a entrega e op��es de pagamento (<span style="color: red">necessita mais informa��es</span>)<p/>

1. Durante a confirma��o da compra o Sistema dever� consumir servi�os relativos a op��o de pagamento escolhida pelo usu�rio, e n�o havendo restri��es, a compra ser� confirmada e o pedido entrar� na fila de espera do restaurante selecionado

#### Instru��es
>Para simplificar, na confirma��o da compra dever� ser mostrado a p�gina de conclus�o do pedido. N�o ser� necess�rio implementar o sistema de avalia��o dos usu�rios. O valor da taxa de entrega para todos os estabelecimentos ser� R$ 8,00.

O candidato dever� implementar os requisitos para o "carrinho de compras" e a p�gina de conclus�o de pagamento, convertendo-o para *facelets*. � <u>mandat�rio</u> utilizar o *layout*  fornecido.

O projeto traz um prot�tipo de interface gr�fica que poder� ser usado para dirimir d�vidas e tamb�m onde ser� encontrado o arquivo da p�gina de conclus�o de pagamento em HTML.

Para este projeto foram utilizados:

Java 8<br/>
Maven 3.5.x<br/>
Git 2.17.x<br/>
Eclipse (utilizar a vers�o mais recente)<br/>
Wildfly 9.x (exige JRE 8.x)<br/>
JBoss Tools<br/>
Bootstrap 3.3.x<br/>
Facelets 1.1.x<br/>
JSF 1.2<br/>

>O *plugin* JBoss Tools fornece todos os artefatos necess�rios para a utiliza��o do projeto<p/>
>O candidato dever� configurar o pr�prio ambiente de desenvolvimento<p/>
>O diret�rio **docs** do projeto cont�m informa��es adicionais de configura��o do ambiente


<br/><br/><br/>
<span style="display:block; text-align: center;">Boa sorte!</span>