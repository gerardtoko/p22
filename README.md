# p22
``` 

$a = [
	["nom" => "matrix",	"annee" => 2002, "salle" => 20],
	["nom" => "django",	"annee" => 2014, "salle" => 18],
	["nom" => "fight club",	"annee" => 2009, "salle" => 20],
	["nom" => "calimero",	"annee" => 2010, "salle" => 12]	
];


foreach($a as $value) {
	echo "<br>";
	
	if (
		($value["annee"] >= 2005)
		&& ($value["annee"] <= 2015) 
		&& ($value["salle"] == 20)
		&& ($value["nom"] != "django"))
	{
	 echo $value["nom"];
	}
}


array(
  array(
    "Nom" => "Forrest Gump",
    "Année" => 1994,
    "Durée" => "2h20min",
    "Réalisateur" => "Robert Zemeckis",
    "Acteurs" => array("Tom Hanks", "Gary Siniseplus", "Brad Pitt"),
    "Genres" => array("Comédie dramatique" , "Romance"),
    "Like" => 100806,
    "Affiche" => "https://upload.wikimedia.org/wikipedia/en/6/67/Forrest_Gump_poster.jpg",
    "Privé" => true
  ),
  array(
    "Nom" => "Django Unchained",
    "Année" => 2013,
    "Durée" => "2h44min",
    "Réalisateur" => "Quentin Tarantino",
    "Acteurs" => array("Jamie Foxx", "Christoph Waltz", "Clint Eastwood"),
    "Genres" => array("Western"),
    "Like" => 10030,
    "Affiche" => "http://www.filmosphere.com/wp-content/uploads/2012/12/Django-Unchained-affiche.jpg",
    "Privé" => true
  ),
  array(
    "Nom" => "La Ligne verte",
    "Année" => 2000,
    "Durée" => "3h9min",
    "Réalisateur" => "Frank Darabont",
    "Acteurs" => array("Tom Hanks", "Michael Clarke Duncan",  "Brad Pitt"),
    "Genres" => array("Fantastique" , "Policier"),
    "Like" => 20030,
    "Privé" => false,
    "Affiche" => "http://www.notrecinema.com/images/cache/la-ligne-verte-poster_50432_40929.jpg",
   )
  );
  ```
