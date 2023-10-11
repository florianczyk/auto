<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style3.css">
    <style>
        body {
            background-color: lightsteelblue;
            display: flex;
            justify-content: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="gora"><h1>TeAuto</h1></div>
        </header>
        <fieldset>
            <legend><h2>Twoje dane</h2></legend>
                <label for="dane">
                    <input type="text" name="imie" required placeholder="Wpisz swoje imie">
                </label>
                <label for="dane">
                    <input type="text" name="nazwisko" required placeholder="Wpisz swoje nazwisko">
                </label>
                <label for="dane">
                    <input type="text" name="wiek" required placeholder="Podaj swoj wiek">
                </label>
                <label for="dane">
                    <input type="radio" name="mezczyzna" id="">Mężczyzna
                </label>
                <label for="dane">
                    <input type="radio" name="mezczyzna" id="">Kobieta
                </label>
                <label for="dane">
                    <input type="range" name="mezczyzna" id="" min="18" max="99" step="1">
                </label>
        </fieldset>
    </div>
</body>
</html>
