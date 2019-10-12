
<html lang="fr">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Wild Campus Tours</title>
    <link rel="icon" type="image/png" href="favicon.png">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://unpkg.com/bulma@0.7.5/css/bulma.min.css" />
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="style2.css">
    <link rel="stylesheet" type="text/css" href="bootstrap.min.css">
</head>
<!--<a href="https://icons8.com/icon/42201/en-cours">En cours icon by Icons8</a>-->

<body>
    <header>


        <nav class="navbar navbar-expand-lg bg-white">
            <div class="navbar-brand">
                <a class="navbar-item" href="#">
                    <img src="img/logo.png" alt="Logo">
                </a>
            </div>

            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarColor01" aria-controls="navbarColor01" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon">
                    <img src="https://img.icons8.com/ios/50/000000/hamburger.png">
                </span>
            </button>

            <div class="collapse navbar-collapse" id="navbarColor01">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="index.html">Accueil <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="formation.html">Formation</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="outils.html">Outils</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
                <form class="form-inline my-2 my-lg-0" data-children-count="1">
                    <input class="form-control mr-sm-2" type="text" placeholder="Rechercher">
                    <button class="btn btn-secondary my-2 my-sm-0" type="submit">Go</button>
                </form>
            </div>
        </nav>

    </header>

    <!-- introduction -->

    <section class="container-fluid intro">
        <div class="col-12">
            <h1>La vie sur le Campus de Tours</h1>
            <h2>Intégration d'un Wilder</h2>
        </div>

    </section>

    <!-- Présentation de la MAME -->

    <section class="container-fluid prez">

        <div class="row">
            <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
                <img src="img/mame.jpg" alt="Mame" id="mame">
            </div>
        </div>
        <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 campus">
            <h2 class="mt-4">Un Campus au sein de la French Tech Loire Valley</h2>
        </div>

    </section>
    
    <!-- Presentation de la wcs -->

    <section>
<div class="container  my-4">
        <div class="row">
           <div class="col-md-12 col-lg-4">
          
                <img  src="img/ecosysteme_numerique.jpg" alt="écosystème numérique" id="ecosystem">
                <p class="mt-4">Une formation au coeur d'un écosystème numérique</p>
           
            </div>
  
            <div class="col-md-12 col-lg-4">
                <img src="img/insertion.jpg" alt="insertion professionnelle">
                <p>Un fort taux d'insertion professionnelle (90%)</p>
            </div>

            <div class="col-md-12 col-lg-4">
                <img src="img/locaux.jpg" alt="locaux">
                <p>Une formation en présentiel de 5 mois + 2 à 3 mois en entreprise</p>
            </div>
        </div>
        </div>
    </section>

    <!-- slider -->
    <h2 class="my-5">Bienvenue à la Wild Code School</h2>

    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" ></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner card">
          <div class="carousel-item active">
             
            <img class="d-block w-100 card-img" src="img/Wild.jpg" alt="First slide">
           <div class="card-img-overlay">
                <p class="card-title h2  mx-5 "> Wild</p>
           </div>
          </div>
          <div class="carousel-item ">
                
            <img class="d-block w-100 card-img" src="img/code.jpg" alt="Second slide">
            <div class="card-img-overlay">
                    <p class="card-title h2  mx-5 "> Code</p>
               </div>
          </div>
          <div class="carousel-item ">
                
            <img class="d-block w-100 card-img" src="img/school.jpg" alt="Third slide">
            <div class="card-img-overlay">
                    <p class="card-title h2  mx-5"> School</p>
               </div>
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>

 <!-- Témoignages de wilders -->
   <div class="container testimonials mt-5">

       <h3 id="texttestimonials mt-5">Témoignage de Wilders</h3>
       <div class="row">
           <div class="col-12 col-md-6 col-lg-6 avatar">
               <img src="img/Leidi.jpg" alt="">
               <p>La première semaine,  je n'ai pas dormi, je ne suis pas sorti, je n'ai pas mangé. Je suis un vrai zombie, mais j'aime ça !</p>
           </div>
           <div class="col-12 col-md-6 col-lg-6 avatar">
               <img src="img/Chaihine.JPG" alt="Chaihine">
               <p>Je pense qu’ici personne ne vient à reculons. Je suis ravi d’avoir intégré la WCS, une ecole innovante !</p>
           </div>
       </div>
       <div class="row">

           <div class="col-12 col-md-6 col-lg-6 avatar">
               <img src="img/Tim.jpg" alt="Tim">
               <p>Passer de l’élevage de penguin à la Wild Code School c’est intense mais ça en vaut la peine.</p>
           </div>
            <div class="col-12 col-md-6 col-lg-6 avatar">
               <img src="img/Arsene.png" alt="Arsene">
               <p>La WCS le plaisir d’apprendre à coder</p>
           </div>
       </div>
   </div>


    <footer class="navbar-footer">

        <a href="index.html">Accueil</a>
        <a href="formation.html">Formation</a>
        <a href="outils.html">Outils</a>
        <a href="contact.html">Contact</a>
        <a href="mentions.html">Mentions légales</a>
    </footer>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>

</html>
