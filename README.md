# 🎬 Filmwebpagina - PHP Dynamische Pagina

## 📖 Beschrijving
Deze opdracht richtte zich op het bouwen van een dynamische filmwebpagina met **HTML, CSS en PHP**. De pagina haalt alle filmgegevens uit vooraf gedefinieerde **PHP-variabelen**, waardoor het eenvoudig is om een nieuwe film toe te voegen door enkel de variabelen te wijzigen.

## 🚀 Uitgevoerde Taken
- **Filmgegevens dynamisch geladen via PHP-variabelen**, waaronder:
  - 🎥 Titel
  - 📝 Synopsis
  - 🎬 Regisseur
  - 🎭 Lijst van acteurs
  - ⭐ Algemene score
  - 🗣️ Reviews van gebruikers (titel, naam, e-mail, score, review, datum)
  - 🖼️ Filmposter
  - 🏷️ Tags
- **Dynamische weergave geïmplementeerd**:
  - Als de score **hoger is dan 8**, verschijnt een kader met de tekst: _"Dit is een aanrader!"_
  - De score wordt omgezet naar **maximaal 5 sterren** (bijv. 6/10 = 3/5 sterren)
  - De gemiddelde score van gebruikersreviews wordt berekend en weergegeven
  - De e-mailadressen van gebruikers worden weergegeven als **"mailto:" links**

## ⚙️ Installatie-instructies
1. **Installeer een lokale PHP-server** zoals XAMPP of MAMP.
2. **Plaats de PHP-bestanden** in de juiste servermap (bijv. `htdocs` bij XAMPP).
3. **Start de server** en open de pagina in een webbrowser via `http://localhost/filmwebpagina.php`.

## 🖥️ Gebruiksinstructies
1. **Pas de filmgegevens aan** door de PHP-variabelen te wijzigen.
2. **Open de pagina** en bekijk de dynamisch weergegeven filmgegevens.
3. **Test met verschillende films** door de variabelen aan te passen en te vernieuwen.

## 💻 Voorbeeld van gebruikte PHP-variabelen
```php
<?php
$film_titel = "Inception";
$synopsis = "Een dief die de kracht heeft om in de dromen van mensen te infiltreren, krijgt een laatste kans op verlossing...";
$regisseur = "Christopher Nolan";
$acteurs = ["Leonardo DiCaprio", "Joseph Gordon-Levitt", "Ellen Page"];
$score = 8.8;
$tags = ["Sciencefiction", "Actie", "Thriller"];
$poster_url = "inception.jpg";
$reviews = [
    ["titel" => "Mind-blowing!", "naam" => "Jan", "email" => "jan@example.com", "score" => 9, "review" => "Geweldige film!", "datum" => "2024-02-06"],
    ["titel" => "Super", "naam" => "Lisa", "email" => "lisa@example.com", "score" => 8, "review" => "Fantastisch verhaal!", "datum" => "2024-02-05"]
];
?>
```

## 🛠️ Gebruikte Software en Tools
- **PHP-server** (Apache met PHP via XAMPP, MAMP of een andere lokale serveromgeving)
- **Webbrowser** voor het testen van de uitvoer

## 🤝 Bijdragen
Wil je bijdragen? Voel je vrij om een **pull request** in te dienen of een **issue** aan te maken met suggesties voor verbeteringen!

## 📜 Licentie
Dit project is beschikbaar onder de **MIT-licentie**. Voel je vrij om het te gebruiken en aan te passen.

## 📧 Contactgegevens
Heb je vragen of suggesties? Neem contact op via **[randi@example.com](mailto:randi@example.com)**.

---
✨ _Deze opdracht is succesvol afgerond en getest!_ 🎬🍿
