# INTRODUCTION 
# TITRE
Chapitre 1 ~<a href="https://www.example.com">Cliquez ici pour visiter</a>
<ul>
	  <li>Élément 1</li>
	  <li>Élément 2</li>
	  <li>Élément 3</li>
	</ul>

Chapitre 2 ~<a href="https://www.example.com">Cliquez ici pour visiter</a>
<ul>
	  <li>Élément 1</li>
	  <li>Élément 2</li>
	  <li>Élément 3</li>
	</ul>

Chapitre 3 ~<a href="https://www.example.com">Cliquez ici pour visiter</a>
<ul>
	  <li>Élément 1</li>
	  <li>Élément 2</li>
	  <li>Élément 3</li>
	</ul>

Chapitre 4 ~<a href="https://www.example.com">Cliquez ici pour visiter</a>
<ul>
	  <li>Élément 1</li>
	  <li>Élément 2</li>
	  <li>Élément 3</li>
	</ul>

Chapitre 5 ~<a href="https://www.example.com">Cliquez ici pour visiter</a>
<ul>
	  <li>Élément 1</li>
	  <li>Élément 2</li>
	  <li>Élément 3</li>
	</ul>

# LISTE
# BIENVENUE SUR LE SITE WEB
## FIRST
### Leson 
Styling text
**Bold** ou _Italic_<br>
~~Strikethrough~~<br>
**Bold_and_Italic**<br>
***All texte to bold and italic***<br>
<sub>subscrip</sub><br>
<sup>superscr</sup><br>
<Ins>underline</ins>




# CONCLUSION
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Première Page HTML</title>
  </head>
  <body>
  <h1 style="color: red;">Bienvenue sur ma page web</h1>
	<h2>Titre principale</h2>
	<h3>Sous-titre</h3>
	<style>
    p {
        font-size: 18px;
        color: green;
        font-family:Arial,Sans-Serif
    }
    h2 {
        font-size: 18px;
        color: blue
      
    }
    h3 {
        font-size: 18px;
        color: yellow;
    }
    body {
    background-color: #c5e1a5;
    }
    div {
    border: 2px solid white;
    padding: 20px;
    margin: 10px;
}
button {
    background-color: #4caf50;
    color: white;
    padding: 10px 20px;
    border: 1;
    border-radius: 5px;
    cursor: pointer;
}
tr {text-align: center;}
th {text-align: center;}
</style>
<script>
    console.log("Bonjour, JavaScript !");
</script>
<a href="https://www.example.com">Cliquez ici pour visiter</a>
	
	<img src="IMG_20241118_100050.jpg" alt="Description de l'image" width="300" height="200">
	
	<button onclick="changerCouleur()">Changer la couleur</button>
    <h1 id="paragraphe">Ce texte changera de couleur.</h1>

<script>
function changerCouleur() {
    document.getElementById("paragraphe").style.color = "red";
}
</script>

<script>
function changerCouleur() {
    document.getElementById("paragraphe").style.color = "red";
}
</script>

<script>
function changerCouleur() {
    document.getElementById("paragraphe").style.color = "red";
}
</script>
	<p>Ceci est un paragraphe de texte en ordre.</p>
	<ul>
	  <li>Élément 1</li>
	  <li>Élément 2</li>
	  <li>Élément 3</li>
	</ul>
	<p>Ceci est un paragraphe de texte en desordre.</p>
	<ol>
	  <li>Élément 1</li>
	  <li>Élément 2</li>
	  <li>Élément 3</li>
	</ol>
	<h2>Titre principale</h2>
	<p>Google</p> ><a href="https://www.google.com" target="_blank">Cliquez ici pour visiter</a>
	<h3>Tableau d'affichage</h3>
	<table border="2">
	  <tr>
        <th>Nom</th>
        <th>Prenom</th>
        <th>Classe</th>
        <th>Note/20</th>
	  </tr>
	  <tr>
        <td>Rb</td>
        <td>John</td>
        <td>Terminal</td>
        <td>15</td>
	  </tr>
	  <tr>
        <td>Rb</td>
        <td>Jane</td>
        <td>Terminal</td>
        <td>15</td>
    <tr>
        <td>Rb</td>
        <td>Jean</td>
        <td>Terminal</td>
        <td>15</td>
	  </tr>
	  <tr>
        <td>Rb</td>
        <td>Jule</td>
        <td>Terminal</td>
        <td>15</td>
	  </tr>
	  <tr>
        <td>Rb</td>
        <td>Julio</td>
        <td>Terminal</td>
        <td>15</td>
	  </tr>
	  <tr>
        <td>Rb</td>
        <td>Juliette</td>
        <td>Terminal</td>
        <td>15</td>
	</table>
	<h3>Bouton de lancement</h3>
	   <button>click001</button>
	   <button>click002</button>
	   <button>click003</button>
	<form action="/soumettre" method="POST">
	  <label for="nom">Nom :</label>
	  <input type="text" id="nom" name="nom">
	  <input type="submit" value="Envoyer">
	</form>
	<h3>CALCULATRICE</h3>
	<input type="number" id="num1" placeholder="Nombre 1">
<input type="number" id="num2" placeholder="Nombre 2">
<button onclick="additionner()">Additionner</button>
<p id="resultat"></p>

<script>
function additionner() {
    let num1 = parseFloat(document.getElementById("num1").value);
    let num2 = parseFloat(document.getElementById("num2").value);
    let sum = num1 + num2;
    document.getElementById("resultat").innerText = "Résultat : " + sum;
}
</script>
  </body>
</html>
