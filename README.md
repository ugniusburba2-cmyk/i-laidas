# Atviras biudžetas (demonstracija)

Puslapis, kuriame kiekvienas gali matyti valstybės pajamas, išlaidas ir likutį, peržiūrėti išlaidų detales, atsisiųsti duomenis (CSV, JSON) ir pamatyti, ką reiškia konkreti paaukota suma.

**Svarbu:** visi skaičiai `budget.json` faile yra pavyzdiniai. Tai demonstracinė versija, ne tikri valstybės duomenys.

## Failai

- `index.html` – puslapio struktūra
- `styles.css` – išvaizda (šviesi ir tamsi tema)
- `app.js` – skaičiavimai, diagramos ir veiksmai
- `budget.json` – biudžeto duomenys (keičiant šį failą, keičiasi visas puslapis)
- `icon.svg` – piktograma

## Kaip atnaujinti duomenis

Atidarykite `budget.json` ir pakeiskite sumas. Pajamų ir išlaidų sumos turi būti mln. EUR. Kiekvienos išlaidų kategorijos punktų suma turi sutapti su kategorijos suma.

## Paaukojimas

Puslapis pinigų nerenka. Skiltyje „Paremti valstybę“ rodoma tik skaičiuoklė. Oficialią aukojimo nuorodą galima įrašyti `app.js` faile į konstantą `OFFICIAL_DONATION_URL`, ir tik tada, kai tai yra oficialus valstybės institucijos kanalas.

## Privatumas

Duomenys nesiunčiami į serverį, nerenkami jokie asmeniniai duomenys.
