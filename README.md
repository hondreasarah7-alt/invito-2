# invito-2
<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sarah & Marco - Il Nostro Matrimonio</title>
<style>
body {
    margin: 0;
    font-family: 'Georgia', serif;
    background-color: #fdfaf6;
    color: #333;
    text-align: center;
}
header {
    background: url('copertina.jpg') center/cover no-repeat;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    color: white;
    background-attachment: fixed;
}
header h1 {
    font-size: 3em;
    margin: 0;
}
section {
    padding: 60px 20px;
}
h2 {
    margin-bottom: 20px;
    font-size: 2em;
}
.gallery img {
    width: 250px;
    margin: 10px;
    border-radius: 10px;
}
.timeline {
    max-width: 700px;
    margin: auto;
    text-align: left;
}
.timeline p {
    margin: 15px 0;
}
.location {
    background-color: #f3ece6;
}
.gift {
    background-color: #e8d8c3;
}
footer {
    padding: 30px;
    background-color: #333;
    color: white;
}
button {
    padding: 10px 20px;
    background-color: #c6a77d;
    border: none;
    color: white;
    cursor: pointer;
    border-radius: 5px;
}
button:hover {
    background-color: #a8885f;
}
</style>
</head>

<body>

<header>
    <h1>Sarah & Marco</h1>
    <p>Vi invitiamo a celebrare il nostro amore</p>
    <p>Data del matrimonio</p>
</header>

<section>
    <h2>La Nostra Storia</h2>
    <div class="gallery">
        <img src="foto1.jpg" alt="Foto 1">
        <img src="foto2.jpg" alt="Foto 2">
        <img src="foto3.jpg" alt="Foto 3">
    </div>
</section>

<section class="location">
    <h2>La Cerimonia</h2>
    <p><strong>Chiesa:</strong> Nome Chiesa</p>
    <p><strong>Indirizzo:</strong> Via ....</p>
    <p><strong>Orario:</strong> 15:30</p>

    <h2>Il Ricevimento</h2>
    <p><strong>Location:</strong> Nome Villa / Ristorante</p>
    <p><strong>Indirizzo:</strong> Via ....</p>
</section>

<section>
    <h2>Programma della Giornata</h2>
    <div class="timeline">
        <p>15:30 – Cerimonia in Chiesa</p>
        <p>17:00 – Aperitivo di Benvenuto</p>
        <p>19:30 – Cena</p>
        <p>22:30 – Taglio della Torta</p>
        <p>23:00 – DJ Set & Festa</p>
    </div>
</section>

<section class="gift">
    <h2>Lista Nozze</h2>
    <p>Il regalo più bello sarà condividere con voi questo giorno speciale.</p>
    <p>Per chi desidera contribuire al nostro viaggio di nozze:</p>
    <p><strong>IBAN:</strong> IT00X0000000000000000000000</p>
    <button onclick="navigator.clipboard.writeText('IT00X0000000000000000000000')">
        Copia IBAN
    </button>
</section>

<footer>
    <p>Con amore, Sarah & Marco ❤️</p>
</footer>

</body>
</html>
