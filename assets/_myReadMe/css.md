
________Identificadores________

•tag
•id="#id"
•class=".class"

___comentarios___

Ctrol + /

________Unidades________

Fixas

•Milímetro (1mm) CUIDADO - essa valor varia de acordo com o Zoom da tela
•Centímetro (1cm) CUIDADO - essa valor varia de acordo com o Zoom da tela
•inches (1in = 96px ou 2.54cm)
•Píxels (1px = 1/96 ou 1 inches) CUIDADO - Uma tela HD tem menos "px" que uma tela 4k
•Points (1pt = 1/72 ou 1 inches)
•Paica (1pc = 12 pontos)

Relativas

"UNIDADES RELATIVAS SAO RELATAIVAS A ALGO""

•Porcentagem (1% - Relativo ao tamanho do Elemento Pai) - CUIDADO - Se voce mudar o tamanho do Pai, o tamanho do Filho sera alterado
•Viewport Heith (1vh - Relativo a Altura da tela)
•Viewport Width (1vw - relativo a Largura da tela)
•Ems (em)
•Rems (rem)
•(Ex)
•character unit (ch)
•viewport minimun (vmin)
•viewport maximum (vmax)

________Edicao de Texto________
text-
text-transform
text-decoration
text-align
text-shadow
letter-spacing
word-spacing

________Edicao de font________
font-
font-family: Arail, sans-serif
font-family: "courier new", Courier, monospace
font-Style
font-size
font-weight

border
boxmodel
box sizing
scroll


________Position________

<Margin> - Espacamento externo
<Padding> - Espacamento0 interno

Display-
<inline> Elementos que NAO ocupam a linha toda, por exemplo em sua forma natural o elemento <span> esse vode NAO pode redimencionar a altura e largura
<block> Elementos que ocupam a linha toda como por exemplo em sua forma natural o elemento <p>, esse voce pode redimencionar a altura e largura
<inline-block> Elementos que NAO ocupam a linha toda, por exemplo em sua forma natural o elemento <span> esse vode NAO pode redimencionar a altura e largura

Position-
<static>
O elemento fica no fluxo normal do documento
<relative>
O elemento fica no fluxo normal do documento, O elemento é posicionado em relação a si mesmo
<absolute>
O elemento saio do fluxo normal do documento. O elemento é posicionado em relação ao Pai, se o Pai nao for Static
Sua posição final é determinada por top, right, bottome left.
<fixed>
O elemento sai do fluxo normal do documento. O elemento é posicionado em relação a ViewPort.
Sua posição final é determinada por top, right, bottom e left.
<sticky>
O elemento continua no fluxo normal do documento, mas quando rolamos a pagina, ele fica grudado ao Pai

Float
OverFlow