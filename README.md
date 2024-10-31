# Magyar diceware file generáló script

Szerző: Müller Miklós <muller.miklos@gmail.com>

Használat: ./csinald

*Vigyázat:* Ez a script ma (2024.10.31) éppen működik. de semmi nem garantálja, hogy a hu.wiktionary.org forrásoldalon nem változk
valami, amitől elromlik ez a script. Ha így lenne, nyiss egy issuet.

A script amúgy:

- Letölti a https://hu.wiktionary.org/wiki/Kateg%C3%B3ria:Magyar_szavak_list%C3%A1ja címről
a magyar szavakat
- abból kiválogatja az ékezet nélkülieket
- abból kiszűri a vissza-, szerte-, szembe-, helyre-, egybe-, ellen-, bele-, haza-, tele-, neki-, meg-, fel-, oda-, ide- kezdetűeket
- abból a 3-7 hosszúságúakat

Ez ma (2024/10/31) egy 8222 szóból álló lista, ami pont egy kicsit több a diceware-hez szükséges 7776-os listánál.

Ezekből még kiszűr annyit, hogy pont 7776 maradjon, és kész is a magyar diceware lista.

Szabadon letölthető, módosítható, forkolható, bármi, csak a kredit maradjon meg.

