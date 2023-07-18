# Tela_login
Prototipo para tela de login ou cadastro



# Html_pagina_login

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../css/estiloLogin.css">
    <title>login</title>
</head>
<body>
    <div id="principal">
    

            <form id="formulario" action="" method="post">

                <h1 id="titulo">Login</h1>

                <input class="dados" id="email" type="email" name="email" placeholder="Digite seu email:">
                <input class="dados" id="senha" type="password" placeholder="Digite sua senha:">

                <button type="submit" class="dados" id="btn" name="botao">ENTRAR</button>

                <a id="ancora" class="dados" href="pag2.html">Quero me cadastrar...</a>

            </form>

        
    </div>

    <script src="../js/"></script>
</body>
</html>

# Css_tela_login


#principal{
    width: 100%;
    height: 620px;
    display:flex;
    justify-content: left;
    align-items: center;
    background-image: url(../imagens/background.jpg);
    background-size: cover;

}


#formulario{
    border: 1px white solid;
    border-radius: 20px;
    background-color: #F5F1A2;
    padding: 10px;
    margin-left: 10px;
    display:flex;
    flex-direction: column;
    height: 550px;
    width: 500px;
    
}

.dados{
    height:40px;
    border: 1px solid;
    border-radius: 10px;
    margin-top: 20px;
}


#btn{
    height: 45px;
    margin-top: 130px;
    background-color: #69E5F5;
    font-size: 25px;
    color: white;
}
#btn:hover{
    border: 2px solid black;
    color: black;
}

h1{
    background-color: white;
    border: 1px white solid;
    border-radius: 15px;
    text-align: center;
    margin-bottom: 70px;
}

#ancora{
    height: 30px;
    margin-top: 50px;
    margin-left: 339px;
    margin-right: 10px;
    border: 1px solid;
    border-radius: 10px;
    padding: 5px 3px 0px 3px;
    width: 150px;
    background-color: #69E5F5;
    text-align: center;
    text-decoration: none;
    color: white;
}
#ancora:hover{
    border: 2px solid black;
    color: black;
}


@media screen and (min-width: 320px) and (max-width: 498px){
    #principal{
        width: 100%;
        height: 550px;
        display:flex;
        padding: 0px;
        justify-content: center;
        align-items: center;
        background-image: linear-gradient(45deg, #0FF5E7, #F527D4, #13A89F);
        
    
    }
    

    #formulario{
        border: 1px white solid;
        border-radius: 20px;
        background-color: #F5F1A2;
        padding: 10px;
        margin: 0px;
        display:flex;
        flex-direction: column;
        height: 350px;
        width: 260px;
        
    }

    .dados{
        height:20px;
        border: 1px solid;
        border-radius: 10px;
        margin-top: 20px;
    }
    

    #btn{
        height: 35px;
        margin-top: 70px;
        background-color: #69E5F5;
        font-size: 20px;
        color: white;
    }
    #btn:hover{
        border: 2px solid black;
        color: black;
    }
    
    #ancora{
       margin-top: 30px;
       margin-left: 100px;
       height: 20px;
        background-color: #69E5F5;
        text-align: center;
        text-decoration: none;
        color: white;
    }
    #ancora:hover{
        border: 1px solid black;
        color: black;
    }
   
    h1{
        text-align: center;
        margin-bottom: 10px;
    }
}


@media screen and (min-width: 500px) and (max-width: 1024px){
    
    #principal{
        width: 100%;
        height:600px;
        display:flex;
        justify-content: center;
        align-items: center;
        background-image: url(../imagens/background.jpg);
        background-size: cover;
    
    }
    
    
    #formulario{
        border: 1px white solid;
        border-radius: 20px;
        background-color: #F5F1A2;
        padding: 10px;
        display:flex;
        flex-direction: column;
        height: 480px;
        width: 360px;
        
    }

    .dados{
        height:35px;
        border: 1px solid;
        border-radius: 10px;
        margin-top: 20px;
    }
    

    #btn{
        height: 48px;
        margin-top: 100px;
        background-color: #69E5F5;
        font-size: 20px;
        color: white;
    }
    #btn:hover{
        border: 2px solid black;
        color: black;
    }
    
    #ancora{
       margin-top: 40px;
       margin-left: 200px;
       height: 20px;
        background-color: #69E5F5;
        text-align: center;
        text-decoration: none;
        color: white;
    }
    #ancora:hover{
        border: 1px solid black;
        color: black;
    }
   
    h1{
        text-align: center;
        margin-bottom: 60px;
        
    }
}


# Html_pagina_cadastro


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../css/cadastra.css">
    <title>Cadastrar</title>
</head>
<body>


    <main id="main">

        <fieldset id="fiel1"> <legend>Coloque seus dados: </legend>
        
            <form id="pessoal" class="da_cad" action="" method="post">

                <div id="div1">
                    <input class="pessoa" id="nome" type="text" name="nome" placeholder="Digite seu nome:">
                    <input class="pessoa" id="sob_nome" type="text" name="sob_nome" placeholder="Digite seu sobrenome:"><br>
                    <input class="pessoa" id="celular" type="tel" placeholder="Digite seu celular:" name="celular">

                    <br>

                    <label class="labels" id="label_data" for="data">Data de nascimento: </label> <input class="date" id="data" type="date" name="data"><br>

                </div>

                <div id="div2">
                    <label class="labels" for="">Selecione seu sexo:</label><br>
                    <label class="labels" for="masculino">Mascullino</label> <input class="opc" id="masculino" type="radio" name="opcoes" value="m"><br>
                    <label class="labels" for="femeninono">Femenino</label> <input class="opc" id="femeninono" type="radio" name="opcoes" value="f"><br>
                    <label class="labels" for="outros">Outros</label> <input class="opc" id="outros" type="radio" name="opcoes" value="outros"><br>

                </div>

                <div id="div3">
                    <input class="end" id="email" type="email" name="email" placeholder="Digite seu email:"><br>
                    <input class="end" id="senha" type="password" name="senha" placeholder="Digite sua senha:"><br>
                    <input class="end" id="con_senha" type="password" name="senha" placeholder="Confirme sua senha:">
                </div>
                

            </form>
        
        </fieldset>

        <fieldset id="fiel2"><legend>Coloque seu indereço: </legend>
        
            <form id="end" class="da_cad" action="" method="post">

                <label class="labels" for="estados">Selecione seu estado: </label>
                <select class="sele" id="estados">
                    <option value="Rio de Janeiro">RJ</option>
                    <option value="Minas Gerais">MG</option>
                    <option value="São Paulo">SP</option>
                </select>

                    <br>

                <label class="labels" for="cidades">Digite sua cidade: </label>
                <select class="sele" id="cidades">
                    <option value="bh">Belo Horizonte</option>
                    <option value="mc">Mogi das Cruzes</option>
                    <option value="cc">Copa Cabana</option>
                </select>

                <br>

                <input class="end" type="text" id="cep" placeholder="Digite seu cep: "><br>
                <input class="end" type="text" id="end" placeholder="Digite seu endereço: "> <input type="number" value="00" id="num"> <input class="end" type="text"       id="comp" placeholder="Complemento">
                
            </form>
        
        </fieldset>

        <input id="botao" type="button" value="SALVAR">

    </main>

    <br>

    

    <script src="../js/"></script>
</body>
</html>

# Css_tela_cadastrar


#main{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    flex-wrap: wrap;
    background-image: url(../imagens/background.jpg);
    background-size: cover;
}

fieldset{
    margin-top: 20px;
    width: 590px;
    border-radius: 10px;
    background-color: #F5F1A2;
}

.end, .pessoa, .sele, .labels, .date{
    margin: 5px 3px 5px 3px;
}

#div2{
    padding:8px;
}

input, select{
    border: 1px white solid;
    border-radius: 5px;
    padding: 3px 3px;
}

.pessoa, .end{
    width: 50%;
}

#comp{
    width: 83px;
}

#num{
    width: 50px;
}

.opc{
    position:absolute;
    left: 110px
}


#botao{
    font-size: 30px;
    margin: 100px 5px 50px;
    height: 60px;
    width: 100%;
    color: white;
    border: 1px solid white;
    border-radius: 10px;
    background-color: #69E5F5;
}
#botao:hover{
    border: solid 2px black;
    color: black;
}
