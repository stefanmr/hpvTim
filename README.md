# hpvTim — Edukativna igra: Komunikacija o HPV vakcini

Interaktivna igra za radionice sa lekarima, zasnovana na **JitsuVax / HBM** metodologiji.
Cilj je vežbanje empatične i tačne komunikacije sa roditeljima koji imaju nedoumice oko HPV vakcine.

## Pokretanje

Nije potrebna instalacija ni internet. Dovoljno je otvoriti **`index.html`** u bilo kom
modernom pregledaču (Chrome, Edge, Firefox, Safari) — npr. dvoklikom na fajl.

Aplikacija je jedan samostalan HTML fajl (HTML + CSS + JavaScript, bez zavisnosti).

## Tok igre

1. **Podešavanje** — broj timova (2–10), imena timova, vreme za odgovor (30–120 s, podrazumevano 90 s) i pokretanje tajmera (automatski po izboru avatara — podrazumevano — ili ručno, dugmetom facilitatora).
2. **Tabla** — leaderboard sa trenutnim rezultatom i indikatorom „na potezu”, mreža od 20 avatara.
3. **Potez** — facilitator otvara izjavu roditelja klikom na avatar; tim formuliše odgovor uživo dok teče tajmer.
4. **Bodovanje** — facilitator dodeljuje **0 / 1 / 2** poena prema kvalitetu odgovora.
5. **Kraj** — kada se iskoriste svi avatari (ili ručno), prikazuje se finalna tabela sa pobednikom.

Izjave su pri svakom startu nasumično raspoređene na avatare. Uz svaku izjavu postoji skrivena
**Pomoć za facilitatora** (HBM drajver i JitsuVax koren) koja se otkriva po potrebi.

**Tema:** prekidačem u donjem desnom uglu (🌙 / ☀️) može se uključiti **svetla tema visokog
kontrasta** — korisno za projektore i osvetljene prostorije. Izbor se pamti za sledeće otvaranje.

## Bodovanje

| Poeni | Kriterijum |
|-------|------------|
| **0** | Napadački ton, pretežak medicinski žargon ili izazvan konflikt |
| **1** | Faktografski tačno, ali bez empatije / validacije zabrinutosti |
| **2** | Empatija i validacija + jasna, kratka i tačna informacija |

## Izmena scenarija (fino podešavanje)

Sve izjave roditelja žive kao običan tekst unutar fajla **`index.html`**, pa je najlakše
direktno izmeniti taj fajl u bilo kom tekst editoru (TextEdit u *plain text* režimu, VS Code,
Sublime, ili GitHub web editor).

1. Otvoriti `index.html` i pronaći blok `const SCENARIOS` (oko 313. linije).
2. Svaki scenario je jedan blok od četiri polja:

   ```js
   {t:"Fertilitet dečaka",
    q:"A šta je sa mojim sinom — može li mu ova vakcina naškoditi...",
    hbm:"Percepcija prepreka — strah od ugrožavanja buduće plodnosti...",
    jv:"Fear and phobias / Unwarranted beliefs — dezinformacije..."},
   ```

   - `t` = naslov u zaglavlju izjave
   - `q` = izjava roditelja (ono na šta timovi odgovaraju)
   - `hbm` = Health Belief Model napomena (pomoć za facilitatora)
   - `jv` = JitsuVax drajver napomena (pomoć za facilitatora)

3. Menja se **samo tekst između navodnika**. Sačuvati fajl i otvoriti `index.html` dvoklikom
   u pregledaču — nema build koraka ni servera.

**Tri pravila da se fajl ne pokvari:**

- **Ne dirati strukturu** — ne brisati `"`, `:`, `{ }`, ni zarez posle svakog bloka
  (svaki scenario se završava sa `},` osim poslednjeg, koji se završava samo sa `}`).
- **Ne kucati prav dvostruki navodnik `"` unutar teksta** — on prekida string i kvari fajl.
  Za navodnike unutar teksta koristiti zakrivljene: `„ ”` (zato ih postojeći scenariji koriste).
- **Za dodavanje scenarija** kopirati ceo `{...},` blok, nalepiti ga i izmeniti tekst — a ako
  se promeni broj scenarija, dodati još jedan emoji u listu `FACES = [...]` (oko 396. linije)
  da broj avatara ostane usklađen sa brojem scenarija.
