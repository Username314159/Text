        <link rel="stylesheet" href="stylesheet/style.css">

    </head>

    <body>
        <br><p>
        <a href = "https://www.w3schools.com/html/html_basic.asp" title = "learn HTML" target = "_blank" id = "link"> <em>This is a link </em><br> </a>
        <a href = "mailto:idunnoknowtheway@gmail.com" title = "mail">contact someone now!</a><br><br>
        <button target = "_blank" title = "coding site" onclick = "document.location='https://www.asc.ohio-state.edu/orban.14//physics_coding/bonk/bonk.html'">button</button><br>
        <br>

        <a href = "#list1">food list</a><br>
        <a href = "#list2">quack list</a><br>
        <a href = "#list3">formats list</a><br>
        </p>

        <img style = "border: 10px solid rgb(189, 93, 41);" src = "https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_4x3.jpg" 
             alt = "oops! oh well" width = "700" height = "600" usemap = "#workmap" title = "this is a cat">
        <a href = "Duck page.html">

        <picture>
            <source srcset = "file:///C:/Users/carso/Documents/Folder%20Tree/Images%20of%20Great%20Pleasure/ducko.jpg">
            <img src = "https://th.bing.com/th/id/R.e56a460d30a7c38597d67e02d7ecba94?rik=HS1%2f4%2bFn63hpJw&riu=http%3a%2f%2f3.bp.blogspot.com%2f-ogkSpbuCps4%2fTWG3DGdHkWI%2fAAAAAAAAA8M%2fUNBClDd1yLE%2fs1600%2fwhite-duck-water.jpg&ehk=amXglkfr8S07SuyY6SR89aJHrUZcZwotK5%2bMd2hT85Y%3d&risl=&pid=ImgRaw&r=0"
                alt = "duck" style = "width:550px;height:550px;" title = "this is a duck"></a>
                <!-- float:right -->
        </picture>

        <map name = "workmap">
            <area shape = "circle" coords = "330,310,30" alt = "eye" onclick = "myFunction()"
                  href = "https://en.wikipedia.org/wiki/Eye" target = "_blank">
            <area shape = "rect" coords = "0,0,100,100" alt = "darkness"
                  href = "https://upload.wikimedia.org/wikipedia/commons/c/c8/Very_Black_screen.jpg">
            
        </map>
        <script>
            function myFunction() {
                alert("You clicked on the eye!");
            }
        </script>
        
<!-- rect - defines a rectangular region
    circle - defines a circular region
    poly - defines a polygonal region
    default - defines the entire region-->

        <ol style = "background-image: url('https://th.bing.com/th/id/OIP.OwjBEKd5VZ91vEbNPdS7wwHaEK?rs=1&pid=ImgDetMain');">
            <li style = "text-align:center;"> <h1 style = "color:rgb(91, 189, 216);"> Rain </h1> <hr>
            <li style = "color:rgb(125, 38, 125);"> <h2 style = "font-family:verdana;"> test2 </h2> <hr>
        </ol>


        <address>
        <a href ="#link"> <ul style = "font-family:courier;" id = "list1"> 
            <li style = 'color:rgb(233, 146, 15)' title = 'carrots are "orange" indeed'> carrots 

            <li style = "color:rgb(251, 19, 19);" title = "delicoius"> tomatoes

            <li style = "color:rgba(193, 207, 32, 0.858);" title = "this is round most of the times"> potatoes
        </ul></a><hr>
        </adress>
        
        <i><b><ol style = "font-size:45px;" id = "list2"><a href ="#link">
            <li> w  h  a  t </li>
            <li> t h e </li>
            <li style = "border: 5px solid magenta;"> q u a c k </li>
        </a></ol></b></i>
        

        <pre style = "font-size:200%;">
            <sup><p style = "color:rgb(204, 30, 30)"> "paragraph"     <q>here</q> </p></sup>
        </pre>

        <p style = "font-size:30px;" id = "list3"><a href = "#link">
            <strong> this is a strong text </strong><br>
            <em> this is an emphasized text </em><br>
            <mark> this is a marked text</mark><br>
            <small> this is a small text</small><br>
            <del> this is a deleted text</del><br>
            <ins> this is an inserted text</ins><br>
            <sub>subscript </sub> normal <sup> superscript</sup><br>
            <abbr title = "Fear of Missing Out"> FOMO </abbr>
        
        </a></p>

        <bdo dir = "rtl"> <cite> write this sentence backwards </cite></bdo>
        <!-- this is a comment --> <br>
        <a href = "new.html">Return to top</a>
        
    </body>





body {background-color:rgb(255, 208, 208);
      border: 5px solid rgb(244, 119, 96);
      margin: 0px;
      padding: 5px;}

p {color: maroon; 
    border: 5px solid rgb(252, 199, 102);
    padding: 10px;
    margin: 50px;
    text-align:center;
    font-size:large;
}

h1 {color: darkgreen;
    margin: 5px;
    display: inline-block;
    }

pre {background-color:aquamarine; 
        font-family:'Times New Roman', Times, serif;}
hr {color: teal;
    font-size: 100px;}

img {border: 5px solid lightgreen;
     margin: 50px;}
    
button {font-size:large;}

ol, ul {margin: 10px;
        font-size: larger;}

a:link {color: rgb(26, 190, 190);
        background-color: transparent;
        text-decoration: none;}

a:visited {color: tomato;
           background-color: transparent;
           text-decoration: none;}

a:hover {color: rgb(241, 68, 97);
         background-color: transparent;
         text-decoration: underline;}

a:active {color: yellow;
          background-color: transparent;
          text-decoration: underline;
          font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif}


          
