#Emmet参考手册

>Emmet (前身为 Zen Coding)
http://docs.emmet.io/cheat-sheet/

###在线编辑器的支持：
     JSFiddle
     JS Bin
     CodePen
     ICEcoder
     Divshot
     Codio

###HTML缩进表

####后代：>
    nav>ul>li
       <nav>
        <ul>
            <li></li>
        </ul>
       </nav>

####兄弟：＋
    div+p+bq
        <div></div>
        <p></p>
        <blockquote></blockquote>

####上级：^
    div+div>p>span+em^bq
        <div></div>
        <div>
            <p><span></span><em></em></p>
            <blockquote></blockquote>
        </div>

####分组：()
    div>(header>ul>li*2>a)+footer>p
        <div>
            <header>
                <ul>
                    <li><a href=""></a></li>
                    <li><a href=""></a></li>
                </ul>
            </header>
            <footer>
                <p></p>
            </footer>
        </div>

####乘法：*
    ul>li*5
        <ul>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
        </ul>

####自增符号：$
    ul>li.item$*5
        <ul>
            <li class="item1"></li>
            <li class="item2"></li>
            <li class="item3"></li>
            <li class="item4"></li>
            <li class="item5"></li>
        </ul>
    h$[title=item$]{Header $}*3
        <h1 title="item1">Header 1</h1>
        <h2 title="item2">Header 2</h2>
        <h3 title="item3">Header 3</h3>
    ul>li.item$$$*5
        <ul>
            <li class="item001"></li>
            <li class="item002"></li>
            <li class="item003"></li>
            <li class="item004"></li>
            <li class="item005"></li>
        </ul>
    ul>li.item$@-*5
        <ul>
            <li class="item5"></li>
            <li class="item4"></li>
            <li class="item3"></li>
            <li class="item2"></li>
            <li class="item1"></li>
        </ul>
    ul>li.item$@3*5
        <ul>
            <li class="item3"></li>
            <li class="item4"></li>
            <li class="item5"></li>
            <li class="item6"></li>
            <li class="item7"></li>
        </ul>

####ID和类属性
    #header
        <div id="header"></div>
    .title
        <div class="title"></div>

####自定义属性
    p[title='hell world']
        <p title="hell world"></p>

####文本：{}
    a{Click me}
        <a href="">Click me</a>

####隐式标签
    em>.class
        <em><span class></span></em>
    ul>.class
        <ul>
            <li class></li>
        </ul>


####缩写：！
    <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <title>Document</title>
        </head>
        <body>
            
        </body>
    </html>

####缩写：a
    <a href=""></a>

####缩写：a:link
    <a href="http://"></a>

####缩写：a:mail
    <a href="mailto:"></a>

####缩写：abbr
    <abbr title=""></abbr>

####缩写：acronym
    <acronym title=""></acronym>

####缩写：base
    <base href="">

####缩写：basefont
    <basefont>

####缩写：br
    <br>

####缩写：frame
    <frame>

####缩写：hr
    <hr>

####缩写：bdo
    <bdo dir=""></bdo>

####缩写：bdo:r
    <bdo dir="rtl"></bdo>

####缩写：bdo:l
    <bdo dir="ltr"></bdo>

####缩写：col
    <col>

####缩写：link
    <link rel="stylesheet" href="">

####缩写：link:css
    <link rel="stylesheet" href="style.css">

####缩写:link:favicon
    <link rel="shortcut icon" type="image/x-icon" href="favicon.ico">

####缩写：link:touch
    <link rel="apple-touch-icon" href="favicon.png">

####缩写：link:rss
    <link rel="alternate" type="application/rss+xml" title="RSS" href="rss.xml">

####缩写：link:atom
    <link rel="alternate" type="application/atom+xml" title="Atom" href="atom.xml">

####缩写：meta
    <meta>

####缩写：meta:utf
    <meta http-equiv="Content-Type" content="text/html;charset=UTF-8">

####缩写：meta:win
    <meta http-equiv="Content-Type" content="text/html;charset=windows-1251">

####缩写：meta:vp
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">

####缩写：meta:compat
    <meta http-equiv="X-UA-Compatible" content="IE=7">

####缩写：style
    <style></style>

####缩写：script
    <script></script>

####缩写：script:src
    <script src=""></script>

####缩写：img
    <img src="" alt="">

####缩写：iframe
    <iframe src="" frameborder="0"></iframe>

####缩写：embed
    <embed src="" type="">

####缩写：object
    <object data="" type=""></object>

####缩写：param
    <param name="" value="">

####缩写：map
    <map name=""></map>

####缩写：area
    <area shape="" coords="" href="" alt="">

####缩写：area:d
    <area shape="default" href="" alt="">

####缩写：area:c
    <area shape="circle" coords="" href="" alt="">

####缩写：area:r
    <area shape="rect" coords="" href="" alt="">

####缩写：area:p
    <area shape="poly" coords="" href="" alt="">

####缩写：form
    <form action=""></form>

####缩写：form:get
    <form action="" method="get"></form>

####缩写：form:post
    <form action="" method="post"></form>

####缩写：label
    <label for=""></label>

####缩写：input
    <input type="text">

####缩写：inp
    <input type="text" name="" id="">

####缩写：input:hidden
    <input type="hidden" name="">

####缩写：input:search
    <input type="search" name="" id="">

####缩写：input:email
    <input type="email" name="" id="">

####缩写：input:url
    <input type="url" name="" id="">

####缩写：input:p
    <input type="password" name="" id="">

####缩写：input:datetime
    <input type="datetime" name="" id="">

####缩写：input:date
    <input type="date" name="" id="">

####缩写：input:datetime-local
    <input type="datetime-local" name="" id="">

####缩写：input:month
    <input type="month" name="" id="">

####缩写：input:week
    <input type="week" name="" id="">

####缩写：input:time
    <input type="time" name="" id="">

####缩写：input:number
    <input type="number" name="" id="">

####缩写：input:color
    <input type="color" name="" id="">

####缩写：input:checkbox
    <input type="checkbox" name="" id="">

####缩写：input:radio
    <input type="radio" name="" id="">

####缩写：input:range
    <input type="range" name="" id="">

####缩写：input:file
    <input type="file" name="" id="">

####缩写：input:submit
    <input type="submit" value="">

####缩写：input:image
    <input type="image" src="" alt="">

####缩写： input:button
    <input type="button" value="
    ">

####缩写：isindex
    <isindex>

####缩写：input:reset
    <input type="reset" value="">

####缩写：select
    <select name="" id=""></select>

####缩写：textarea
    <textarea name="" id="" cols="30" rows="10"></textarea>

####缩写：option
    <option value=""></option>

####缩写:menu:context
    <menu type="context"></menu>

####缩写：menu:toolbar
    <menu type="toolbar"></menu>

####缩写：video
    <video src=""></video>

####缩写：audio
    <audio src=""></audio>

####缩写：html:xml
    <html xmlns="http://www.w3.org/1999/xhtml"></html>

####缩写：keygen
    <keygen>

####缩写：command
    <command>

####缩写：bq
    <blockquote></blockquote>

####缩写:acr
    <acronym title=""></acronym>

####缩写：fig
    <figure></figure>

####缩写：figc
    <figcaption></figcaption>

####缩写：ifr
    <iframe src="" frameborder="0"></iframe>

####缩写：emb
    <embed src="" type="">

####缩写：obj
    <object data="" type=""></object>

####缩写：src
    <source>

####缩写：cap
    <caption></caption>

####缩写：colg
    <colgroup></colgroup>

####缩写：fst,fset
    <fieldset></fieldset>

####缩写：btn
    <button></button>

####缩写：btn:b
    <button type="button"></button>
