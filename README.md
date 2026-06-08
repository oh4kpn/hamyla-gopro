# Hamyla GoPro Hero 10 Blacks - Moottoripyöräilyasetukset (Optimoidut)

Tämä asetussivu on optimoitu vauhdikkaaseen moottoripyöräkuvaukseen (kypärä- ja tankokiinnitykset). Asetusten tavoitteena on estää taivaan puhkipalaminen, säilyttää vauhdintunne ja varmistaa sujuva editointi nykyaikaisilla laitteilla (esim. Apple M2 tai tehokkaat PC-läppärit).

## 🎥 Perusasetukset (Video Settings)

| Asetus | Arvo | Kuvaus |
| :--- | :--- | :--- |
| **Resoluutio & FPS** | `4K / 60` | Optimaalinen suhde tarkkuutta ja sulavaa liikettä. (Johtuen firmiksen ominaisuuksista välkynnänesto pitää pakottaa 60Hz, muutoin hertsit ei sovi monitoreilla katseluun) |
| **Linssi (Lens)** | `SuperView` | Laajentaa näkymää pysty- ja sivusuunnassa. Tuo tankoa ja mittaristoa kuvaan korostaen vauhtia. |
| **Vakaus (HyperSmooth)** | `Standard` | Riittävä vakaus maantieajoon ilman, että kuvaa rajataan (cropataan) liikaa. |
| **Videon pakkaus** | `HEVC` | Älykäs ja tilaa säästävä pakkausmuoto. Vaatii modernin editointikoneen. |

---

## 🛠️ Protune-asetukset (Valotus & Värit)

Nämä asetukset ajetaan sisään manuaalisesti, jotta kamera ei tee virhevalotuksiaan.

*   **Valotuksen korjaus (EV Comp):** `-1.0`  
    > ☀️ **Tärkein asetus:** Pakottaa kameran alivalottamaan kuvaa hieman. Tämä pelastaa taivaan ja pilvien yksityiskohdat kirkkaassa päivänvalossa. Varjoja voi tarvittaessa avata jälkikäteen editoinnissa.
*   **ISO Min:** `100`  
    *   Alin mahdollinen herkkyys puhtaalle kuvalle aurinkoisella säällä.
*   **ISO Max:** `800`  
    *   Estää kameraa nostamasta herkkyyttä liian korkeaksi hämärissäkään kohdissa (esim. metsätaipaleet tai sillat), mikä pitää kuvan vapaana digitaalisesta kohinasta.
*   **Bittinopeus (Bit Rate):** `Normal`  
    *   Erinomainen kompromissiratkaisu, joka säästää muistikorttitilaa pitkillä ajopätkillä kuvanlaadun kärsimättä.
*   **Väri (Color):** `Natural`  
    *   Tuottaa realistiset ja tasapainoiset värit suoraan kamerasta ilman "Vibrant"-tilan ylikorostettuja, puhkeavia sävyjä.
*   **Terävyys (Sharpness):** `Medium`  
    *   Poistaa digitaalisen yliterävyyden ja tekee videosta luonnollisemman ja elokuvallisemman näköisen.

---

## 💡 Vinkkejä editointiin
Koska videomuotona on **HEVC**, editointi sujuu parhaiten laitteilla, joista löytyy rautatason HEVC-dekoodaus (esim. Apple M2 -sirun *Media Engine* tai 2000 luvun Intel/AMD-prosessorit). Jos huomaat videon pätkivän editointiohjelmassa, käytä ohjelman sisäisiä **Proxy-tiedostoja** (kevennettyjä vastineita) editoinnin ajaksi.
