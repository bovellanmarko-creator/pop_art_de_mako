<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taidegalleria - 1950-luku</title>
    <link href="https://fonts.googleapis.com/css2?family=Lobster&family=Special+Elite&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        /* 1950-luvun väripaletti ja perusasetukset */
        body {
            margin: 0;
            padding: 0;
            background-color: #f4ece1; /* Pehmeä kermanvärinen tausta */
            font-family: 'Special Elite', typewriter, serif;
            color: #333;
        }

        /* Keskittävä pääsäiliö */
        .main-container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #ffffff;
            box-shadow: 0 0 50px rgba(0,0,0,0.1);
            min-height: 100vh;
        }

        /* Pääkuva ylhäällä */
        .hero-image {
            width: 100%;
            display: block;
            border-bottom: 8px solid #5d8aa8; /* "Airforce blue" koristeraita */
        }

        /* Sisältöalue */
        .content {
            padding: 40px;
        }

        h1 {
            font-family: 'Lobster', cursive;
            text-align: center;
            color: #c0392b; /* Retro punainen */
            font-size: 3rem;
            margin-bottom: 40px;
            text-shadow: 2px 2px #eee;
        }

        /* Teosten esittely "taulukko" ilman reunoja */
        .art-row {
            display: flex;
            align-items: center;
            margin-bottom: 50px;
            gap: 30px;
        }

        .art-image {
            flex: 0 0 300px;
            height: 300px;
            object-fit: cover;
            border: 10px solid #fff;
            box-shadow: 5px 5px 15px rgba(0,0,0,0.2);
            background-color: #eee;
        }

        .art-text {
            flex: 1;
        }

        .art-text h2 {
            font-family: 'Playfair Display', serif;
            margin-top: 0;
            color: #2c3e50;
            border-bottom: 2px dashed #bdc3c7;
            padding-bottom: 10px;
        }

        .art-text p {
            line-height: 1.6;
            font-size: 1.1rem;
        }

        /* Mobiilioptimointi */
        @media (max-width: 768px) {
            .art-row {
                flex-direction: column;
                text-align: center;
            }
            .art-image {
                flex: 0 0 auto;
                width: 100%;
                max-width: 300px;
            }
        }
    </style>
</head>
<body>

    <div class="main-container">
        <img src="kolme_nude_piisapa_lenskari.jpg" alt="Pääteos" class="hero-image">

        <div class="content">
            <h1>Modernia Väriä & Muotoa</h1>

            <div class="art-row">
                <img src="https://via.placeholder.com/300" alt="Teos 1" class="art-image">
                <div class="art-text">
                    <h2>Abstrakti Unelma</h2>
                    <p>Tämä teos edustaa aikakauden dynaamista otetta, jossa värit kohtaavat vapaan muodon. Teos on toteutettu sekatekniikalla alkuperäiselle 50-luvun sanomalehtipaperille.</p>
                </div>
            </div>

            <div class="art-row">
                <img src="https://via.placeholder.com/300" alt="Teos 2" class="art-image">
                <div class="art-text">
                    <h2>Urbaani Syke</h2>
                    <p>Katunäkymä, joka on suodatettu pop-taiteen esi-isien linssin läpi. Voimakkaat kontrastit ja typografiset elementit luovat syvyyttä ja tarinaa jokaisella siveltimenvedolla.</p>
                </div>
            </div>

            <div class="art-row">
                <img src="https://via.placeholder.com/300" alt="Teos 3" class="art-image">
                <div class="art-text">
                    <h2>Piispan Hymy</h2>
                    <p>Hahmotutkielma, jossa yhdistyvät klassinen muotokuvataide ja moderni katutaide. Väripaletti on poimittu suoraan vanhoista matkailujulisteista.</p>
                </div>
            </div>

            <div class="art-row">
                <img src="https://via.placeholder.com/300" alt="Teos 4" class="art-image">
                <div class="art-text">
                    <h2>Linnunrata</h2>
                    <p>Lennokas ja energinen sommitelma, joka johdattaa katsojan läpi aikakauden optimismin ja teknologisen murroksen. Teos, joka herättää huoneen eloon.</p>
                </div>
            </div>

        </div>
    </div>

</body>
</html>
