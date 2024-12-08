# new-intern
repository
<html>
    <head>
      <!-- <link rel="stylesheet" href="cal.css">-->
       <style>

       *{
            margin:0;
            padding:0px;
            box-sizing: border-box;
            font-family:Arial, Helvetica, sans-serif;
            user-select:none;
        }
        body{
            height:100vh;
            background:#240046;
            display:grid;
        }
        .container{
            width:100%;

            height:100%;

            display:flex;
        }
        .calculator{
            background: #023e7d;
            padding:10px;
            box-shadow:0px 0px 10px 3px rgba(0,0,0,0.219);
            margin:auto;
            border-radius:10px;

        }
        .calculator form input{
            border:0;
            outline:0;
            width:60px;
            height:60px;
            border-radius:10px;
            font-family:Nunito;
            font-weight:700;
            font-size:1.7em;
            color:red;
            cursor:pointer;
            margin:10px;
        }
        .calculator form input numpadtns{
            background:#012a4a;

        }
        form.display{
            display:flex;
            justify-content:flex-end;
            margin:20px 0;
            
        }
        form .display input{
            text-align:right;
            font-family:serif;
            flex:2;
            font-size:45px;
            padding:62px  151px;
            box-sizing:border-box;
            background:#218380;
            box-shadow:0 0 10px 3px #00000033;
            height:80px;
            color:blue;
        }
        form input .equal{
            width:145px;
            background:#005f08;

        }
        form input.ac,form input.del{
            background-color:#5f0000;

        }
        .symbols{
            background-color:#edae49;
        }
        .special{
            background:#248277;
        }
        .calculator form input:hover{
            box-shadow:0px 0px 5px 3px #00000025;
        }
        
        </style>
    </head>
    <body>
        <div class="container">
            <div class="calculator">
                <form>
                    <div class="display">
                        <input type="text" >
                    </div>
                    <div>
                        <input type="button" value="ac" onclick="display.value=''" class="ac">
                        <input type="button" class="del" value="del" onclick="display.value=display.value.tostring().slice(0,-1)">
                        <input type="button" class="symbols" value="."onclick="display.value+='.'">
                        <input type="button" class="symbols" value="/"onclick="display.value+='/'">
                    </div>
                    <div>
                        <input type="button" class="numpadbtns" value="7" onclick="display.value+='7'">
                        <input type="button" class="numpadbtns" value="8" onclick="display.value+='8'">
                        <input type="button" class="numpadbtns" value="9" onclick="display.value+='9'">
                        <input type="button" class="symbols" value="*" onclick="display.value+='*'">
                    </div>
                    <div>
                        <input type="button" class="numpadbtns" value="4" onclick="display.value+='4'">
                        <input type="button" class="numpadbtns" value="5" onclick="display.value+='5'">
                        <input type="button" class="numpadbtns" value="6" onclick="display.value+='6'">
                        <input type="button" class="symbols" value="-" onclick="display.value+='-'">
                    </div>
                    <div>
                        <input type="button" class="numpadbtns" value="1" onclick="display.value+='1'">
                        <input type="button" class="numpadbtns" value="2" onclick="display.value+='2'">
                        <input type="button" class="numpadbtns" value="3" onclick="display.value+='3'">
                        <input type="button" class="symbols" value="+" onclick="display.value+='+'">
                    </div>
                    <div>
                        <input type="button" class="special" value="00" onclick="display.value+='00'">
                        <input type="button" class="special" value="0" onclick="display.value+='0'">
                        <input type="button"  value="=" onclick="display.value=eval(display.value)" class="equal">
                    </div>
                </form>
        </div>
    </div>
