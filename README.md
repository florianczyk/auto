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
                    <input type="text" name="wiek" required placeholder="Podaj województwo">
                </label>
                <label for="dane">
                    Wybierz przedział wiekowy <select name="wiek" id="" size="1">
                    <optgroup label="Prz.wiekowy">
                        <option value="1">18-29</option>
                        <option value="2">30-39</option>
                        <option value="3">40-49</option>
                        <option value="4">50-59</option>
                        <option value="5">60-69</option>
                        <option value="6">70-79</option>
                        <option value="7">80-89</option>
                        <option value="8">90-99</option>
                    </optgroup>
                    </select>
                </label>
        </fieldset>
        <fieldset>
            <legend><h2>Pojazd</h2></legend>
                </label>
                <label for="pojazd">
                    <input type="radio" name="przod" id="">Napęd przód
                </label>
                <label for="pojazd">
                    <input type="radio" name="tyl" id="">Napęd tył
                </label>
                <label for="pojazd">
                    <select name="marka" id="" value="Wybierz">
                        <optgroup label="Wybierz markę">
                            <option value="1">BMW</option>
                            <option value="2">Audi</option>
                            <option value="3">Ferrari</option>
                            <option value="4">Toyota</option>
                            <option value="5">Fiat</option>
                            <option value="6">Renault</option>
                            <option value="7">Ford</option>
                            <option value="8">Nissan</option>
                            <option value="9">Volkswgen</option>
                            <option value="10">Opel</option>
                            <option value="11">Kia</option>
                            <option value="12">Dacia</option>
                            <option value="13">Volvo</option>
                            <option value="14">Citroen</option>
                            <option value="15">Hyundai</option>
                            <option value="16">Mercedes</option>
                            <option value="17">Skoda</option>
                            <option value="18">Alfa Romeo</option>
                            <option value="19">Aston Martin</option>
                            <option value="20">Bentley</option>
                        </optgroup>
                    </select>
                </label>
                <label for="pojazd">
                    <input type="text" name="produkcja" id="" required placeholder="Wpisz rok produkcji">
                <label for="pojazd">
                    Fest wolne<input type="range" min="1" max="10" step="1">Fest szybkie
                </label>
                <label for="pojazd">
                    <input type="color"> Wybierz kolor furmany
                </label>
        </fieldset>
    </div>
</body>
</html>
