# Edukativna igra: Komunikacija o HPV vakcini sa roditeljima

## Dizajn i tok igre za fasilitatora (voditelja)

Ova aplikacija/igra je dizajnirana za radionice sa lekarima. Prikazuje se na velikom ekranu, dok fasilitator kontroliše unos sa svog uređaja.

### Faza 1: Podešavanje igre (Setup Screen)
* **Izbor igrača/timova:** Padajući meni za odabir broja timova (od 2 do 5).
* **Unos imena:** Tekstualna polja gde fasilitator upisuje imena timova (npr. "Tim Pedijatri", "Tim Ginekolozi").
* **Dugme:** "Započni igru".

### Faza 2: Glavna tabla (The Board)
* **Gornji deo ekrana (Leaderboard):** Tabela koja stalno prikazuje trenutni broj poena svakog tima. Pored imena tima čiji je trenutno red stoji indikator.
* **Centralni deo ekrana (Avatari):** Mreža od 17 avatara (npr. smajliji sa različitim izrazima lica ili kartice sa brojevima od 1 do 17). 
* *Mehanika:* Svaki avatar je nasumično povezan sa jednom od 17 izjava (randomizacija se dešava pri startu igre).

### Faza 3: Potez i diskusija (Gameplay)
1. Fasilitator proziva tim koji je na potezu.
2. Tim bira avatar.
3. Fasilitator klikće na izabrani avatar.
4. **Pop-up prozor (Modal):** Preko ekrana se otvara veliki prozor sa tekstom izjave roditelja. 
5. Tim ima zadatak da verbalno formuliše odgovor (uživo u prostoriji). Ograničenje je npr. 60 sekundi.

### Faza 4: Ocenjivanje (Scoring)
Fasilitator na svom ekranu dodeljuje poene nakon izlaganja tima:
* **0 poena:** Odgovor je bio napadački, korišćen je pretežak medicinski žargon, ili je izazvan konflikt.
* **1 poen:** Odgovor je faktografski tačan, ali je izostala empatija ili validacija zabrinutosti roditelja (čisto "izbacivanje" podataka).
* **2 poena:** Odličan odgovor. Tim je prvo primenio empatiju/validaciju, a zatim dao jasnu, kratku i tačnu informaciju u skladu sa JitsuVax metodologijom.

* Nakon bodovanja, pop-up se zatvara, poeni se dodaju na tabelu, a iskorišćeni avatar postaje neaktivan. Red prelazi na sledeći tim.

### Faza 5: Kraj igre
* Igra se završava kada se otvore svi avatari ili istekne vreme. Prikazuje se finalna tabela sa pobednikom.

---

## Baza scenarija sa mapiranim korenima (HBM i JitsuVax)

**1. Tajming i odlaganje**
> "Doktore, zar nije rano da moje dete sada primi vakcinu? Još uvek je mala i ne razmišlja o tim stvarima. Zašto da žurimo? Zar nije logičnije da joj damo tu vakcinu kada se približi vreme, kad to postane kritično?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija osetljivosti (Roditelj misli da dete trenutno nije ugroženo niti osetljivo na infekciju).
> * **JitsuVax Koren:** *Distorted risk perception* (Iskrivljena percepcija rizika – nerazumevanje koncepta profilakse i tajminga imunološkog odgovora pre izlaganja).

**2. Kondom kao zamena**
> "Slušala sam neke doktore i zar nije jedina zaštita od HPV-a korišćenje kondoma tokom seksualnih odnosa? Ne vidim razlog zašto bismo dete izlagali vakcini, kad je kondom osnovna i sasvim dovoljna zaštita."
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija koristi (Roditelj ne vidi dodatnu korist vakcine naspram mehaničke zaštite).
> * **JitsuVax Koren:** *Unwarranted beliefs* (Neosnovana uverenja – lažna ekvivalencija zaštite kondomom i potpunog imuniteta).

**3. Vakcinacija dečaka**
> "Zašto mi preporučujete ovu vakcinu za sina? Mislila sam da HPV izaziva samo rak grlića materice i da je ovo vakcina isključivo namenjena devojčicama. Koja je svrha da je on primi?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija osetljivosti (Roditelj veruje da dečaci nisu osetljivi na bolest).
> * **JitsuVax Koren:** *Distorted risk perception* (Iskrivljena percepcija rizika – nedostatak informacija o širini patologije koju virus izaziva kod oba pola).

**4. Sumnja u efikasnost (broj tipova)**
> "Čula sam na televiziji da postoji preko 1000 tipova HPV-a. Ako ih ima toliko mnogo, koja je onda uopšte poenta ove vakcine? Zar nije besmisleno štititi se od samo nekoliko tipova kada je virus toliko rasprostranjen?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija koristi (Sumnja da delimično pokriće tipova donosi ikakvu stvarnu korist).
> * **JitsuVax Koren:** *Epistemic relativism* (Epistemički relativizam – oslanjanje na površne informacije iz medija umesto na razumevanje koji tačno genotipovi izazivaju karcinom).

**5. Brzina razvoja bolesti**
> "Negde sam pročitala da je 6 do 12 meseci sasvim dovoljno da dođe do promena na grliću materice. Ako se to tako brzo razvija, zar nije onda bolje i sigurnije da ona ide na redovne preglede kod ginekologa, umesto da prima vakcinu?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija koristi i Percepcija ozbiljnosti (Sekundarna prevencija se doživljava kao dovoljna, umanjujući ozbiljnost patologije).
> * **JitsuVax Koren:** *Unwarranted beliefs* (Neosnovana uverenja – nerazumevanje razlike između primarne prevencije i lečenja posledica).

**6. Trajanje imuniteta**
> "Znam neke žene koje su primile vakcinu pre 7-8 godina i vidim da to nije baš tako pouzdano kako se priča. Ako moja ćerka primi vakcinu sada sa 11 godina, da li će to uopšte delovati kada bude imala 28 ili 38 godina? Da li će morati stalno da prima nove doze?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija koristi (Sumnja u dugoročnu isplativost i trajanje zaštite).
> * **JitsuVax Koren:** *Epistemic relativism* (Epistemički relativizam – stavljanje anegdotskih iskustava ispred kliničkih studija).

**7. Spontano čišćenje virusa**
> "Čitala sam da najveći broj zaraženih osoba zapravo nikada ni ne dobije simptome i da čak 9 od 10 infekcija prođe spontano, samo od sebe, u periodu od dve godine. Zašto onda da izlažem dete vakcini, ako organizam to očigledno može sam da reši?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija ozbiljnosti (Ako većina preleži bez posledica, onda sama infekcija nije ozbiljna pretnja).
> * **JitsuVax Koren:** *Distorted risk perception* (Iskrivljena percepcija rizika – previđanje onog malog, ali fatalnog procenta kod koga se razvije karcinom).

**8. Hirurško lečenje kao alternativa**
> "Neki ginekolozi kažu da se kondilomi, pa čak i teže promene poput CIN 2 i 3, lako uklanjaju intervencijom. Ako to može tako rutinski da se reši i skine, da li je zaista neophodno da prima vakcinu?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija ozbiljnosti (Hirurgija je "laka", pa bolest nije ozbiljna).
> * **JitsuVax Koren:** *Distorted risk perception* (Iskrivljena percepcija rizika – drastično potcenjivanje stresa, bola i rizika operativnih zahvata na grliću materice).

**9. Strah od neželjenih efekata**
> "Iskreno, jako se plašim neželjenih reakcija i njene dugoročne bezbednosti. Koliko je ova vakcina uopšte dugo na tržištu i ko je proizvodi? Nemam dovoljno informacija o tome kakva su iskustva u drugim zemljama da bih bila mirna."
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija prepreka (Strah od nepoznatog i nuspojava deluje kao ogromna barijera za prihvatanje).
> * **JitsuVax Koren:** *Fear and phobias* (Strahovi i fobije – anksioznost usled nedostatka informacija o sigurnosnom profilu).

**10. Stigma (neće se desiti mom detetu)**
> "Ja vrlo dobro poznajem i vaspitavam svoje dete. Sigurna sam da ona neće doći u situaciju da dobije seksualno prenosivu bolest. Mislim da vakcina za ovu vrstu bolesti nama jednostavno nije potrebna."
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija osetljivosti (Potpuno negiranje rizika jer se dete doživljava kao "sigurno").
> * **JitsuVax Koren:** *Moral concerns* (Moralne brige – povezivanje infekcije sa "lošim vaspitanjem" ili promiskuitetom, želja za očuvanjem čistote deteta).

**11. Fertilitet**
> "Svašta se priča o ovoj vakcini i najviše me brine kako će ona uticati na njeno zdravlje kasnije u životu. Mene zanima da li ova vakcina može da izazove probleme sa fertilitetom i da li će ona moći da ima decu bez problema ako je sada primi?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija prepreka (Strah od ugrožavanja reproduktivnog zdravlja stvara snažan otpor).
> * **JitsuVax Koren:** *Fear and phobias* / *Unwarranted beliefs* (Strahovi potpomognuti specifičnim, čestim dezinformacijama i teorijama o sterilizaciji).

**12. Sastav vakcine**
> "Zabrinuta sam šta se sve tačno nalazi u toj vakcini. Stalno čitamo o raznim dodacima i aluminijumu u vakcinama. Da li je zaista bezbedno da se takav sastav ubrizgava mom detetu koje je još uvek u razvoju?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija prepreka (Briga o unosu nepoznatih ili "toksičnih" supstanci).
> * **JitsuVax Koren:** *Fear and phobias* (Strah od hemije/toksina – "Toxophobia").

**13. Nepoverenje u statistiku**
> "Iskreno, apsolutno mi zvuči netačno da smo mi baš u vrhu po statistici za rak grlića materice. Pričala sam sa nekim ljudima, pa i lekarima, koji kažu da se to preuveličava i da oni veruju samo u svoje lično iskustvo. Zašto bih ja sada slepo verovala tim brojkama?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija ozbiljnosti (Negiranje nacionalnog zdravstvenog problema na nivou cele populacije).
> * **JitsuVax Koren:** *Epistemic relativism* (Epistemički relativizam – selektivno odbacivanje zvaničnih statističkih podataka u korist pristrasnog ličnog iskustva).

**14. Nedovoljna svest o drugim kancerima**
> "Shvatam da ova vakcina štiti od raka grlića materice, ali stalno potencirate da treba i dečaci da je prime. Koji to tačno rak dečaci uopšte mogu da dobiju od HPV-a? Nikad nisam čula da muškarci imaju ozbiljne posledice, osim eventualno nekih bradavica."
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija ozbiljnosti i Percepcija osetljivosti (Verovanje da muški pol ne snosi teške posledice).
> * **JitsuVax Koren:** *Distorted risk perception* (Iskrivljena percepcija rizika zbog manjka informisanosti o karcinomima usne duplje, anusa, penisa itd.).

**15. Uticaj na pubertet**
> "Ona je sada u najosetljivijem periodu, tek ulazi u pubertet i hormoni joj se jako menjaju. Plašim se da bi ova vakcina mogla nekako da poremeti njen prirodni razvoj. Da li je zaista pametno davati joj ovako nešto baš sada kada joj se telo toliko menja?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija prepreka (Strah od ometanja fiziološkog razvoja).
> * **JitsuVax Koren:** *Unwarranted beliefs* (Neosnovana uverenja – povezivanje imunološkog odgovora sa endokrinim/hormonalnim promenama).

**16. Iskustvo iz inostranstva vs. mi**
> "Zanima me koliko je ova vakcina zapravo testirana kod nas? Znam da pričate da to daju u inostranstvu, ali ko nam garantuje da je to dobro i za našu decu? Koliko je uopšte dugo ova vakcina na tržištu?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija prepreka (Nepoverenje u lokalni zdravstveni sistem stvara barijeru).
> * **JitsuVax Koren:** *Epistemic relativism* (Epistemički relativizam uz blagi prizvuk sumnje u motive institucija).

**17. Normalizacija virusa**
> "Čitala sam da preko 80% ljudi ionako pre ili kasnije dođe u kontakt sa ovim virusom i da većina nosi HPV. Ako je to toliko uobičajeno i normalno, zašto pravimo toliku paniku i moramo decu da vakcinišemo? Zar se ne stiče neki prirodni imunitet?"
> 
> 💡 **Pomoć za fasilitatora:**
> * **HBM Drajver:** Percepcija ozbiljnosti (Smatranje da "sveprisutnost" virusa znači da je on bezopasan).
> * **JitsuVax Koren:** *Distorted risk perception* (Iskrivljena percepcija rizika i privlačnost ideje o prirodnom imunitetu "krda").
