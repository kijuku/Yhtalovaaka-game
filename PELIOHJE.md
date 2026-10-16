# Yhtälövaaka – peliohje

Yhtälövaaka on selaimessa pelattava yhtälöpeli. Siinä ensimmäisen asteen yhtälö näkyy
kallistuvana vaakana. Peli toimii tietokoneella, tabletilla ja Chromebookilla ilman asennusta.

**Pelaa:** https://kijuku.github.io/Yhtalovaaka-game/

## Vaaka

| Palikka | Tarkoittaa |
|---|---|
| sininen laatikko | **x** (sen painoa eli ratkaisua ei näe) |
| oranssi punnus | **+1** |
| punainen ilmapallo | **−1** (vetää ylöspäin) |

Yhtälö `2x + 3 = 11` on vaaka, jonka vasemmalla puolella on kaksi laatikkoa ja kolme punnusta
ja oikealla yksitoista punnusta. Kun teet **saman siirron molemmille puolille**, vaaka pysyy
tasapainossa. Yhtälö on ratkaistu, kun vaa'alla on muoto **x = luku**.

## Aloitus

1. **Kuka pelaa?** Kirjoita nimimerkki tai valitse se *Viimeksi pelanneet* -listasta. Peli ei
   käynnisty ilman nimimerkkiä.
2. **Taso**: valitse alapalkista *Helppo*, *Keskitaso* tai *Vaikea*. Valinta muistetaan.
3. **Pelitapa**: paina pelitapakorttia. Kortissa näkyy oma ennätyksesi valitulla tasolla.

## Pelitavat

| Pelitapa | Tavoite | Tulos |
|---|---|---|
| **Pikakisa** | 5 yhtälöä mahdollisimman nopeasti | aika + vihjesakot (pienempi parempi) |
| **Sprintti** | 10 yhtälöä mahdollisimman nopeasti | aika + vihjesakot |
| **Aikakisa** | montako yhtälöä ratkaiset 3 minuutissa | ratkaistut yhtälöt (suurempi parempi) |
| **Harjoittelu** | ei kelloa; siirron voi tehdä myös vain toiselle puolelle | ei ennätyksiä |

- Aika-ajot alkavat lähtölaskennalla 3–2–1.
- Kello käy vain, kun yhtälö on näkyvissä. Ratkaisun jälkeistä *Oikein!*-hetkeä ei lasketa
  aikaan.

## Vaikeustasot

| Taso | Yhtälötyypit | Esimerkki |
|---|---|---|
| **Helppo** | `x + b = c`, `ax = c` | `x + 4 = 9`, `3x = 12` |
| **Keskitaso** | `ax + b = c`, x molemmilla puolilla | `2x + 3 = 11`, `5x − 2 = 2x + 7` |
| **Vaikea** | x molemmilla puolilla, sulut, negatiiviset ratkaisut | `4x − 1 = 2x + 5`, `2(x + 3) = x + 8` |

Jokaisen yhtälön ratkaisu on kokonaisluku, ja palikat mahtuvat vaa'alle. Peli antaa useammin
niitä tyyppejä, jotka ovat sinulle vaikeita.

## Siirron tekeminen

Siirto on **termi + toiminto**.

1. Kirjoita termi: luku tai x-termi, esim. `3`, `2x`, `x` tai `-1`.
2. Valitse toiminto:

| Nappi | Näppäin | Tekee molemmille puolille |
|---|---|---|
| **+ n** | `+` | lisää termin |
| **− n** | `-` | vähentää termin |
| **· n** | `*` | kertoo luvulla |
| **: n** | `/` | jakaa luvulla |

Esimerkki yhtälölle `2x + 3 = 11`:

1. kirjoita `3` ja paina `−`, jolloin vaa'alla on `2x = 8`
2. kirjoita `2` ja paina `:`, jolloin vaa'alla on `x = 4`, ja yhtälö on ratkaistu

Muuta:

- Kun termikenttä on tyhjä, `-` aloittaa negatiivisen luvun.
- `x`:n jälkeen kirjoitettu numero aloittaa uuden termin.
- Kielletty tai turha siirto (esim. nollalla jakaminen, x:llä kertominen tai jakaminen,
  nollan lisääminen tai ykkösellä kertominen) näyttää selityksen ja tyhjentää kentän. Vaaka ei
  muutu, eikä siirtoa lasketa.
- **Kumoa** (`Z`) peruu edellisen siirron. Se lasketaan siirroksi.
- **Vihje** (`H`) tekee seuraavan järkevän siirron puolestasi. Pikakisassa ja Sprintissä
  jokainen vihje lisää aikaan **10 sekuntia**, ja Aikakisassa se vie 10 sekuntia jäljellä
  olevasta ajasta. Harjoittelussa vihje on ilmainen.
- `Backspace` poistaa merkin, ja `Esc` keskeyttää kisan. Kisan voi keskeyttää myös HUD:n
  *Lopeta*-napista.
- Kosketusnäytöillä ruudun alareunassa on numerorivi `0–9`, `x` ja `←`.

### Harjoittelu: vaaka kallistuu

Harjoittelussa HUD:n **Kohde**-napista voi valita, kohdistuuko siirto *molemmille puolille*,
*vain vasemmalle* vai *vain oikealle*. Toispuoleinen siirto kallistaa vaakaa, ja silloin
näkee, miksi siirto on tehtävä molemmille puolille. Yhtälössä näkyy silloin `≠`.
Tasapainon saa takaisin **Kumoa**-napilla tai tekemällä vastaavan siirron toiselle puolelle.
Vihje ei toimi, kun vaaka on vinossa. Jokainen uusi yhtälö alkaa kohteella *molemmat puolet*.
Kisoissa siirto tehdään aina molemmille puolille.

## Tulosnäyttö

- Iso tulos, mitali ja sijoitus kunniataulussa. Kunniataululle pääsystä tulee konfettia.
- **Siirrot / optimi**: tekemäsi siirrot verrattuna pienimpään mahdolliseen määrään, ja niistä
  laskettu **tehokkuus** (100 % = jokainen siirto osui).
- Vihjeet, keskiaika ja hitain yhtälö.
- **Harjoittele näitä**: yhtälöt, joissa tarvitsit vihjeitä tai ylimääräisiä siirtoja.
- **Taitokartta**: viisi yhtälötyyppiä värikoodattuna.
  - vihreä = sujuu (keskiaika enintään 12 s)
  - keltainen = hidas
  - punainen = vaikeuksia (vihjeitä yli puolessa tai keskimäärin yli kaksi ylimääräistä siirtoa)
  - harmaa = ei vielä kokeiltu
- Napit: *Uudestaan (Enter)*, *Valikkoon*, *Kunniataulu* ja tarvittaessa **Lähetä opettajalle**.

## Kunniataulu

- Välilehdet **Pikakisa**, **Sprintti**, **Aikakisa** ja **Pelaajat**.
- Jokaisella pelitavalla ja vaikeustasolla on oma top 10 (kulta, hopea, pronssi). *Taso*-napista
  vaihdetaan näytettävää tasoa.
- Tasatuloksessa vähemmän siirtoja voittaa, sitten aiempi merkintä.
- **Pelaajat**-sivulla näkyvät kaikki tällä laitteella pelanneet: yhtälöt, kierrokset,
  tehokkuus, vihjeet, omat ennätykset valitulla tasolla ja valitun pelaajan taitokartta.
- *Tyhjennä taulu* poistaa kunniataulun vahvistuksen jälkeen.

Tiedot tallentuvat **vain tämän selaimen** muistiin (IndexedDB), joten kunniataulu on
laitekohtainen.

## Lähetä opettajalle

Nappi näkyy vain, kun peli on avattu opettajan linkillä (`?taulukko=…`).

1. Paina **Lähetä opettajalle**.
2. Ensimmäisellä kerralla peli kysyy **luokan** (esim. `5A`). Se muistetaan nimimerkille.
3. Peli kertoo, menikö tulos perille. Ilman verkkoa tulos jää jonoon ja lähtee myöhemmin.

Lähetetään vain nimimerkki, luokka ja kierroksen luvut (pelitapa, taso, aika, siirrot,
vihjeet), ei henkilötietoja. Taulukkosovelluksen (Google Apps Script) saa pelin tekijältä.
