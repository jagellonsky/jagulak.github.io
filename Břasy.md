<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Břasy</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <link rel="stylesheet" href="css.css">
</head>
<body>

    <nav class="navbar navbar-expand-sm bg-primary navbar-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">
            <img src="./img/logo.png" alt="logo">
          </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="collapsibleNavbar">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" href="#obec">o obci</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">akce</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">atrakce</a>
              </li>  
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">pro zájemce</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">úřad</a></li>
                  <li><a class="dropdown-item" href="#">kontakty</a></li>
                  <li><a class="dropdown-item" href="#">formuláře</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>

<div id="o_obci" class="container">
    <div class="row">
        <div class="col-lg-2">
            <h1 id="obec">O obci</h1>
             <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia sequi velit iusto temporibus? Excepturi, temporibus explicabo delectus sequi vel repellendus est porro? Quo officiis est quidem maiores vitae sint quae.</p>
             <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quia sequi velit iusto temporibus? Excepturi, temporibus explicabo delectus sequi vel repellendus est porro? Quo officiis est quidem maiores vitae sint quae.</p>
        </div>
         <div class="col-lg-8">
         <img src="./img/mapa2.png" width="100%">
         </div>
         <div class="col-lg-2">
            <h1>lokace</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit eius, ipsam est debitis nesciunt iusto tempore maxime quod, magni, accusamus nisi. Assumenda voluptate nostrum, dolorum necessitatibus voluptas aspernatur totam dolor?
            </p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit eius, ipsam est debitis nesciunt iusto tempore maxime quod, magni, accusamus nisi. Assumenda voluptate nostrum, dolorum necessitatibus voluptas aspernatur totam dolor?
            </p>
         </div>
    </div>
</div>
<div class="container">
    <div class="row">
        <div class="col-md-2">
            <h1 id="">Kalendář akcí</h1>
            <table>
                <thead>
                    <tr>
                        <th>Po</th>
                        <th>Út</th>
                        <th>St</th>
                        <th>Čt</th>
                        <th>Pá</th>
                        <th>So</th>
                        <th>Ne</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>30</td>
                        <td>31</td>
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                    </tr>
                    <tr>
                        <td>6</td>
                        <td>7</td>
                        <td>8</td>
                        <td>9</td>
                        <td>10</td>
                        <td>11</td>
                        <td>12</td>
                    </tr>
                    <tr>
                        <td>13</td>
                        <td>14</td>
                        <td>15</td>
                        <td>16</td>
                        <td>17</td>
                        <td>18</td>
                        <td>19</td>
                    </tr>
                    <tr>
                        <td>20</td>
                        <td>21</td>
                        <td>22</td>
                        <td>23</td>
                        <td>24</td>
                        <td>25</td>
                        <td>26</td>
                    </tr>
                    <tr>
                        <td>27</td>
                        <td>28</td>
                        <td>29</td>
                        <td>30</td>
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-md-8">
            <div id="demo" class="carousel slide" data-bs-ride="carousel">

                <!-- Indicators/dots -->
                <div class="carousel-indicators">
                <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>
                </div>
                
                <!-- The slideshow/carousel -->
                <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="./img/lom.jpg" alt="lom" class="d-block" style="width:100%;">
                    <div class="carousel-caption">
                    <h3>lom</h3>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="./img/rozhledna.jpg" alt="rozhledna" class="d-block" style="width:100%">
                    <div class="carousel-caption">
                    <h3>rozhledna</h3>
                    </div> 
                </div>
                <div class="carousel-item">
                    <img src="./img/pumptrack.png" alt="pumptrack" class="d-block" style="width:100%">
                    <div class="carousel-caption">
                    <h3>ultramarínka</h3>
                    </div>  
                </div>
                <div class="carousel-item">
                    <img src="./img/foto1.jpg" alt="brasy" class="d-block" style="width:100%">
                    <div class="carousel-caption">
                    <h3>pohled ze shora</h3>
                    </div>  
                </div>
                </div>
                
                <!-- Left and right controls/icons -->
                <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
                <span class="carousel-control-prev-icon"></span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
                <span class="carousel-control-next-icon"></span>
                </button>

            </div>
        </div>

        <div class="col-md-2">
        </div>
    </div>
</div>

<div class="container" id="slide_3">
    <div class="row" id="urad_formular">
        <div class="col-sm-6">
            <h1>Úřad</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptate corporis, tempora, minima tenetur earum officiis facilis ipsum repellat modi fugit quia fugiat reprehenderit deleniti beatae dolore, obcaecati quas dicta! Deleniti?</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam eius nam commodi. Doloribus nemo cumque pariatur, quisquam sequi voluptate repudiandae quidem mollitia! Cupiditate fugit sit soluta voluptatibus iure impedit expedita.</p>
            <img src="./img/urad.png">
        </div>
        <div class="col-sm-6">
            <h1>formulář</h1>
            <form>
                <label for="name">Jméno:</label>
                <input type="text" id="name" name="name"><br><br>
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email"><br><br>
                <label for="phone">Telefon:</label>
                <input type="tel" id="phone" name="phone"><br><br>
                <label for="address">Adresa:</label>
                <input type="text" id="address" name="address"><br><br>
                <label for="city">Město:</label>
                <input type="text" id="city" name="city"><br><br>
                <label for="postcode">PSČ:</label>
                <input type="text" id="postcode" name="postcode"><br><br>
                <label for="type">Typ bydlení:</label>
                <select id="type" name="type">
                    <option value="">Vyberte</option>
                    <option value="byt">Byt</option>
                    <option value="dum">Dům</option>
                    <option value="garsonka">Garsonka</option>
                </select><br><br>
                <label for="message">Zpráva:</label>
                <textarea id="message" name="message"></textarea><br><br>
                <input type="submit" value="Odeslat">
            </form>

        </div>
    </div>
</div>

<div class="mt-12 p-5 bg-primary text-white ">
    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <h2>adresa</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum repudiandae dolorum modi. Eum, sit? Eum esse sequi ut minus ab pariatur ipsum nobis magni vitae, qui, eos, fugiat provident asperiores?
                </p>
                &copy;Václav Jagulák
            </div>
            <div class="col-md-4">
                <h2>kontakt</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minima cumque cupiditate odio laboriosam asperiores doloremque. Inventore temporibus quos fuga magnam iusto necessitatibus aliquam deserunt mollitia ducimus, sit doloribus, quis eveniet!</p>
            </div>
            <div class="col-md-4">
                <h2>úřední hodiny</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet qui voluptas in aliquid, magni asperiores, earum corporis, ducimus suscipit itaque provident dolorem rerum neque error. Fuga consequuntur in dolore blanditiis.</p>
            </div>
        </div>
    </div>
  </div>
    
</body>
</html>
