<!DOCTYPE html>
<html lang="bg" dir="ltr">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>SPORT BG</title>
    	<link rel="stylesheet" href="Style.css"/>
    </head>
    <body>
      	<header class="mainHeader">
            <nav class="main-navigation">
                <ul>
                    <li class="active"><a href="#">Начало</a></li>
                    <li><a href="CatalogMen.htm">МЪЖЕ</a></li>
                    <li><a href="CatalogWomen.htm">ЖЕНИ</a></li>
                    <li><a href="CatalogSports.htm">СПОРТОВЕ</a></li>
                    <li><a href="CatalogBrands.htm">МАРКИ</a></li>
                </ul>
            </nav>
      	</header>
        <div class="Header">
                <h1 class="Title">МАГАЗИН ЗА СПОРТНИ СТОКИ</h1>
        </div>
    	<div class="mainContent">
    		<div class="Content">
                <article class="One">
                    <header>
    					<h2><a href="#" title="First post">СП</a></h2>
    				</header>
            <div class="Firstcontainer">
              <div class="container">
                <img src="img\23.jpg" alt="Running" class="image">
                <div class="middle">
                  <a href="CatalogSports.htm">Бягане</a>
                </div>
              </div>
              <div class="container">
                <img src="img\21.jpg" alt="Training" class="image">
                <div class="middle">
                  <a href="CatalogSports.htm">Тренировка</a>
                </div>
              </div>
              <div class="container">
                <img src="img\35.jpg" alt="Swimming" class="image">
                <div class="middle">
                  <a href="CatalogSports.htm">Плуване</a>
                </div>
              </div>
              <div class="container">
                <img src="img\7.jpg" alt="Football" class="image">
                <div class="middle">
                  <a href="CatalogSports.htm">Футбол</a>
                </div>
              </div>
              <div class="container">
                <img src="img\18.jpg" alt="Cycling" class="image">
                <div class="middle">
                  <a href="CatalogSports.htm">Колоездене</a>
                </div>
              </div>
            </div>

                <!-- <li><a href="CatalogSports.htm">Вижте още спортове</a></li> --->

                </article>
                <article class="Two">
                    <header>
    					<h2><a href="#" title="Second post">Промоции</a></h2>
    				</header>
    					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                </article>
                <article class="Three">
                    <header>
    					<h2><a href="#" title="Second post">Избрани продукти</a></h2>
    				</header>
    					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                </article>
                <article class="Four">
                    <header>
    					<h2><a href="#" title="Second post">Нова колекция Есен - Зима 2018</a></h2>
    				</header>
    					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                </article>
                <article class="Five">
                    <header>
    					<h2><a href="#" title="Second post">Марки</a></h2>
    				</header>
                    <ul>
                        <li>Champion</li>
                        <li>Reebok</li>
                        <li>Adidas</li>
                        <li>Puma</li>
                        <li>Nike</li>
                        <li><a href="CatalogBrands.htm">Вижте още марки</a></li>
                    </ul>
                </article>
                <article class="Six">
                  <header>
    					             <h2><a href="#" title="Second post">Актуално за сезона</a></h2>
                  </header>
                          <p id="demo">JavaScript can change HTML element.</p>
                          <button type="button" name="button" onclick="ChangeText()">Change Text</button>
                          <p id="style">JavaScript can change the style of an element.</p>
                          <button type="button" name="button" onclick="ChangeStyle()">Change Style</button>


                          <input id="number">
                          <button type="button" name="button" onclick="numberValidation()">Submit</button>
                          <p id="num"></p>
                </article>
    		</div>
    	</div>
    	<footer class="mainFooter">
          <p>2018 All Rights Recived</p>
          <a href="#">Guides</a>
          <a href="#">Terms of Use</a>
          <a href="#">Terms of Sale</a>
          <a href="#">Privacy & Cookie Policy</a>
          <a href="#">Cookie Settings</a>
    	</footer>
      <script>
          function ChangeText() {
              document.getElementById("demo").innerHTML = "Hello World";
          }
          function ChangeStyle() {
            for (var i = 0; i < 100; i++) {
              document.getElementById("style").style.fontSize="50px"+i;
            }
          }


          function numberValidation() {
              var x, text;
              x = document.getElementById("number").value;
              if (x<1||x>10) {
                  text= "Input not valid";
              }
              else {
                text = "Input valid";
              }
              document.getElementById("num").innerHTML=text;
          }
      </script>
    </body>
</html>
