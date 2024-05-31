<!DOCTYPE html>
<html lang="sr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AutoMotive Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #343a40;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #495057;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }
        main {
            padding: 2rem;
        }
        section {
            margin-bottom: 2rem;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .newsletter input {
            padding: 0.5rem;
            margin-right: 0.5rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>AutoMotive Hub</h1>
        <p>Vaš ultimativni vodič kroz svet automobila!</p>
    </header>

    <nav>
        <a href="#">Početna</a>
        <a href="#">Vesti</a>
        <a href="#">Testovi automobila</a>
        <a href="#">Saveti i trikovi</a>
        <a href="#">O nama</a>
        <a href="#">Kontakt</a>
    </nav>

    <main>
        <section id="vesti">
            <h2>Najnovije Vesti</h2>
            <ul>
                <li>
                    <a href="#">Naslov Vesti 1</a>
                    <p>Kratak opis vesti koja donosi najnovije informacije iz sveta automobila.</p>
                </li>
                <li>
                    <a href="#">Naslov Vesti 2</a>
                    <p>Kratak opis vesti koja donosi najnovije informacije iz sveta automobila.</p>
                </li>
                <li>
                    <a href="#">Naslov Vesti 3</a>
                    <p>Kratak opis vesti koja donosi najnovije informacije iz sveta automobila.</p>
                </li>
            </ul>
        </section>

        <section id="testovi">
            <h2>Testovi Automobila</h2>
            <ul>
                <li>
                    <a href="#">Model Automobila 1</a>
                    <p>Kratak opis testa i rezultata. <a href="#">Detaljnije</a></p>
                </li>
                <li>
                    <a href="#">Model Automobila 2</a>
                    <p>Kratak opis testa i rezultata. <a href="#">Detaljnije</a></p>
                </li>
                <li>
                    <a href="#">Model Automobila 3</a>
                    <p>Kratak opis testa i rezultata. <a href="#">Detaljnije</a></p>
                </li>
            </ul>
        </section>

        <section id="saveti">
            <h2>Saveti i Trikovi</h2>
            <ul>
                <li>
                    <a href="#">Kako odabrati pravi automobil za vas</a>
                    <p>Kratak opis članka sa korisnim savetima.</p>
                </li>
                <li>
                    <a href="#">Održavanje automobila: 10 ključnih saveta</a>
                    <p>Kratak opis članka sa savetima za održavanje vozila.</p>
                </li>
                <li>
                    <a href="#">Zimska priprema vašeg automobila</a>
                    <p>Kratak opis članka sa savetima za zimsko održavanje vozila.</p>
                </li>
            </ul>
        </section>

        <section id="onama">
            <h2>O Nama</h2>
            <p>
                <strong>AutoMotive Hub</strong> je vaš pouzdan izvor za sve što je vezano za automobile. Bilo da ste strastveni ljubitelj automobila, profesionalni vozač ili samo neko ko želi da bude u toku sa najnovijim dešavanjima u autoindustriji, mi smo tu da vam pružimo sve potrebne informacije.
            </p>
        </section>

        <section id="kontakt">
            <h2>Kontakt</h2>
            <p>Imate pitanja? Želite da sarađujete sa nama? Kontaktirajte nas putem e-maila na <a href="mailto:kontakt@automotivehub.com">kontakt@automotivehub.com</a> ili nas pratite na društvenim mrežama.</p>
        </section>

        <section class="newsletter">
            <h2>Pretplatite se na naš newsletter</h2>
            <p>Unesite vašu e-mail adresu da biste primali najnovije vesti i ekskluzivne ponude.</p>
            <form action="#">
                <input type="email" placeholder="Vaš e-mail">
                <input type="submit" value="Pretplati se">
            </form>
        </section>
    </main>

    <footer>
        <p>Pratite nas na društvenim mrežama:</p>
        <a href="#">Facebook</a> | 
        <a href="#">Twitter</a> | 
        <a href="#">Instagram</a> | 
        <a href="#">LinkedIn</a>
        <p>&copy; 2024 AutoMotive Hub</p>
    </footer>
</body>
</html>
