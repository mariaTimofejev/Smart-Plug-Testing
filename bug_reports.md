### Bug 1 – Nutipistik ei ühendu automaatselt pärast ruuteri restarti

# Kirjeldus:
- Pärast WiFi ruuteri taaskäivitamist ei loonud nutipistik automaatselt võrguühendust.

# Testimise sammud:

Ühendasin nutipistiku WiFi võrku
Kontrollisin, et seade töötab normaalselt
Taaskäivitasin ruuteri
Ootasin 3 minutit

# Oodatud tulemus:
- Seade ühendub automaatselt uuesti võrku.

# Tegelik tulemus:
- Seade jäi offline olekusse ning vajas käsitsi taaskäivitamist.

# Tõsidus:
- Keskmine

### Bug 2 – Viivitus kahe telefoni kasutamisel

# Kirjeldus:
- Seadme reageerimine aeglustus, kui nutipistikut juhiti korraga kahest telefonist.

# Testimise sammud:

- Ühendasin seadme telefoniga A
- Lisasin seadme telefoni B
- Lülitasin seadet sisse ja välja mõlemast telefonist

# Oodatud tulemus:
- Seade reageerib koheselt mõlemast telefonist.

# Tegelik tulemus:
- Reageerimisel tekkis 3–5 sekundiline viivitus.

# Tõsidus:
- Madal

# Bug 3 – Äpp ei uuenda seadme olekut kohe

# Kirjeldus:
- Pärast seadme väljalülitamist ei uuenenud seadme staatus mobiilirakenduses kohe.

# Testimise sammud:

- Lülitasin seadme sisse
- Lülitasin seadme välja füüsiliselt
- Kontrollisin rakenduse olekut

# Oodatud tulemus:
- Rakendus kuvab kohe õige seadme staatuse.

# Tegelik tulemus:
- Rakendus näitas vana olekut umbes 10 sekundit.

Tõsidus:
- Madal
