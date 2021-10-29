<html>

<body>

<header>
<h1>FlexBox</h1>
</header>

<div>

<div>

<ul>

<h2>Flex Container</h2>
<p>-É a tag que envolve os itens, será nela que iremos aplicar a propriedade "display:flex". Transforma todos os seus itens filhos em flex itens.</p>
<strong>- Propriedades relacionadades</strong>
<li>display</li>
<li>flex-direction</li>
<li>flex-wrap</li>
<li>flex-flow</li>
<li>justify-content</li>
<li>lign-items</li>
<li>align-content</li>
</ul>

</div>

<div>

<ul>

<h2>Flex Item</h2>

<p>-São os elementos filhos diretos do Flex Container. É também
podem se tornar Flex Container.</p>
<strong>- Propriedades relacionadades</strong>

<li>flex-grow</li>
<li>flex-basis</li>
<li>flex-shrink</li>
<li>flex</li>
<li>order</li>
<li>align-self</li>

</ul>

</div>
<div>

<ul>

<h2>Flex Item</h2>

<p>-São os elementos filhos diretos do Flex Container. É também
podem se tornar Flex Container.</p>
<strong>- Propriedades relacionadades</strong>

<li>flex-grow</li>
<li>flex-basis</li>
<li>flex-shrink</li>
<li>flex</li>
<li>order</li>
<li>align-self</li>

</ul>

</div>

<div>

<ul>

<h2>Flex Direction</h2>

<p>-É a propriedade que estabeleceo eixo principal do container,
definindo assim a direção que os flex items são colocados no flex container.</p>
<strong>- -EIXOS</strong>

<li>Row (padrão) : à direção do texto, esquerda para direita.
<ul><li>row-reverse : sentido oposto à direção do texto.</li></ul>
</li>
<li>Column : ordenação de cima para baixo, em coluna unica.
<ul><li>column-reverse : ordenação inversa, de baixo para cima.</li></ul>
</li>

</ul>

</div>

<div>

<ul>

<h2>Flex Wrap</h2>

<p>-É a propriedade que define se os itens devem ou não quebrar a linha.
	por padrão eles não quebram linhas, isso faz com que os flex itens
sejam compactados além do limite do conteúdo.</p>
<strong>- Comportamentos</strong>

<li>Wrap
<ul><li>nowrap : é o padrao, não permite a quebra de linha.</li></ul>
<ul><li>wrap : permite a quebra de linha assim que um dos flex itens não puder mais ser compactado.</li></ul>
</li>
<li>Wrap Reverse
<ul><li>wrap : permite a quebra de linha assim que um dos flex itens não puder nais ser compactado, porém na direção contrária da linha,acima.</li></ul>
</li>

</ul>

</div>
<div>
<h2>Flex Flow</h2>
<p>- É um atalho para as propriedade flex-direction e flex-wrap.

	porém seu uso não é tão comum, visto que, quando mudamos o flex-direction para column, mantemos o padrao do flex-wrap que é no wrap.</p>
</div>




</div>

</body>

</html>