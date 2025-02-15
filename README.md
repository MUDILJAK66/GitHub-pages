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
