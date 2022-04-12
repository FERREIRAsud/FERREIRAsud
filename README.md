<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" type="text/css" href="index_form.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>
</head>

<body class="fadeIn">
    <div class="align">
        <h1>Welcome to Ecommerce Research</h1>
        <div class="name?">
            <form>
                <p>Whats your name?</p>
                <input type="text" name="name">
            </form>
        </div>

        <div class="GO_ONE">
            <form>
                <!--Quantos anos você tem-->
                <p>How old are you?</p>
                <input type="radio" name="idade" value="18_22">18 a 25 <br>
                <input type="radio" name="idade" value="23_30">25 a 35 <br>
                <input type="radio" name="idade" value="35_75">35 a 75 <br>
            </form>
        </div>

        <div class="GO_TWO">
            <form>
                <!--Qual é o seu departemento-->
                <p>What's your department?</p>
                <input type="radio" name="department" value="department_l">Logistic <br>
                <input type="radio" name="department" value="department_M">Marketing <br>
                <input type="radio" name="department" value="department_O">Ongoing <br>
                <input type="radio" name="department" value="department_b">B2B <br>
            </form>
        </div>

        <div class="GO_TREE">
            <form>
                <!--Quanto tempo está no ecommerce?-->
                <p>How long have you been in ecommerce?</p>
                <input type="radio" name="number" value="-_de_1_ano">+ 1 year<br>
                <input type="radio" name="number" value="+_de_um_ano">- 1 year<br>
            </form><br>
        </div>

        <div class="GO_FOUR">
            <form>
                <!--Qual é o nivel de satifação no ecommerce-->
                Level of Satisfection is Ecommerce? <br> Little satisfied
                <input type="range" name="satisfaction" min="0" max="10"> Very Pleased
            </form><br><br>
        </div>

        <div>
            <form>
                <a class="intro_submit" href="index_intro.html"> SUBMIT </a>
            </form>
        </div><br>
        <div class="intro_ONE">
            <a class="ONE" href="index_intro.html">BACK!</a>
        </div>
    </div>
    </div>
</body>

</html>
