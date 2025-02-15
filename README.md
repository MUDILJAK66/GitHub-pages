<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Uvod u HTML">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="Maja U">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Obrazac </title>
        </head>
<body>
    <form action="/action_page.php">
        <label for="fname">Ime i prezime:</label><br>
        <input type="text" id="fname" placeholder="Maja Udiljak"><br>
        <label for="email">Unesi email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="phone">Broj telefona:</label><br>
        <input type="tel" id="phone" name="phone" placeholder="097 794 1137"pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required><br>
        <label for="password">Vaša zaporka</label><br>
        <input type="password">
        <br><br>

        <label for="colors">Boja:</label>
        <input type="color" value="color:black">

        <br><br>
        <label for="potvrda"> Želite li primati obavijesti</label>
        <input type="checkbox" id="obavijesti" name="potvrda" value="Potvrda">
        <br><br>
        <label for="ocjene">Ocjenite usluge naše tvrtke</label><br>
        <label for="ocjena1">1</label>
        <input type="radio" id="ocjena1" name="ocjena" value="1">
        <label for="ocjena2">2</label>
        <input type="radio" id="ocjena2" name="ocjena" value="2">
        <label for="ocjena3">3</label>
        <input type="radio" id="ocjena3" name="ocjena" value="3">
        <label for="ocjena4">4</label>
        <input type="radio" id="ocjena4" name="ocjena" value="4">
        <label for="ocjena5">5</label>
        <input type="radio" id="ocjena5" name="ocjena" value="5">
        <br><br>
        <label for="myfile">Priložite datoteku:</label><br>
        <input type="file" id="myfile" name="myfile" multiple>
        <br><br>
        <label for="datum">Izaberi datum:</label>
        <input type="date" id="datum" name="datum">

    </form>
</body>
</html>


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Uvod u HTML">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="Maja U">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Obrazac </title>
    </head>
<body>
   <form action="/action_page.php" method="post">
    <label for="fname">Ime i prezime *</label><br>
    <input type="text" id="fname" placeholder="Vaše ime i prezime" required>
    <br><br>
    <label for="email">E-mail adresa *</label><br>
    <input type="email" id="email" name="email" required>
    <br><br>
    <label for="phone">Broj telefona *</label><br>
    <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required>
    <br><br>
    <label for="datum">Izaberi datum:</label>
    <input type="date" id="datum" name="datum">
    <br><br>
    <label for="jezici"> Želite li primati obavijesti</label><br>
    <label for="jezik1">Engleski</label>
    <input type="checkbox" id="jezik1" name="jezici" value="Engleski">
    <label for="jezik2">Španjolski</label>
    <input type="checkbox" id="jezik2" name="jezici" value="Španjolski">
    <label for="jezik3">Njemački</label>
    <input type="checkbox" id="jezik3" name="jezici" value="Njemački">
    <label for="jezik4">Francuski</label>
    <input type="checkbox" id="jezik4" name="jezici" value="Francuski">
    <label for="jezik5">Talijanski</label>
    <input type="checkbox" id="jezik5" name="jezici" value="Talijanski">
    <br><br>
    <label for="potvrda">Da li će te koristiti usluge naše tvrtke</label><br>
    <label for="ocjena1">da</label>
    <input type="radio" id="ocjena1" name="potvrda" value="1">
    <label for="ocjena2">da</label>
    <input type="radio" id="ocjena2" name="potvrda" value="2">
    <br><br>
    <label for="myfile">Priložite životopis:</label><br>
    <input type="file" id="myfile" name="myfile" multiple>
    <br><br>
    <button type="reset">Obriši podatke</button><input type="submit" value="Prijavi se">
</form>
</body>
</html>

1. Potrebno je HTML dokumentu dodijeliti naslov "My Portfolio". Što je potrebno napisati unutar <head> oznake HTML dokumenta kako bi se to postiglo?
2. Koji element koristimo za označavanje sadržaja koji predstavlja glavnu navigaciju?
3. Koristeći HTML, označite sadržaj kao audio zapis sa kontrolama za upravljanje reprodukcijom sadržaja.
4. Što je HTML?
5 zadatak
6. Koji od navedenih elemenata je najprikladnije koristiti za označavanje sadržaja koji nije direktno povezan sa sadržajem koji ga okružuje?
7. Koji od navedenih elemenata je najprikladnije koristiti za označavanje uvodnog sadržaja?
8. HTML dokument ne smije sadržavati više od jednog <article> elementa.
9. Kako HTML omogućuje izradu pristupačnih web stranica?
10. Koji HTML atribut koristimo za primjenu linijskih stilskih pravila?
11. Koji selektor će selektirati sve <a> elemente koji se nalaze pod pokazivačem miša?
12. Što je potrebno napisati da bi se iskoristila CSS3 varijabla "color-primary" kao vrijednost za promjenu boje teksta?
13. prazav <div> elementKoristeći CSS, selektirajte element i uredite ga tako da odgovara obliku na slici. Pretpostavite veličine i boje, one ne moraju biti u potpunosti točne. (list slika)
14. zadatak
    15. Potrebno je pozvati SCSS funkciju "lighten". Koja od navedenih linija koda je ispravna?
    16. 16. Potrebno je iskoristiti SCSS mixin "square". Koja od navedenih linija koda je ispravna?
17. Što je to minifikacija (minimizacija)? Zašto koristiti minifikaciju?
18. Što se od navedenog ne koristi za petlju?
19. Što od navedenog nije ispravan identifikator varijable?
20. Potrebno je definirati funkciju "max" koja će vratiti veći od dva broja. Ako su brojevi jednaki, funkcija vraća prvi broj.
Funkcija prima dva broja preko parametara. Pretpostavite da će parametri uvijek biti brojevi.
max(1, 2) - funkcija vraća 2
max(1, 1) - funkcija vraća 1
21. Koja je razlika između deklariranja varijable pomoću ključne riječi "let" i "const"?
22. Izradite JavaScript dokument koji omogućuje funkcionalnosti web aplikacije i korisničkog sučelja, a koje su opisane u kriterijima zadatka. Kriteriji zadatka nalaze se u dokumentu s temom koji ste ranije preuzeli.
23. JavaScript je objektno-orijentirani programski jezik.
24. JavaScript je funkcijski programski jezik.
25. Što je ECMAScript?
26. Što HTML DOM ne definira?
27. Koja od navedenih metoda koje postoje nad "document" objektom nije ispravna?
27. Koja od navedenih metoda koje postoje nad "document" objektom nije ispravna?
28. Na stranici se nalazi copyright element i unutar njega element s ID-jem "copyright-year".
Željeno ponašanje je da se unutar elementa s ID-jem "copyright-year" ispiše trenutna godina.
Koristeći JavaScript, napišite kod koji će realizirati željeno ponašanje. (zadatak riješiti u dostupnom code editoru)
29. što je GIT
30. Kako se inicijalizira Git repozitorij?
31. Što je to repozitorij?
32. Kako se instalira paket s nazivom algebra-library tako da se zapiše u package.json datoteku?
34. Child komponenta može i smije mijenjati props objekt koji je primila od parent komponente.
35. Što od navedenog nije jedna od faza životnog ciklusa React komponente?
36. Potrebno je u komponentu <User> postaviti prop "firstName". Odaberite ispravnu liniju koda.


