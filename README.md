# hpvTim — Edukativna igra: Komunikacija o HPV vakcini

Interaktivna igra za radionice sa lekarima, zasnovana na **JitsuVax / HBM** metodologiji.
Cilj je vežbanje empatične i tačne komunikacije sa roditeljima koji imaju nedoumice oko HPV vakcine.

## Pokretanje

Nije potrebna instalacija ni internet. Dovoljno je otvoriti **`index.html`** u bilo kom
modernom pregledaču (Chrome, Edge, Firefox, Safari) — npr. dvoklikom na fajl.

Aplikacija je jedan samostalan HTML fajl (HTML + CSS + JavaScript, bez zavisnosti).

## Tok igre

1. **Podešavanje** — broj timova (2–5), imena timova i vreme za odgovor (30–120 s).
2. **Tabla** — leaderboard sa trenutnim rezultatom i indikatorom „na potezu”, mreža od 17 avatara.
3. **Potez** — facilitator otvara izjavu roditelja klikom na avatar; tim formuliše odgovor uživo dok teče tajmer.
4. **Bodovanje** — facilitator dodeljuje **0 / 1 / 2** poena prema kvalitetu odgovora.
5. **Kraj** — kada se iskoriste svi avatari (ili ručno), prikazuje se finalna tabela sa pobednikom.

Izjave su pri svakom startu nasumično raspoređene na avatare. Uz svaku izjavu postoji skrivena
**Pomoć za facilitatora** (HBM drajver i JitsuVax koren) koja se otkriva po potrebi.

## Bodovanje

| Poeni | Kriterijum |
|-------|------------|
| **0** | Napadački ton, pretežak medicinski žargon ili izazvan konflikt |
| **1** | Faktografski tačno, ali bez empatije / validacije zabrinutosti |
| **2** | Empatija i validacija + jasna, kratka i tačna informacija |
