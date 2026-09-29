# ViliQuiz 2.0

Kahoot + Blooket -tyylinen selainpelin valmis kehitysversio.

## Käynnistys
- Asenna Node.js
- Avaa kansio terminaalissa
- `npm install`
- `npm start`
- Avaa `http://localhost:3000`

## Demo-admin
Salasana: `blooket123`

## Mukana
- pakollinen rekisteröinti ja kirjautuminen
- käyttäjätilit, XP, levelit, kolikot ja tilastot
- live WebSocket multiplayer
- pelikoodit ja lobby
- Classic, Speed, Battle, Survival ja Treasure -pelimuotojen runko
- 5/8 kysymyksen pelit
- pisteet, vastaukset ja ranking
- profiili ja inventory
- shop ja adminin luomat paketit/skinit
- package/skin editor
- admin dashboard
- online-lista
- aktiiviset pelit
- admin spectate
- admin join mihin tahansa aktiiviseen peliin
- kick
- kolikkotyökalu
- palvelinviesti
- daily limitin hallinta (oletuksena pois)

## Julkaisu
Tämä on toimiva kehitysprojekti. Ennen julkista tuotantokäyttöä salasanat tulee hashata, sessiot/tunnisteet tehdä turvallisesti ja tiedot siirtää oikeaan tietokantaan. Vercelissä WebSocket-palvelinta ei voi käyttää näin sellaisenaan; tarvitset erillisen realtime-backend-palvelun tai muun palvelimen.
