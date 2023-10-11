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
            <legend><h2>Dane ogólne pojazdu</h2></legend>
                </label>
                <label for="pojazd">
                    <input type="radio" name="przod" id="">Napęd przód
                </label>
                <label for="pojazd">
                    <input type="radio" name="tyl" id="">Napęd tył
                </label>
                <label for="pojazd">
                    <select name="marka" id="">
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
        <fieldset>
            <legend><h2>Wiecej danych pojazdu</h2></legend>
                <label for="wdpojazdu">
                    Wybierz typ nadwozia <select name="nadwozie" id="">
                        <optgroup label="Wybierz nadwozie">
                            <option value="1">Auta małe</option>
                            <option value="2">Auta miejskie</option>
                            <option value="3">Coupe</option>
                            <option value="4">Kabriolet</option>
                            <option value="5">Kombi</option>
                            <option value="6">Kompact</option>
                            <option value="7">Minivan</option>
                            <option value="8">Sedan</option>
                            <option value="9">Suv</option>
                        </optgroup>
                    </select>
                <label for="pojazd">
                    Wybierz kolor wnętrza <input type="color">
                </label>
                <img src="data:image/jpeg;base64,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" alt="">
                <label for="wdpojazdu"> <form > Wartość maksymalna pojazdu <input type="range" id="a" name="a" min="0" max="200000" step="1000" oninput="result.value=a.value"/> <output name="result" for="a">0</output> zł </form> </label> 
                Wpisz swoje uwagi odnośnie pojazdu <textarea name="uwagi" id="" cols="30" rows="3"></textarea>
        </fieldset>
        <button class="guzik">Szukaj</button>
    </div>
</body>
</html>
