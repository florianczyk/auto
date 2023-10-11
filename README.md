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
                <input type="radio" name="mezczyzna" id="">Mężczyzna
                </label>
                <label for="dane">
                    <input type="radio" name="kobieta" id="">Kobieta
                </label>
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
                    Wybierz przedział wiekowy <select name="wiek" id="" size="1">
                        <option value="1">18-29</option>
                        <option value="2">30-39</option>
                        <option value="3">40-49</option>
                        <option value="4">50-59</option>
                        <option value="5">60-69</option>
                        <option value="6">70-79</option>
                        <option value="7">80-89</option>
                        <option value="8">90-99</option>
                    </select>
                </label>
        </fieldset>
    </div>
</body>
</html>
