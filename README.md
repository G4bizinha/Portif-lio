﻿# Meu-Portif-lio
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Meu Portifolio</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel="stylesheet" type="text/css" href="MeuEstilo.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="icon" type="image/x-icon" href="/images/images.png">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&display=swap" rel="stylesheet">

</head>
<body class="Portifolio">
    <div class="roboto-medium">
     <div class="lable"> 
        <div>
            <img src="https://media.licdn.com/dms/image/C4D03AQF8YoIl85I41A/profile-displayphoto-shrink_200_200/0/1652819792513?e=1715212800&v=beta&t=7amsA6wWbQd6BOGdwbvpjDvnmes7rX-nnmIB5TyLsVU"
            class="profile-img">
        </div>
        <div class="profile-info mt-5">
            <H1 class="dancing-script">Gabriela Von Borowski Ben</H1>
            <h2 class="dancing-script">Jr. developer </h2>
        </div>
     </div>
        

        <div class= "lable mt-1 lable3 cor2">
            <h3 class= "lable1">Idade (Age):</h3>
            <h3 class= "lable2">21</h3>
        </div>
        <hr>
        <div class= "lable mt-1 lable3 cor2">
            <h3 class= "lable1">Cidade(City):</h3>
            <h3 class= "lable2">Viamão-RS</h3>
        </div>
        <hr/>
        <div class= "lable mt-1 lable3 cor2">
            <h3 class= "lable1">Graduação (Graduation):</h3>
            <h3 class= "lable2">Ciência da Computação (Computer Science)</h3>
        </div>
        <hr>
        <div class= "lable mt-1 lable3 cor2">
            <h3 class= "lable1">Período da Graduação (Period of Graduation):</h3>
            <h3 class= "lable2">6</h3>
        </div>
        <hr>
            <div>
                <h3 class= "lable1 mt-1 lable3 cor collapsible">Certificações (Certifications):</h3>     
                    <ul class= "lable3 cor3 content">
                    <li><h3 class="lable2">Escola e Faculdades QI - Informática - Básico (Basic Informatic)</h3></li>
                    <li><h3 class="lable2">CISCO - CyberSecurity Essentials</h3></li>
                    <li><h3 class="lable2">CISCO - CyberOps</h3></li>
                    <li><h3 class="lable2">IFRS - Inglês Básico (Basic English)</h3></li>
                    <li><h3 class="lable2">IFRS - Inglês Intermediário (Medium English)</h3></li>
                    <li><h3 class="lable2">IFRS - Espanhol Básico (Basic Spanish)</h3></li>
                    <li><h3 class="lable2">IFRS - Libras</h3></li>
                  </ul>
            </div>
            <hr>
            <div>
                <h3 class= "lable1 mt-1 lable3 cor collapsible">Minhas Experiências Profissionais (My Professional Experiences):</h3>
                        <ul class="lable3 cor3 content">
                        <li><h3 class="lable2">Manutenção de Hardware trabalhando como estagiária no Departamento de Informática da Brigada Militar-RS</h3></li>
                        <li><h3 class="lable2">Suporte Técnico estagiando na Secretária de Sistema Penal e Socioeducativo (SSPS) no Centro Administrativo Fernando Ferrari (CAFF)</h3></li>
                        </ul>
            </div>
            <hr>
            <div>
            <h3 class= "lable1 mt-1 lable3 cor collapsible">Linguagens de Programação e Ferramentas (Program Language and Tools):</h3>
              <div class="mt-1 cor3 content">
                <ul>
                <li><img height="35" width="35" src="https://cdn.simpleicons.org/c" /></li>
                <hr>
                <li><img height="35" width="35" src="https://cdn.simpleicons.org/c++" /></li>
                <hr>
                <li><img height="35" width="35" src="https://cdn.simpleicons.org/Mysql" /></li>
                <hr>
                <li><img height="35" width="35" src="https://cdn.simpleicons.org/postgresql" /></li>
                <hr>
                <li><img height="35" width="35" src="https://cdn.simpleicons.org/firebase" /></li>
                <hr>
                <li><img height="35" width="35" src="https://cdn.simpleicons.org/mongodb" /></li>
                <hr>
                <li><img height="35" width="35" src="https://cdn.simpleicons.org/visualstudiocode" /></li>
            </ul>
              </div>
            </div>
              <hr>
            <h4 style="font-style: italic;">~ Come get connect with me ~</h4>
            <a href="https://www.linkedin.com/in/gabriela-von-borowski-ben/">
                <img height="32" width="32" src="https://cdn.simpleicons.org/linkedin" />
            </a> 
        </div>
    </div>
    <script>
        var coll = document.getElementsByClassName("collapsible");
        var i;
        
        for (i = 0; i < coll.length; i++) {
          coll[i].addEventListener("click", function() {
            this.classList.toggle("active");
            var content = this.nextElementSibling;
            if (content.style.display === "block") {
              content.style.display = "none";
            } else {
              content.style.display = "block";
            }
          });
        }
        </script>
    </body>
</html>

