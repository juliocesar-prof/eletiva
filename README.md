<!DOCTYPE <html>
<html lang="pt-br">

<style>
@charset "UTF-8";
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
@font-face {
    font-family: idroid;
    src: url(../fontes/idroid.otf);
    font-weight: normal;
}
/*
#c5ebd6
#83e1ad
#3ddc84
#2fa866
#1a5c37
#063d1e
*/


#PROJETO {
    background-color: var(--cor4);
}

:root {
    --cor0: #dbd9b3;
    --cor1: #83e1ad;
    --cor2: #3ddc84;
    --cor3: #2fa866;
    --cor4: #1a5c37;
    --cor5: #063d1e;

    --fonte-padrao: Arial, Verdana, Helvetica, sans-serif;
    --fonte-destaque: "Bebas Neue", cursive;
    --fonte-androif: "idroid", cursive;
}

* { /* determina margin e padding para tudo*/
    margin: 0px;
    padding: 0px;
}

body{
    background-color: var(--cor0);
    font-family: var(--fonte-padrao);
}
a.externo::after {
    content: "\1F517";
}


header {
    background-color: var(--cor4);
    min-height: 150px;
    text-align: center;
    padding-top: 30px;
    background-image: linear-gradient(to bottom, var(--cor3), var(--cor5));
}
header > h1 {
    color: white;
    font-family: var(--fonte-destaque);
    font-size: 3em;
    margin-bottom: 20px;
    text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.5);
    font-weight: normal;
}
header > p {
    font-family: var(--fonte-padrao);
    font-size: 1.2em;
    color: white;
    max-width: 600px;
    padding: 0 10px 0 10px;
    margin: auto;
    text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.5);
}


nav {
    background-color: var(--cor5);
    padding: 10px;
    box-shadow: 0px 7px 9px rgba(0, 0, 0, 0.250);
    text-align: center;
}
nav a {
    color: var(--cor1);
    padding: 10px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px 5px 0 0;
    transition-duration: 0.3s;


}
nav > a:hover {
    background-color: var(--cor3);
    color: var(--cor5);
    font-size: 18px;
}


main {
    min-width: 300px;
    max-width: 1000px;
    margin: auto;
    margin-bottom: 30px;
    padding: 20px;
    background-color: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
    border-radius: 0 0 10px 10px;
}
main img {
    width: 100%;
}
main img.pequena {
    display: block;
    max-width: 400;
    margin: auto;
}
div.video {
    background-color: var(--cor5);
    margin: 0px -20px 30px -20px;
    padding: 20px;
    padding-bottom: 56.60%;
    position: relative;
}
div.video > iframe {
    position: absolute;
    top: 5%;
    left: 5%;
    width: 90%;
    height: 90%;
}

main h1 {
  font-family: var(--fonte-androif);
  color: var(--cor4);
  font-size: 1.3em;
  background-image: linear-gradient(to right, var(--cor1), transparent);
  text-indent: 8px;
  font-weight: normal;
}
main h2 {
    font-family: var(--fonte-androif);
    color: var(--cor4);
    font-size: 1.3em;
    background-image: linear-gradient(to right, var(--cor1), transparent);
    text-indent: 8px;
    font-weight: normal;

}
main h3 {
    font-family: var(--fonte-androif);
    color: var(--cor4);
    font-size: 1.3em;
    background-image: linear-gradient(to right, var(--cor1), transparent);
    text-indent: 8px;
    font-weight: normal;

}
main p {
    margin: 15px 0;
    text-align: justify;
    text-indent: 30px;
    font-size: 1em;
    line-height: 2em;
}
main strong {
    color: var(--cor4);
    font-weight: bold;
    padding: 2px 6px;
}
main a {
    text-decoration: none;
    font-weight: bold;
    color: var(--cor5);
    background-color: var(--cor1);
    padding: 2px 6px;
    border-radius: 5px;
}
main a:hover {
    text-decoration: underline;
    color: var(--cor4);

}


aside {
    background-color: var(--cor1);
    padding: 10px;
    border-radius: 10px;
    box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.37);
}
aside ul {
    list-style-type: "\2714\00A0";
    list-style-position: inside;
    columns: 2;
}
aside li {
    cursor: help;
}
aside h3 {
    background-color: var(--cor4);
    color: white;
    padding: 10px;
    margin: -10 -10 0 -10;
    border-radius: 10px 10px 0 0;
}

footer {
    background-color: var(--cor5);
    color: white;
    text-align: center;
    font-size: 1em;
    padding: 5px;
}
footer a {
    color: white;
    font-weight: bolder;
    text-decoration: none;
}
footer a:hover{
    text-decoration: underline;
    color: var(--cor1);
}

</style>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="estilo/style.css">

    <title>Eletiva de rob??tica</title>

</head>
<body>
    <header>
        <h1>DIY: PROJETANDO E PROGRAMANDO - DESENVOLVIMENTO SUSTENT??VEL</h1>
        <p>Professor J??lio Cesar</p>
    </header>
    <nav>
        <a href="#" id="PROJETO">PROJETO</a>
        <a href="#" id="EQUIPES SUCATAS">EQUIPES SUCATAS</a>
        <a href="#" id="EQUIPES LEGO">EQUIPES LEGO</a>
        <a href="#" id="EQUIPE ARDUINO">EQUIPE ARDUINO</a>
    </nav>
    <main>
        <article>

            <h1>JUSTIFICATIVA</h1>
            <p>A sigla DIY, em ingl??s Do it Yourself (ou fa??a voc?? mesmo, em portugu??s) ?? um conceito bem amplo e, portanto, pode ser aplicado de diversas formas. Atualmente, existem outras correntes que incorporam a ess??ncia do DIY. ?? o caso do Movimento Maker, que tamb??m agrega valores hackers ??? como as diversas licen??as open-source e o ato de compartilhar conhecimento.</p>
              <p>Para acompanhar as demandas dos estudantes das novas gera????es, novos conceitos e metodologias surgem para associar o ensino ?? inova????o. Nesse contexto, a educa????o maker emerge com o grande potencial de engajar os estudantes em atividades de aprendizagem muito diferentes da educa????o tradicional.</p>
              <p>Todos os segmentos da Educa????o B??sica e todas as ??reas de conhecimento podem se apropriar das a????es experimentalistas do movimento maker para potencializar a aprendizagem dos estudantes. Lembrando, aqui, da import??ncia da intencionalidade pedag??gica em todas as pr??ticas realizadas. Ou seja, a implementa????o de pr??ticas maker no projeto pedag??gico n??o pode fugir das exig??ncias curriculares, devendo ser uma combina????o entre teoria e pr??tica.</p>
              <p>O uso de rob??s desempenha papel importante para alcan??ar os objetivos de desenvolvimento sustent??vel estabelecidos pelas Na????es Unidas (17 ODS), que s??o 17 objetivos ambiciosos e interconectados, que abordam os principais desafios de desenvolvimento enfrentados por pessoas no mundo todo. Os Objetivos de Desenvolvimento Sustent??vel s??o um apelo global ?? a????o para acabar com a pobreza, proteger o meio ambiente e o clima e garantir que as pessoas do mundo todo possam desfrutar de paz e de prosperidade. A Federa????o Internacional de Rob??tica (IFR) identificou 13 ODS, em que os rob??s ajudam a criar um planeta melhor.</p>
              <p>O ambiente educacional vem percebendo a necessidade de integrar o uso de tecnologias como ferramenta de ensino em sala de aula. Essa nova integra????o tem despertado nos estudantes uma melhor percep????o e aprendizado, como por exemplo, no ensino de rob??tica onde, os discentes aplicam os conceitos de programa????o, desenvolvem um racioc??nio logico e aprendem inform??tica.</p>
              <p>Esse projeto ?? idealizado para ser executado dentro do Centro de Ensino em Tempo Integral Carlos Drummond de Andrade (CEPI - CDA), localizada no munic??pio de Novo Gama - GO</p>
            <h2>OBJETIVOS</h2>
            <p>OBJETIVO GERAL</p>
Desenvolver projetos atendendo a 13 Objetivos de Desenvolvimento Sustent??veis, utilizando as metodologias e ferramentas apresentadas na capacita????o, convergindo com as pr??ticas realizadas pelo mercado de trabalho.

<p>OBJETIVOS ESPEC??FICOS</p>
Desenvolver a motricidade fina.
Analisar e entender o funcionamento dos mais diversos mecanismos f??sicos
Proporcionar a forma????o de habilidades manuais.
Desenvolver a concentra????o e a observa????o
Motivar a precis??o de seus projetos

            </p>
            <h3>METODOLOGIA</h3>
            <p>Ser??o ministradas aulas de rob??tica, durante as aulas ser??o desenvolvidos os conhecimentos de programa????o no qual utilizaremos a IDE do Arduino para desenvolver os c??digos fonte dos mesmo e ser?? necess??rio o aprimoramento da matem??tica b??sica, eletr??nica b??sica.</p>
          </p>A turma ir?? se dividir em 3 grupos para desenvolverem projetos finais distintos.</p>
<p>Ser??o propostos alguns temas exemplos (irriga????o automatizada, coleta seletiva) que os alunos poder??o ou n??o utilizar.</p>
<p>Os projetos finais ir??o visar desenvolver uma das 13 ODS. Os alunos ir??o propor um tema no qual eles ir??o desenvolver a programa????o (software) e a parte f??sica (hardware) dos projetos que ir??o utilizar os materiais recicl??veis.</p>

            </p>

                        </article>
    </main>
    <footer>
        <p>Website Developed By <a href="https://www.instagram.com/weslleymk1/?hl=pt" target="_blank">Wesley Marques</a>
           & <a href="https://www.instagram.com/julioborges.12/"target="_blank">Professor JC </a>
        </p>
    </footer>
</body>
</html>
