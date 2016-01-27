# Drupal Training Day - Hoe nu verder?

![test](http://drupaltrainingday.nl/sites/all/themes/trainingday/css/images/DTD2015-seal-golden-100x100.png)

* Links naar info
* Links naar chatkanalen en fora
* Uninstaller VM
* Installatie instructies [**XAMPP**](https://www.apachefriends.org/index.html)


## Installatie
Drupal stelt een aantal eisen aan je (lokale) host:

 * Apache (verreweg het meest gebruikt) of anders Nginx
 * PHP - Voor het uitvoeren van PHP-scripts
 * MySQL – voor het opslaan van de gegevens van de website
 
=============================
### Uitleg

#### Webserver
De webserver is een computerprogramma dat op verzoek van een bezoeker van een website de bijbehorende internetpagina's doorgeeft, zodat deze te zien zijn voor de bezoeker.

#### Apache
Apache is een webserver en wordt vaak gebruikt om website's op te hosten in een Linux omgeving.

#### PHP
PHP is de afkorting van `PHP: Hypertext Preprocessor`, een (gratis) open-source scripttaal die met behulp van webserver-software (meestal Apache) werkt. Drupal is voornamelijk geschreven in PHP.

#### MySQL
Een opensource database die vooral vaak op het web wordt gebuikt, vaak in combinatie met PHP. Een database is een centrale plaats op een webserver om gegevens op te slaan.


=============================

 
### XAMPP
Gelukkig is het afzonderlijk downloaden en installeren van de verschillende onderdelen niet nodig. Er bestaan een aantal mooie alles-in-een pakketten, zoals [**XAMPP**](https://www.apachefriends.org/index.html). Je kunt deze gratis downloaden en met enkele klikken van de muis installeren.

#### Download

De laatste versie van XAMPP is [**hier**](http://sourceforge.net/projects/xampp/files/latest/download) te downloaden.

#### Installatie

Is XAMPP gedownload, dan open je de Windows Verkenner. Vind het XAMPP-bestand (vaak in de Downloads map) en open het. 

Het installatie-scherm word nu geopend. Doorloop de installatie en klik op finish. Mogelijk vraagt jouw Windows Firewall om toestemming. Geef deze toestemming.

Er is nu een een map aangemaakt op het hoogste niveau van je systeem, over het algemeen is dit in 'C:\'. De aangemaakte map heet 'xampp'.

Je beschikt nu over een localhost. Deze kun je bereiken via je webbrowser op <http://localhost>.

#### Beheren
De webserver staat nu weliswaar op onze lokale schijf, maar draait nog niet. We moeten die eerst starten. Vind in de XAMPP folder (C:\xampp ) het bestand xampp-control.exe en start het.

Het XAMPP Control Panel verschijnt.

Klik op de [Start]-knop rechts van “MySQL”.
=============================
## Drupal
### Download
Wanneer je naar je nieuwe localhost gaat, komt je op het dashboard.
Onderaan deze pagina staan een aantal logo's van bekende webapplicaties. Klik op het Drupal-logo.

Je komt nu op een pagina waarop je verschillende webapplicaties kunt downloaden.

Zoek op deze pagina naar het kopje 'Drupal'. Hieronder staan een aantal downloadknoppen.

Klik op 'download' achter de nieuwste Drupal 7-versie (De versie start met 'Drupal Module 7.') voor het platform 'Windows'.

### Installatie
Ga nu naar de map waar ook jouw XAMPP installatie-bestand stond (vaak de Downloads map). Hier staat een nieuw bestand, waarvan de naam start met 'bitnami-drupal-'. Open dit bestand.

Dit installatie bestand is helaas niet beschikbaar in het Nederlands. Kies daarom bij 'Language Selection' voor de optie 'English - English' en klik op 'OK'.

Je komt nu in het welkomstscherm. Klik op 'Next'. Hier kun je de installatiemap van XAMPP selecteren. Klik hier ook weer op 'Next'.

In dit scherm ga je een beheerdersaccount aanmaken. Vul bij 'Login' een gebruikersnaam in voor jouw beheerdersaccount en onthoud deze goed. Vul bij 'Your real name' je eigen naam in en bij 'Email Address' je eigen email adres.

Onder 'Please enter the existing MySQL password for XAMPP', staat een veld, 'Password' genoemd. Laat dit veld leeg.

Vul bij 'Enter the application password' een zelfgekozen wachtwoord in. In het veld daaronder vul je nog een keer dit zelfde wachtwoord in.

Klik op 'Next', vul hier de naam van je nieuwe Drupal-website in en klik weer op 'Next'.

In dit scherm vraagt de installatie om 'mail support' in te schakelen. Schakel dit niet in en klik op 'Next'.

In dit scherm vraagt de installatie of je gebruik wil maken van 'Bitnami Cloud Hosting'. Vink dit vakje uit, zodat je hier geen gebruik van maakt en klik op 'Next'. Nu volgt een aankondiging over je installatie. Klikt op 'Next'.

De installatie wordt nu gestart. Zodra deze installatie klaar is, klik je op 'Finish'.

Nu opent jouw eigen nieuwe Drupal-website, helemaal klaar voor gebruik!




