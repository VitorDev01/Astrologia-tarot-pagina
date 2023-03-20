<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title></title>
    <style>
        * {
           margin: 0;
           padding: 0;
           box-sizing: border-box;
        }

        body {
           font-family: 'times';
           font-size: 16px;
        }

        header {
           width: 100%;
           height: 750px;
           background-image: url(Skewed1.png);
           background-attachment: fixed;
           background-position: center;
           background-size: cover;
           position: relative;
           overflow: hidden;
           color: #fff;
           text-align: center;
        }

        header .textos {
           margin-top: 152px;
        }
        
        header .titulo {
           font-size: 40px;
        }
        
        header .subtitulo {
           font-size: 42px;
           font-weight: 300;
           margin-bottom: 32px;
        }

        header .boton {
           display: inline-block;
           padding: 6px;
           width: 128px;
           border: 1px solid #fff;
           color: #fff;
           font-size: 19px;
           text-align: center;
           text-decoration: none;
           border-radius: 16px;
        }

        .sesgoabajo {
           z-index: 10;
           position: absolute;
           bottom: 0;
           left: 0;
           border-width: 0 0 45vh 100vw;
           border-style: solid;
           border-color: transparent transparent #fff transparent;
        }
        
        .sesgoarriba {
           z-index: 10;
           position: absolute;
           top: 0;
           left: 0;
           border-width: 35vh 100vw 0 0;
           border-style: solid;
           border-color: #fff transparent transparent transparent;
        }

        .contenedor {
            width: 90%;
            max-width: 1000px;
            margin: auto;
            overflow: hidden;
            padding: 52px 0;
        }
        
        
        .sobre-nosotros {
            text-align: center;
            font-size: 56px;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        .slogan {
            font-size: 24px;
            font-weight: 300;
            text-align: center;
            margin-bottom: 24px;
        }
        
        .parrafo {
            margin-bottom: 13px;
            font-weight: 300;
            text-align: justify;
            line-height: 24px;
            color: rgb(24, 16, 16);
        }
        
        .acerca-de .boton {
            display: inline-block;
            padding: 6px;
            width: 128px;
            font-weight: 300;
            border: 1px solid rgba(24, 16, 16, .7);
            color: rgb(24, 16, 16);
            font-size: 16px;
            text-align: center;
            text-decoration: none;
            border-radius: 16px;
            margin-top: 24px;
        }
        
        
        .encima h2 {
            position: relative;
            top: 45%;
            text-align: center;
            color: #fff;
        }
        
        .encima div {
            position: relative;
            display: block;
            top: 46%;
            width: 40px;
            height: 5px;
            background: #fff;
            margin: auto;
        }
        
        .fondo {
            height: 900px;
            position: relative;
            background-image: url(fondo.png);
            overflow: hidden;
            background-attachment: fixed;
            background-position: center;
            padding-top: 130px;
        }
        
        .sesgoabajo-unico {
            z-index: 10;
            position: absolute;
            bottom: 0;
            left: 0;
            border-width: 0 0 35vh 100vw;
            border-style: solid;
            border-color: transparent transparent #2c3e50 transparent;
        }
        
        
        form {
            display: flex;
            width: 100%;
            justify-content: space-between;
            flex-wrap: wrap;
            margin: auto;
        }
        
        
        @media screen and (max-width:610px) {
            header .textos {
                margin-top: 140px;
            }
        
            header .titulo {
                font-size: 40px;
                
            }
        
            .none {
                display: none
            }
        
            .imagenes {
                flex-grow: 1;
            }
        
            .card {
                width: 90%;
            }
        
            .fondo {
                height: auto;
            }
        
            .especial {
                display: none;
            }
        
            .cliente {
                width: 90%;
                height: 200px;
                margin-bottom: 50px;
            }
        }
        
        @media screen and (max-width:380px) {
            header .textos {
                margin-top: 100px;
            }
        
            header .titulo {
                font-size: 65px;
            }
        
            header .subtitulo {
                font-size: 25px;
                margin-bottom: 32px;
            }
        
            .sobre-nosotros {
                font-size: 46px;
            }
        
            .slogan {
                font-size: 20px;
            }
        
            .titulo-patrocinadores {
                font-size: 46px;
            }
        
            .subtitulo-patrocinadores {
                font-size: 20px;
            }
        }  
        
    </style>
</head>
<body>
    <header>
        <div class="textos">
            <h1 class="titulo">Vitor Oliveira</h1>
            <h3 class="subtitulo">Astrologia & Tarot</h3>
            <a href="#" class="boton">Contato</a>
        </div>
        <div class="sesgoabajo"></div>
    </header>
    <main>
        <section class="acerca-de">
            <div class="contenedor">
                <h2 class="sobre-nosotros">Sobre</h2>
                <h3 class="slogan">Tarot</h3>
                <p class="parrafo">Estudando e praticando tarot a mais de um ano  venho me empenhando em ajudar as pessoas com este oráculo, não uso nenhuma religião neste trabalho como muitos fazem pra dar um ar a mais de misticismo por que as coisas são mais práticas do que parecem, conselhos amorosos, decisões difíceis de serem tomadas, saio desse emprego? será que a pessoa com quem estou me relacionando realmente gosta de min? isso entre muitas outras coisas o tarot responde,<strong> frisando aqui que o livre arbítrio é de cada um e cabe a você escolher oque fazer independente do que as cartas dizem.</strong></p>
                <br>
                <h3 class="slogan">Astrologia</h3>
               
                <p class="parrafo">O Mapa Astral de revolução solar é com o qual trabalho que costuma levar em média uma semana para ser analisado completamente, o mapa da revolução indica as coisas que iram acontecer no seu próximo ano pessoal que começa na seu aniversário e vai até o próximo no ano seguinte, para este serviço é necessário <b>data de nascimento, hora de nascimento ( Exata ) e cidade de nascimento.</b></p>
                <br>
                  <h3 class="slogan">Preços</h3>
                 <p class="parrafo">Um dos motivos do meu interesse em aprender Astrologia e Tarot foram os preços exagerados que muitos oferecem na internet, por isso decidi aprender e oferecer para as pessoas de uma forma mais acessível, as consultas de Tarot em geral custam em torno de <b>R$70,00</b>, já a leitura do mapa astral completa <b>R$250,00</b>, e a leitura de um assunto específico do mapa por <b>R$80</b>, O atendimento único é  on-line, presencialmente apenas se morar na mesma região que eu. Para mais informações entre em contato, disponível no início da página.</p>
            </div>
        </section>
    </main>
</body>
</html>
