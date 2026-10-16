# Yhtälövaaka

**Pelaa selaimessa: https://kijuku.github.io/Yhtalovaaka-game/**

Ensimmäisen asteen yhtälö kallistuvana vaakana – kuka ratkaisee nopeimmin? Toimii
tietokoneella, tabletilla ja Chromebookilla ilman asennusta.

Vaa'alla **sininen laatikko on x**, **oranssi punnus 1** ja **punainen ilmapallo −1**. Tee sama
siirto molemmille puolille, kunnes vaa'alla on **x = luku**.

Tarkempi ohje: **[PELIOHJE.md](PELIOHJE.md)**

## Pelitavat ja tasot

| Pelitapa | Tavoite |
|---|---|
| **Pikakisa** | 5 yhtälöä mahdollisimman nopeasti |
| **Sprintti** | 10 yhtälöä mahdollisimman nopeasti |
| **Aikakisa** | Montako yhtälöä ratkaiset 3 minuutissa |
| **Harjoittelu** | Ei kelloa – kokeile siirtoa vain toiselle puolelle, niin näet vaa'an kallistuvan |

| Taso | Esimerkki |
|---|---|
| **Helppo** | `x + 4 = 9`, `3x = 12` |
| **Keskitaso** | `2x + 3 = 11`, `5x − 2 = 2x + 7` |
| **Vaikea** | `4x − 1 = 2x + 5`, `2(x + 3) = x + 8` |

## Näin pelaat

1. Kirjoita **luku tai x-termi**, esim. `3`, `2x` tai `x`.
2. Valitse toiminto: **+** lisää, **−** vähentää, **·** kertoo, **:** jakaa – molemmilta puolilta.
3. Näppäimistöllä: numerot ja `x`, sitten `+ - * /`. **Z** kumoaa, **H** antaa vihjeen
   (kisoissa vihje lisää aikaan 10 s).

Tulosnäytöllä näet ajan, siirtojen määrän verrattuna parhaaseen mahdolliseen sekä
**taitokartan**: mitkä yhtälötyypit sujuvat ja mitä kannattaa harjoitella. Peli antaa
vaikeita tyyppejä useammin.

## Nimimerkki ja kunniataulu

Pelaa omalla **nimimerkillä**. Kunniataulussa ovat jokaisen pelitavan ja tason kymmenen
parasta. Tiedot tallentuvat vain omaan selaimeen.

## Opettajalle: tulokset Google Sheetsiin

Oppilaat avaavat pelin opettajan antamalla linkillä:

```
https://kijuku.github.io/Yhtalovaaka-game/?taulukko=<opettajan taulukkosovelluksen osoite>
```

Tulosnäytölle tulee **Lähetä opettajalle** -nappi, ja oppilas kirjoittaa kerran luokkansa
(esim. 5A). Taulukkoon tallentuu vain nimimerkki, luokka ja pelin luvut – ei henkilötietoja.
Taulukkosovelluksen (Google Apps Script) saa pelin tekijältä.

## Tietoa

- Tehty Unity 6:lla (WebGL). Lähdekoodi ei ole julkinen.
- Toimii kokonaan selaimessa, ei evästeitä eikä seurantaa.
- Sama tekijä: [Kertolaskukisa](https://kijuku.github.io/MultiplyGame/).
