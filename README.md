# TpQuiEstCe

Quiestce.php

<html>
    <head>
        <meta charset="utf-8">
        <link rel="stylesheet" href="quiestce.css">
    </head>

    <body>

<table>
    <tr>
        <td><img src="images/0.jpg"></td>
        <td><img src="images/1.jpg"></td>
        <td><img src="images/2.jpg"></td>
        <td><img src="images/3.jpg"></td>
    </tr>
    <tr>
        <td><img src="images/4.jpg"></td>
        <td><img src="images/5.jpg"></td>
        <td><img src="images/6.jpg"></td>
        <td><img src="images/7.jpg"></td>
    </tr>
    <tr>
        <td><img src="images/8.jpg"></td>
        <td><img src="images/9.jpg"></td>
        <td><img src="images/10.jpg"></td>
        <td><img src="images/11.jpg"></td>
    </tr>
    <tr>
        <td><img src="images/12.jpg"></td>
        <td><img src="images/13.jpg"></td>
        <td><img src="images/14.jpg"></td>
        <td><img src="images/15.jpg"></td>
    </tr>

</table>


        <h2 id="q1"><u>1/ A-t-il des lunettes ?</u></h2>
        <input id="b1O" type="button" value="Oui" onclick="oui(0)">
        <input id="b1N" type="button" value="Non" onclick="non(0)"><br><br>

        <h2 id="q2"><u>2/ A-t-il une moustache ?</u></h2>
        <input id="b2O" type="button" value="Oui" onclick="oui(1)">
        <input id="b2N" type="button" value="Non" onclick="non(1)"><br><br>

        <h2 id="q3"><u>3/ A-t-il un chapeau ?</u></h2>
        <input id="b3O" type="button" value="Oui" onclick="oui(2)">
        <input id="b3N" type="button" value="Non" onclick="non(2)"><br><br>

        <h2 id="q4"><u>4/ A-t-il des cheveux ?</u></h2>
        <input id="b4O" type="button" value="Oui" onclick="oui(3)">
        <input id="b4N" type="button" value="Non" onclick="non(3)"><br><br>

        <h2 id="q5"><u>5/ A-t-il une boucle d'oreille ?</u></h2>
        <input id="b5O" type="button" value="Oui" onclick="oui(4)">
        <input id="b5N" type="button" value="Non" onclick="non(4)"><br><br>

        <h2 id="q6"><u>6/ A-t-il une barbe ?</u></h2>
        <input id="b6O" type="button" value="Oui" onclick="oui(5)">
        <input id="b6N" type="button" value="Non" onclick="non(5)"><br><br>

        <h2 id="q7"><u>7/ A-t-il un noeud papillon ?</u></h2>
        <input id="b7O" type="button" value="Oui" onclick="oui(6)">
        <input id="b7N" type="button" value="Non" onclick="non(6)"><br><br>

        <input id="reponse" type="submit" value="Cliquez pour avoir la réponse">

        <input id="rejouer" type="submit" value="Cliquez pour rejouer">

        
        

    </body>
</html>

quiestce.css

h2{
    font-family: Apple Chancery, cursive;
}

input[type="button"]{
        display: inline-block;
        background-color: #e91313;
        border-radius: 5px;
        border: 4px double #cccccc;
        color: #eeeeee;
        text-align: center;
        font-size: 18px;
        padding: 10px;
        width: 100px;
        -webkit-transition: all 0.5s;
        -moz-transition: all 0.5s;
        -o-transition: all 0.5s;
        transition: all 0.5s;
        cursor: pointer;
        margin: 5px;
}

input[type="button"]:hover{
    color: black;
}

input[type="submit"]{
    display: inline-block;
        background-color: #9b13e9;
        border-radius: 5px;
        border: 4px double #cccccc;
        color: #eeeeee;
        text-align: center;
        font-size: 18px;
        padding: 10px;
        width: 260px;
        -webkit-transition: all 0.5s;
        -moz-transition: all 0.5s;
        -o-transition: all 0.5s;
        transition: all 0.5s;
        cursor: pointer;
        margin: 10px;
}

input[type="submit"]:hover{
    color: black;
}
