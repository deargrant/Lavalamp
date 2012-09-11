Lavalamp
========
** ESTE CÓDIGO <B>NÃO</B> PERTENCE À MIM **
Tutorial de minha autoria e apenas!<br>Todos os códigos estão disponíveis separadamente no repositório caso ache necessário!
<br>

Código básico
=====
Comece colando o código à seguir onde você deseja que o menu apareça. Em "link" você deve colocar o nome/título do link, e em #, o endereço URL para onde o link direcionará.

<pre>
&lt;ul class="lavaLamp"&gt;
            &lt;li&gt;&lt;a href="#"&gt;LINK&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href="#"&gt;LINK&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href="#"&gt;LINK&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href="#"&gt;LINK&lt;/a&gt;&lt;/li&gt;
        &lt;/ul&gt;
</pre>
<br>
Estilo
=
Abaixo se encontra o estilo do menu lavalamp que devem ser postos entre as tags &lt;style> e &lt;/style>:
<pre>
        .lavaLampWithImage {
            position: relative;
            height: 30px;
            width: 800px;
            background: url("http://static.tumblr.com/mpornxv/B2Clov3g4/bg.gif") no-repeat top;
            padding: 15px;
            margin: 10px 0;
            overflow: hidden;
        }
                .lavaLampWithImage li {
                    float: left;
                    list-style: none;
                }
                    .lavaLampWithImage li.back {
                        background: #77a692 no-repeat right -30px;
                        width: 9px; height: 30px;
                        z-index: 8;
                        position: absolute;
                    }
                        .lavaLampWithImage li.back .left {
                            background: #77a692 no-repeat top left;
                            height: 30px;
                            margin-right: 9px; /* 7px is the width of the rounded shape */
                        }
                    .lavaLampWithImage li a {
                        font: bold 14px arial;
                        text-decoration: none;
                        color: #fff;
                        outline: none;
                        text-align: center;
                        top: 7px;
                        text-transform: uppercase;
                        letter-spacing: 0;
                        z-index: 10;
                        display: block;
                        float: left;
                        height: 30px;
                        position: relative;
                        overflow: hidden;
                        margin: auto 10px;    
                    }
                        .lavaLampWithImage li a:hover, .lavaLampWithImage li a:active, .lavaLampWithImage li a:visited {
                            border: none;
                        }

        .lavaLampNoImage {
            position: relative;
            height: 30px;
            width: 800px;
            background-color: white;
            padding: 15px;
            margin: 10px 0;
            overflow: hidden;
            border: 1px solid gray;
        }
                .lavaLampNoImage li {
                    float: left;
                    list-style: none;
                }
                    .lavaLampNoImage li.back {
                        border: 1px solid #000;
                        background-color: #e6e8ea;
                        width: 9px;
                        height: 30px;
                        z-index: 8;
                        position: absolute;
                    }
                    .lavaLampNoImage li a {
                        font: bold 14px arial;
                        text-decoration: none;
                        color: #000;
                        outline: none;
                        text-align: center;
                        top: 7px;
                        text-transform: uppercase;
                        letter-spacing: 0;
                        z-index: 10;
                        display: block;
                        float: left;
                        height: 30px;
                        position: relative;
                        overflow: hidden;
                        margin: auto 10px;
                    }
                        .lavaLampNoImage li a:hover, .lavaLampNoImage li a:active, .lavaLampNoImage li a:visited {
                            border: none;
                        }                    

        .lavaLampBottomStyle {
            position: relative;
            height: 30px;
            width: 800px;
            background-color: white;
            padding: 15px;
            margin: 10px 0;
            overflow: hidden;
            border: 1px solid gray;
        }
                .lavaLampBottomStyle li {
                    float: left;
                    list-style: none;
                }
                    .lavaLampBottomStyle li.back {
                        border-bottom: 5px solid blue;
                        width: 9px;
                        height: 30px;
                        z-index: 8;
                        position: absolute;
                    }
                    .lavaLampBottomStyle li a {
                        font: bold 14px arial;
                        text-decoration: none;
                        color: #000;
                        outline: none;
                        text-align: center;
                        top: 7px;
                        text-transform: uppercase;
                        letter-spacing: 0;
                        z-index: 10;
                        display: block;
                        float: left;
                        height: 30px;
                        position: relative;
                        overflow: hidden;
                        margin: auto 10px;
                    }   
                        .lavaLampBottomStyle li a:hover, .lavaLampBottomStyle li a:active, .lavaLampBottomStyle li a:visited {
                            border: none;
                        }   
                        .lavaLamp {
    position: relative;
    height: 29px; width: LARGURApx;
    background: #COR DE FUNDO no-repeat top;
    padding: 7px; margin: 5px 0;
    overflow: hidden;
}
    /* Force the list to flow horizontally */
    .lavaLamp li {
        float: left;
        list-style: none;
    }
        /* Represents the background of the highlighted menu-item. */
        .lavaLamp li.back {
            background: #COR FUNDO HOVER  no-repeat right -30px;
            width: 9px; height: 30px;
            z-index: 8;
            position: absolute;
        }
            .lavaLamp li.back .left {
                background: #COR FUNDO HOVER  no-repeat top left;
                height: 30px;
                margin-right: 9px;
            }
        /* Styles for each menu-item. */
        .lavaLamp li a {
            position: relative; overflow: hidden;
            text-decoration: none;
            text-transform: uppercase;
            font: bold 14px arial;
            color: #fff; outline: none;
            text-align: center;
            height: 30px; top: 7px;
            z-index: 10; letter-spacing: 0;
            float: left; display: block;
            margin: auto 10px;
        }
</pre>
<br>
Javascript
=
    <script type="text/javascript" src="http://static.tumblr.com/mpornxv/BnLlov3e2/jquery-1.1.3.1.min.js"></script>

    <script type="text/javascript" src="http://static.tumblr.com/mpornxv/n3hlov3c1/jquery.easing.min.js"></script>

    <script type="text/javascript" src="http://static.tumblr.com/mpornxv/Mwklov3cl/jquery.lavalamp.js"></script>
<pre>&lt;script type="text/javascript">
    $(function() {
  $(".lavaLamp").lavaLamp({
  fx: "backout", speed: 700 })
  });

&lt;/script></pre>

Faça as substituições em #COR FUNDO HOVER (é a cor que fica quando o mouse estiver por cima do link), LARGURA a largura do seu menu e #COR DE FUNDO é a cor de fundo do menu todo.