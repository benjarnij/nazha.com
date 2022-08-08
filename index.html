<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Ajout</title>
  </head>
  <body class="container">
  <div>
            <header class="header">
                <div>
                    <h1 class="titre">mon application de gestion des ventes</h1>

                </div>
                <div>

                </div>
                <nav class="navbar">
                    <a href="http://127.0.0.1/tp3_g1/www.accueil.com">Acceuille</a>
                    <a class="active" href="http://127.0.0.1/tp3_g1/www.acture.com">Facture</a>
                    <a href="http://127.0.0.1/tp3_g1/www.commnde.com">Commande</a>
                    <a href="http://127.0.0.1/tp3_g1/www.client.com">Client</a>
                </nav>

            </header>
</div>
  <h1>Inscription</h1>
      <section class="section">
        <form action="<?php echo $_SERVER["PHP_SELF"] ?>" name="inscription_form" method="post">
            <h2>Ajout d'un client</h2>
        <fieldset>
                <legend>Identité du client</legend>
              <label>Nom : </label>
              <input name="nom" type="text" maxlength="15" size="16" placeholder="Entrez votre nom" />
              <label>Prénom : </label>
              <input name="prenom" type="text" maxlength="15" size="16" placeholder="Entrez votre prénom" /><br><br><br>
              <label> Cellulaire/Télephone: </label>
              <input name="tel" type="text" maxlength="25" size="16" placeholder="Cellulaire/Télephone" />
              <label>Adresse </label>
              <input type="texte" name="adresse" placeholder="Votre adresse"/>
            <div>
              <label for="">Recherche google </label>
            <input type="search"  maxlength="25" size="16"   >
            <input type="submit" value="Envoyer">
            </div>
            </fieldset>
            <div class="bouttom"> 
              <input type="submit" value="S'enregistrer" /> <input type="reset" value="Réinitialiser" />
            </div>
        </form>

</section>





    <?php 
      $bd = new PDO("mysql:server=localhost;dbname=tp4",'root','');
      $bd->query("SET NAMES 'utf8'");
      $bd->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);

      if (isset($_POST["nom"]) && isset($_POST["prenom"]) && isset($_POST["adresse"]) && isset($_POST["tel"])) {
            $requete = $bd->prepare("INSERT INTO client(nom, prenom,adresse,tel) VALUES (?, ?, ?, ?)"); 
            $requete->bindValue(1,$_POST['nom']); $requete->bindValue(2,$_POST['prenom']);
            $requete->bindValue(3,$_POST['adresse']); $requete->bindValue(4,$_POST['tel']);
            $requete->execute();
      }
      $requete2 = $bd->prepare("SELECT num, nom,prenom,adresse,tel FROM client");
      $requete2->execute();
      $client = $requete2->fetchAll(PDO::FETCH_ASSOC);
    ?>
    <main class="main">
      <h1>Liste des clients</h1>
      <section>        
        <table>
          <thead>
            <tr>
              <th>num</th><th>Nom</th><th>Prénom</th><th>Adresse</th><th>tel</th>
            </tr>        
          </thead>
          <tbody>
          <?php
                foreach ($client as $ligne) {
                  echo "<tr>";
                  foreach ($ligne as $key=>$cel) {
                    
                      echo "<td>$cel</td>";
                   
                  }
                  echo "</tr>";
                }
              ?>
          </tbody>
        </table> 
      </section>
      
    </main>
    
  </body>
  <style>
        .container{
     max-width: 700px;
     min-height: 2000px;
     background-color: antiquewhite;
     margin: auto;
     padding: 10px;


}
   .header{
     display: flex;
     flex-direction: row;
     flex-wrap: wrap;
     background-color: antiquewhite;
     color: brown;
     padding: 15px 0 0 0;
     

}
.logo{
     width: 120px;
     margin-top: auto;
     margin-bottom: auto;
     padding: 10px;

}
.titre{
     margin:auto;
     text-align: center;
     flex: auto;
     position:sticky;
     top:0;

}
.navbar{
     display: flex;
     background-color: rgb(211, 112, 112);
     flex: 100%;
     padding: 20px 20px ;
     flex-wrap: wrap;
     justify-content: center;
     

}
.navbar a{
     text-decoration: blink;
     color: black;
     font-weight: bold;
     padding: 5px;
}
.navbar a:hover , .navbar >.active{
     text-decoration: underline;
     background-color: antiquewhite;
}
.section{
    padding:20px;
    margin: 40px;
}
input[type="submit"],input[type="reset"]{
     text-align: center;
}
form input::placeholder {
     font-style: italic;
     text-align: center;
   
}
label{
     font-style: oblique;
     color: rgb(59, 4, 4);
     font-weight: bold;
     padding-bottom: 50px;
}
.section form .bouttom{
     text-align: center;
     padding: 15px;
     flex: 100%;
     background-color: brown;
     color: black;
}
fieldset{
     border-width:2px ;
     border-radius: 5px;
     border-color: rgb(87, 28, 184);
     border-style: solid;
}
h2{
        color:#650e91;
        margin-bottom: 2px;
      }
      th, td{
        border: solid;
        padding: 5px;
        border-color:#0ee; 
        border-width:2px
      }
      table{
        border-collapse: collapse;
        width: 100%
      }
      thead tr{background-color:#365D88; color:white}
      tbody tr:nth-child(2n+1){background-color:#6cfbf9; color:black}
      tbody tr:nth-child(2n){background-color:#229190; color:white}
  </style>
</html>
