# Botão com Linha Diagonal no Canto

Script que permite gerar o CSS necessário para criar um botão com os cantos em diagonal utilizando 

[Clique Aqui para Abrir o Gerador de Botão](https://rawgit.com/cmacetko/Util-btn-skewX/master/index.html)

# Compatibilidade

* IE 10+
* Google Chrome 36+
* Firefox 16+
* Safari 3.2+
* Opera 23+

# Cross-Browser

É necessário repetir o comando para cada versão:

**Exemplo:**

    -ms-transform: skewX(100deg); /* IE 9 */
    -webkit-transform: skewX(100deg); /* Safari */
    transform: skewX(100deg);


# Note

Para evitar que o texto do botão acompanhe o angulo definido, é necessário definir um valor negativo acima do botão.

**Exemplo de CSS:**

    #btn-gerado
    {
    	-ms-transform: skewX(-50deg);
    	-webkit-transform: skewX(-50deg);
    	transform: skewX(-50deg);
    	background:#000;
    	display:inline-block;
    	padding:10px 100px;
    }
    #btn-gerado a
    {
    	-ms-transform: skewX(50deg);
    	-webkit-transform: skewX(50deg);
    	transform: skewX(50deg);
    	color:#FFF;
    	font-size:13px;
    	display:block;
    }

**Botão:**

    <div id="btn-gerado"><a href="#">Teste de Botão</a></div>