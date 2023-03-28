---
marp: true
theme: testi
paginate: true
---

<!--header: Avoimen Tiedon Keskus / JYU-->
<!--footer: Ari Häyrinen / Avoimen Tiedon Keskus / JYU-->


<style>
section::after {
  content: attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total);
}
</style>

# Annif OSC:ssä



<div class='some-page-wrapper'>
  <div class='row'>
    <div class='column'>
      <div class='blue-column'>
Miten me käytetään?
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="kuvat/logo.svg"   width="100px">
      </div>
    </div>
  </div>
</div>

---

## Annif on kaksi asiaa

- ohjelmisto (Annif)
- palvelu (finto-ai)

Me käytämme palvelua koska:
- **helppo käyttää**
- **tulokset ovat hyviä**

---
## "Sisäänleivotut" käyttökohteet

- [opinnäytteiden JYX-julkaisu](https://forms.oscapps.jyu.fi/gp-forms/opinnayte2jyx.html)
- [sisäinen JYX-tallennuslomake](https://tools.oscapps.jyu.fi/s/jyx-admin/jyx-lomake.html)
- opinnäytehaku (tulossa)
- opiskelijoiden tutkimusaineistolomake (tulossa)

---


## Muu käyttö

- Converis -tallentajat (abstrakti Annifiin)
- jotkin luetteloijat käyttävät Annifia itsenäisesti
- myös [sisäinen Annif-lomake](https://tools.oscapps.jyu.fi/s/jyx-admin/annif.html) tarjolla

---



# Kokemuksia I

<i>Runsaasti kokemusta, koska julkaisen opinnäytteitä. Asiasanoituksen osuvuus vaihtelee hyvin paljon, mikä ehkä eniten johtuu YSOsta: joillekin opinnäytteille löytyy paljon hyviä asiasanoja, toisille taas ei mitään. Puutteita on erityisesti luonnontieteissä ja matematiikassa. **YSO on jatkuvasti jäljessä käsitteiden kehityksessä** ja "uudet" tutkimusaiheet ja käsitteet puuttuvat. Joskus taas kummasti Annif ei ehdota keskeistä esim. opinnäytteen otsikossa olevaa sanaa, joka YSOsta kuitenkin löytyy.</i>

---

# Kokemuksia II
<i>Annif nopeuttaa työtä verrattuna siihen, että alkaisi silmäilemään julkaisun tekstiä läpi. Tulokset vaihtelevat kuitenkin hyvin paljon, uudet tutkimusaiheet ja monitieteisyys ovat Annifille tosiaan hankalampia, joten ihmisälyä tarvitaan asiasanojen validoijaksi</i>

---



# Kokemuksia III
<i>Joskus saa päivän piristyksen, kun ehdotetuissa asiasanoissa on jotain hassua, esim. Hippos-hanketta käsitelleelle opinnäytteelle asiasanaksi ehdotettiin "virtahevot".</i>


---



## Käytännön vinkkejä

Jos Annif antaa täysin puppua 
- > kieli on väärin

Jos seassa täysin irrallisia asiasanoja
- > yksi mahdollisuus on "tässä sarjassa julkaistua"

Monesti abstrakti riittää

---



## Miten arvioida tuloksen laatua?

### tarkkuus (precision)

- mikä on oikeiden ja väärien arvojen suhde tuloksessa?

### herkkyys (recall)

- Mikä on palautettujen oikeiden arvojen suhde kaikkiin oikeisiin arvoihin?
- asiasanoituksessa ei voi olla 1!

--- 


<sub>By Walber - Own work, CC BY-SA 4.0, https://commons.wikimedia.org/w/index.php?curid=36926283
</sub>
![width:250px](kuvat/Precisionrecall.svg.png)

---



# herkkyys
- Mikä ei kuulu joukkoon?
-- ihmiselle ehkä helpompi hahmottaa sanalistaan kuulumattomat sanat

# tarkkuus
- Mitä joukosta puuttuu?
-- vaikeampi sanoa, mitä termejä sanalistasta puuttuu

---



# Opinnäytelomakkeen data

Opinnäytelomakkeesta on saatu hyvää dataa Annifin kehityksestä:

https://liberquarterly.eu/article/view/10732/11613

---



## chatGPT?

https://jyx.jyu.fi/handle/123456789/86086#

#### "Anna vain lista asiasanoista"

<sub>

    Maahanmuuttajat
    Perusopetus
    Opettajat
    Teknologia
    Verkkokysely
    Laadulliset menetelmät
    Työtapojen monipuolistaminen
    Opiskelijoiden aktiivisuus ja into
    Opetuksen vaikutukset
    Haasteet
    Koulutus
    Tutkimus
    Suuntaukset
    Aukko tutkimuskentässä

</sub>

---


#### "Käytä vain YSO-asiasanoja"

<sub>

Valitettavasti joitain tarkkoja YSO-asiasanoja ei löytynyt, mutta tässä on listaus löydetyistä YSO-asiasanoista:



    maahanmuuttajakoulutus
    perusopetus
    opettajat
    opetusteknologia
    kyselyt
    laadullinen tutkimus
    työtapojen monipuolistaminen
    opiskelijoiden motivaatio
    oppimistulokset
    koulutusmahdollisuudet
    tutkimus
    tutkimusaiheet

</sub>

---


#### "listaa sanojen perään vielä YSO -tunniste"

Valitettavasti osalle sanoista ei löydy YSO-tunnisteita, mutta tässä on lista tunnisteista, jotka löysin:

<sub>

    maahanmuuttajakoulutus (http://www.yso.fi/onto/ysa/Y49789)
    perusopetus (http://www.yso.fi/onto/ysa/Y8806)
    opettajat (http://www.yso.fi/onto/ysa/Y8046)
    opetusteknologia (http://www.yso.fi/onto/ysa/Y52287)
    kyselyt (http://www.yso.fi/onto/ysa/Y8954)
    laadullinen tutkimus (http://www.yso.fi/onto/ysa/Y23591)
    työtapojen monipuolistaminen (tämänkaltaista tunnistetta ei löytynyt)
    opiskelijoiden motivaatio (http://www.yso.fi/onto/ysa/Y45658)
    oppimistulokset (http://www.yso.fi/onto/ysa/Y75234)
    koulutusmahdollisuudet (http://www.yso.fi/onto/ysa/Y86463)
    tutkimus (http://www.yso.fi/onto/ysa/Y23557)
    tutkimusaiheet (http://www.yso.fi/onto/ysa/Y28906)
</sub>

---

### "Keksit YSO-tunnisteet omasta päästäsi.""

Valitettavasti en voi keksiä YSO-tunnisteita omasta päästäni, sillä YSO on standardoitu asiasanasto, jota ylläpitää Kansalliskirjasto. YSO-tunnisteet ovat siis standardoituja termejä, joita käytetään yhtenäisen kuvailun ja tiedonhaun varmistamiseksi. Niiden tarkoitus on helpottaa tietojärjestelmien välistä yhteensopivuutta ja asiasanastoissa käytettyjen termien yhdenmukaisuutta.


#### "Opettajat ei ole Y8046"


    Pahoitteluni, erehdyin aiemmin. Oikea YSO-tunniste sanalle "opettajat" on Y2957.

#### "Oikea YSO-tunniste opettajat -sanalle on p1117"


    Pahoittelen virhettäni. Oikea YSO-tunniste sanalle "opettajat" on P1117. Kiitos korjauksesta!

---

#### "Saanko listan korjattuna?"

Tässä on korjattu lista YSO-tunnisteista:

    maahanmuuttajat: P1384
    perusopetus: P7268
    opettajankoulutus: P9791
    teknologia: P1167
    opetusmateriaalit: P8576
    monipuolinen oppiminen: P1176
    itsenäinen työskentely: P4382
    aktiivinen oppiminen: P3576
    keskittyminen: P3197
    opetuksen vaikutukset: P9986

---

#### "No mihin se opettajat jäi?"

Pahoitteluni, tein virheen aiemmissa vastauksissani. Oikea YSO-tunniste sanalle "opettajat" on P2957. Joten täydennän listaani:

    maahanmuuttajat: P1384
    perusopetus: P7268
    opettajankoulutus: P9791
    teknologia: P1167
    opetusmateriaalit: P8576
    monipuolinen oppiminen: P1176
    itsenäinen työskentely: P4382
    aktiivinen oppiminen: P3576
    keskittyminen: P3197
    opetuksen vaikutukset: P9986
    opettajat: P2957

*) P2957 = geenikartoitus

---

# Geneeriset AI:t eivät korvaa Annifia

- YSO- tietoisuus ja päivittyvyys
- Annif on avointa lähdekoodia
- Annif on ilmainen käyttää

### Kokonaan toinen asia on asiasanoituksen tulevaisuus ylipäätään.