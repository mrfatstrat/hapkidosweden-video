# Produktionsguide: Redigering och efterproduktion
## Promotionvideo for Hapkido Sverige (WKF/Hanminjok)

> **Slutresultat:** En 60-sekunders video i 16:9 (liggande) samt en 20-30-sekunders version i 9:16 (staende, for TikTok/Reels).
> Ingen voice-over -- enbart musik och text pa skarmen.

---

## Innehallsforteckning

1. [Redigeringsprogram](#1-redigeringsprogram)
2. [Projektuppstart](#2-projektuppstart)
3. [Klippning](#3-klippning)
4. [Slowmotion i redigering](#4-slowmotion-i-redigering)
5. [Musik och ljud](#5-musik-och-ljud)
6. [Textoverlagg och grafik](#6-textoverlagg-och-grafik)
7. [Fargkorrigering och grading](#7-fargkorrigering-och-grading)
8. [Exportinstallningar per plattform](#8-exportinstallningar-per-plattform)
9. [Publiceringstips](#9-publiceringstips)

---

## 1. Redigeringsprogram

Det finns flera bra alternativ som antingen ar gratis eller billiga. Har ar en oversikt.

### CapCut (REKOMMENDERAS for detta projekt)

- **Pris:** Gratis (Pro-version finns men behovs inte)
- **Plattform:** Windows, Mac, iOS, Android, webbversion
- **Fordelar:**
  - Extremt nyborrjarvanligt -- du kan komma igang pa minuter
  - Inbyggda textmallar och animationer
  - Bra slowmotion- och speed ramp-verktyg
  - Enkel beat-synkning med musik
  - Kan exportera bade 16:9 och 9:16 fran samma projekt
  - Massor av gratiseffekter och overgangar
- **Nackdelar:**
  - Mindre kontroll over fargkorrigering an DaVinci Resolve
  - Exportkvalitet nagot lagre an professionella verktyg
  - Kinesisktagt foretag (ByteDance/TikTok) -- tankvart om integritet ar viktigt
- **Bast for:** Nyborrjare som vill ha snabbt resultat

### DaVinci Resolve

- **Pris:** Gratis (Studio-version kostar ca 2 900 kr men behovs inte)
- **Plattform:** Windows, Mac, Linux
- **Fordelar:**
  - Branschstandard for fargkorrigering
  - Mycket kraftfullt -- inga begransningar i gratisversionen for detta projekt
  - Professionell export med full kontroll
  - Fusion-sidan for avancerad grafik
- **Nackdelar:**
  - Brant inlarningskurva -- kan kanna sig overvalmingande
  - Kraver en hyfsat kraftfull dator
  - Storre program (ca 2-3 GB nedladdning)
- **Bast for:** Den som vill lara sig ett "riktigt" redigeringsprogram

### iMovie

- **Pris:** Gratis (foljder med Mac och iPhone)
- **Plattform:** Mac, iPhone, iPad
- **Fordelar:**
  - Redan installerat pa Apple-enheter
  - Extremt enkelt
  - Bra integration mellan iPhone och Mac
- **Nackdelar:**
  - Begransade textmojligheter (stort problem for detta projekt)
  - Ingen 9:16-export inbyggt -- kraver workaround
  - Fa overgangar och effekter
  - Ingen speed ramping
- **Bast for:** Snabb enkel redigering pa Mac/iPhone, men INTE idealt for detta projekt

### Jamforelsetabell

| Funktion | CapCut | DaVinci Resolve | iMovie |
|---|---|---|---|
| Svarighetsgrad | Latt | Svart | Mycket latt |
| 9:16-export | Ja, enkelt | Ja, med setup | Nej (workaround) |
| Textanimationer | Manga inbyggda | Manga (men manuellt) | Mycket begransade |
| Speed ramping | Ja, enkelt | Ja, avancerat | Nej |
| Fargkorrigering | Grundlaggande | Branschledande | Minimal |
| Beat-synkning | Automatisk funktion | Manuellt | Manuellt |
| Exportkvalitet | Bra | Utmarkt | Bra |
| Pris | Gratis | Gratis | Gratis |

### Rekommendation for detta projekt

**Anvand CapCut Desktop** som forstahandsval. Anledningar:

1. Du far snabbt resultat utan att behova lara dig ett komplext program.
2. Inbyggd beat-synkning sparar mycket tid.
3. Enkel vaxling mellan 16:9 och 9:16.
4. Textanimationer som ser professionella ut ar bara nagra klick bort.

Om du vill ha battre fargkorrigering eller planerar att gora mer video i framtiden -- valj DaVinci Resolve, men rakna med att lagga nagra extra timmar pa att lara dig programmet.

> **Resten av guiden visar steg i CapCut Desktop, men principerna ar desamma i alla program.**

---

## 2. Projektuppstart

### Steg 1: Ladda ner och installera CapCut Desktop

1. Ga till [capcut.com](https://www.capcut.com/) och ladda ner desktopversionen.
2. Installera och oppna programmet.
3. Skapa ett gratiskonto (du kan anvanda Google-inloggning).

### Steg 2: Organisera ditt material INNAN du borjar

Skapa foljande mappstruktur pa din dator:

```
hapkido-promo/
├── ratt-material/          (alla videoklipp fran filmningen)
│   ├── klubb-stockholm/
│   ├── klubb-goteborg/
│   └── klubb-malmo/
├── musik/                  (musikfiler)
├── grafik/                 (logotyper, bilder)
│   ├── wkf-logotyp.png
│   └── hapkido-korea-text.png
├── typsnitt/               (nedladdade typsnitt)
└── export/                 (har hamnar fardig video)
```

**Namge klipp beskrivande.** Ist for `IMG_4523.mov`, dop om till exempelvis:
- `stockholm-spark-narbild-01.mov`
- `goteborg-kast-helkropp-02.mov`
- `malmo-grupp-stretching-01.mov`

Det tar lite tid men sparar ENORMT mycket tid nar du redigerar.

### Steg 3: Skapa projekt i CapCut

**For 16:9-versionen (60 sekunder):**

1. Oppna CapCut Desktop och klicka **"New project"**.
2. Langst upp i forhands-granskningsfonstret, klicka pa formatknappen.
3. Valj **16:9**.
4. Under projektinstallningar, kontrollera:
   - **Upplosning:** 1920x1080 (1080p) eller 3840x2160 (4K om materialet ar i 4K)
   - **Bildfrekvens (FPS):** 25 fps (europeisk standard) eller 30 fps (om materialet ar filmat i 30 fps)

**For 9:16-versionen (20-30 sekunder):**

1. Nar 16:9-versionen ar klar, klicka **"File" > "New project"**.
2. Valj format **9:16**.
3. Samma upplosning och FPS som ovan.

> **Tips:** Borja alltid med 16:9-versionen. Det ar lattare att korta ner och anpassa for 9:16 an tvartom.

### Steg 4: Importera material

1. Klicka pa **"Import"** langst upp till vanster.
2. Valj alla videoklipp, musikfiler och grafik.
3. Materialet dyker upp i mediabiblioteket.
4. I CapCut kan du skapa mappar i mediabiblioteket -- gor det for att spegla din mappstruktur.

### Steg 5: Kontrollera bildfrekvens pa materialet

Hogerkicka pa ett klipp i mediabiblioteket och valj **"Properties"** eller **"Clip info"**.

- Klipp filmade i **24/25/30 fps** = vanliga klipp
- Klipp filmade i **120 fps eller 240 fps** = slowmotion-material

Markera eller lagg slowmotion-klipp i en egen mapp. Du kommer behova dem senare.

---

## 3. Klippning

### Grundlaggande klippteknik

**Vad ar en tidslinje?**
Tidslinjen ar det langa faltet langst ner i redigeringsprogrammet. Har placerar du dina klipp i ordning, fran vanster till hoger. Vanster = borjan av videon, hoger = slutet.

**Sa har gor du:**

1. **Dra ett klipp** fran mediabiblioteket ner till tidslinjen.
2. **Forkorta klippet** genom att dra i kanterna (vanster kant = startpunkt, hoger kant = slutpunkt).
3. **Klipp/dela** ett klipp genom att placera uppspelningshuvudet (den vertikala linjen) dar du vill klippa och tryck **Ctrl+B** (Windows) eller **Cmd+B** (Mac).
4. **Ta bort** oonskat material genom att markera det och trycka **Delete**.
5. **Flytta klipp** genom att dra dem till en ny position.

### Klippa i takt med musiken (beat-synkning)

Det har ar NYCKELN till att videon ska kanna sig professionell.

**I CapCut (automatisk metod):**

1. Dra din musikfil till tidslinjen (ljudsparet, under videosparet).
2. Markera musikklippet.
3. Klicka pa **"Auto beat"** i verktygsfraltet (eller hogerkicka > "Beat detection").
4. Valj **"Beat 1"** (markerar huvudbeats) eller **"Beat 2"** (markerar fler beats).
5. Gula markeringar dyker upp pa musiksparet -- det ar takterna.
6. Klipp dina videoklipp sa att varje nytt klipp borjar pa en gul markering.

**Manuell metod (alla program):**

1. Spela musiken och tryck **M** (eller markorknapppen) varje gang du hor en tydlig beat.
2. Nu har du markeringar langs tidslinjen.
3. Placera klippbyten pa dessa markeringar.

> **Tips:** Du behover INTE byta klipp pa varje beat. Varannan eller var fjarde beat kanns ofta mer naturligt. Lat kasnlan av musiken styra.

### Hur man skapar varierat tempo

Videon ska folja en dramatisk kurva. Har ar strukturen for 60-sekundersversionen:

```
00-10s: LUGNT
  Vida bilder, langsammare klipp, ev. slowmotion
  Bygger stormning och mystik

10-25s: BYGGANDE
  Klipptempot okar gradvis
  Blandning av teknik och tranining

25-45s: INTENSIVT
  Snabba klipp, actionfyllt
  Sparkar, kast, sjalvforsvar
  Kortast klipplangd har

45-55s: GEMENSKAP
  Aterga till lugnare tempo
  Grupp, gemenskap, gladje

55-60s: AVSLUT
  Logotyp + hemsida + 합기도
```

### Overgangar

**Anvand dessa (sparksamt):**

| Overgang | Nar | Hur |
|---|---|---|
| **Hard klipp (straight cut)** | 90 % av alla klippbyten | Bara klipp -- ingen effekt. Ser mest professionellt ut. |
| **Cross dissolve** | Overgangen mellan lugna sektioner | 0.5-1 sekund. Anvand for att visa att tid passerar eller byta plats. |
| **Smash cut** | Fran lugnt till intensivt | Direkt hard klipp fran ett stilla moment till action. Skapar energi. |
| **Dip to black** | Mellan tydliga sektioner | 0.3-0.5 sekund. Kort svart mellanrum. |
| **Fade in / fade out** | Start och slut av videon | 1-2 sekunder. |

**UNDVIK dessa:**

- Star wipe, hjart-overgang, sidan-overgang
- 3D-overgangar och "fancy" effekter
- Allt som ser ut som en PowerPoint-presentation
- Allt som distraherar fran innehallet

> **Tumregel:** Om du maste fundera pa vilken overgang du ska anvanda -- ta en hard klipp.

### Klipplangd: tumregler

| Typ av shot | Klipplangd | Exempel |
|---|---|---|
| Vid/etableringsbild | 3-5 sekunder | Bild av traningslokalen utifraan |
| Medelshot (teknik) | 2-3 sekunder | Person som visar en teknik |
| Narbild | 1-2 sekunder | Hander som griper, fotarbete |
| Action/snabb sekvens | 0.5-1 sekund | Spark, kast, nedlaggning |
| Text pa skarm | 2-3 sekunder (kort text), 4-5 sekunder (langer text) | "Hapkido -- Sjalvforsvar for alla" |

### Hur du skapar bra "flow"

1. **Variera bildstorlek.** Ga fran vid bild till narbild till medelshot. Klipp ALDRIG tva likadana bildstorlekar efter varandra (t.ex. tva narbilder i rad).
2. **Folj rorelsens riktning.** Om nagon sparkar at hoger i ett klipp, lat nasta klipp ha rorelse at vanster. Det skapar dynamik.
3. **Klipp pa rorelse.** Klipp mitt i en rorelse, inte for eller efter. Hjarnan fyller i resten -- det kanns smidigt.
4. **Blanda klubbar.** Varva material fran olika klubbar sa att det kanns som en gemensam organisation, inte en enskild klubb.
5. **Undvik upprepning.** Visa inte tva liknande sparkar eller kast i rad. Sprid ut likartade tekniker.

---

## 4. Slowmotion i redigering

### Anvanda slowmotion-material (120fps / 240fps)

Material filmat i hog bildfrekvens ar avsett for slowmotion. Sa har anvander du det:

**Forsta: forsta matematiken:**

- Din tidslinje ar 25 fps.
- Ett klipp filmat i 120 fps kan spelas upp i 120/25 = **ca 5x slowmotion** utan att det hackar.
- Ett klipp filmat i 240 fps kan spelas upp i 240/25 = **ca 10x slowmotion**.

**I CapCut:**

1. Dra slowmotion-klippet till tidslinjen.
2. Markera klippet.
3. Klicka pa **"Speed"** i verktygsfraltet.
4. Valj **"Normal"** och dra reglagen till vanster (t.ex. 0.2x for 5x slowmotion).
5. Bocka i **"Smooth slow motion"** om alternativet finns (ger mjukare resultat).

**I DaVinci Resolve:**

1. Hogerkicka pa klippet i tidslinjen.
2. Valj **"Clip Attributes"**.
3. Andra **"Video Frame Rate"** till din tidslinjes fps (25).
4. Nu spelas klippet automatiskt i slowmotion.

### Speed ramping (normal hastighet till slow till normal)

Det har ar en av de mest effektfulla teknikerna for kampsportsvideo. Tankscenariot:

En spark borjar i normal hastighet, gar i ultraslowmotion vid traffpunkten och atergar till normal hastighet.

**I CapCut:**

1. Markera klippet pa tidslinjen.
2. Klicka **"Speed"** > **"Curve"**.
3. Valj en fordinstaild kurva (t.ex. **"Montage"** eller **"Hero"**) ELLER skapa en egen.
4. For att skapa en egen kurva:
   - Du ser en linje med punkter.
   - Dra en punkt **nerat** = langsammare vid den tidpunkten.
   - Dra en punkt **uppat** = snabbare.
   - Lagg till fler punkter genom att klicka pa linjen.
5. En typisk speed ramp for en spark:
   ```
   Normal (1x) ──> Snabbt (1.5x) ──> Langsamot (0.2x) ──> Normal (1x)
                    anloppet          traffpunkt           efter
   ```

**I DaVinci Resolve:**

1. Hogerkicka pa klippet > **"Retime Controls"**.
2. En hastighetsrad dyker upp ovanfor klippet.
3. Klicka pa nedatpilen vid den punkt dar du vill andra hastighet.
4. Valj **"Add Speed Point"**.
5. Dra hastighetsvarden mellan punkterna.
6. For mjuk overgeng, hogerkicka pa en speed point > **"Retime Curve"**.

### Timing och kansla

- **Anvand slowmotion sparksamt.** 2-4 slowmotion-moment i en 60-sekundervideo ar lagom. For mycket kanns slott.
- **Slowmotion funkar bast pa:** hogre sparkar, kast, moment dar hela kroppen ar i luften, precisa tekniker.
- **Slowmotion funkar INTE pa:** stretching, statiska poser, gruppbilder, promenerande.
- **Kombinera med musiken:** Lat slowmotion-stallet sammanfalla med ett lugnare parti i musiken.

---

## 5. Musik och ljud

### Var du hittar royalty-free musik

| Tjanst | Pris | Kvalitet | Licensmodell |
|---|---|---|---|
| **YouTube Audio Library** | Gratis | Bra | Fri anvandning, aven kommersiellt |
| **Pixabay Music** | Gratis | Varierar | Fri anvandning, aven kommersiellt |
| **Epidemic Sound** | Ca 130 kr/man | Mycket hog | Licens krays -- tacker YouTube, sociala medier |
| **Artlist** | Ca 170 kr/man | Mycket hog | Universal licens |
| **Free Music Archive** | Gratis | Varierar | Kontrollera licens per lat |

**For koreansk kansla, sok pa:**

- "Korean cinematic" eller "Korean traditional modern" pa Epidemic Sound eller Artlist
- "Asian cinematic" eller "martial arts" pa YouTube Audio Library
- "Korean percussion" eller "gayageum modern" pa Pixabay

> **Viktigt om upphovsratt:** Anvand ALDRIG musik fran Spotify, Apple Music eller YouTube-videor. Aven om du laser "no copyright" i en YouTube-titel -- kontrollera alltid licensen. Anvand bara musik fran tjanster som uttryckligen ger dig ratt att anvanda musiken i video.

### Musikstil for detta projekt

Du soker efter musik som:

- **Kanns modern men med djup** -- inte generisk "upbeat corporate"
- **Har varierat tempo** -- borjar lugnt, bygger upp, nar en topp, och landar mjukt
- **Ar upplyftande men inte overdriven** -- tanke "inspiration" snarare an "fest"
- **Langd:** 60 sekunder (eller en lat du kan klippa till 60 sekunder)

Bra soekord: "cinematic motivational", "martial arts inspiration", "Asian cinematic build", "dramatic uplifting"

### Hur du synkar klipp med musikens beats

1. **Lyssna pa laten 2-3 ganger** innan du borjar klippa. Anteckna var de stora beat-byterna ar.
2. **Markera nyckelpunkter:**
   - Var kickar trummorna in?
   - Var ar refrangens borjan?
   - Var ar det lugnaste partiet?
   - Var finns det "dropp" eller pauser?
3. **Matcha videostrukturen med musikstrukturen:**
   - Musikens intro = videons lugna oppning
   - Musikens uppbyggnad = videoklipp som okar i tempo
   - Musikens climax = snabbaste klippsekvensen
   - Musikens nedgang = gemenskaps-sekvensen
   - Musikens slut = logotyp och info

### Ljudnivaer och fade in/out

**Nivaer:**
- Musik: **-12 dB till -6 dB** (beror pa laten -- anvand oronen)
- Bakgrundsljud fran klipp: **stangd** i de flesta fall (dra ner till -inf dB)
- Om du anvander enskilda ljudeffekter: **-6 dB till -3 dB**

**Fade in/out:**
- **Fade in** pa musikens borjan: 1-2 sekunder
- **Fade out** pa musikens slut: 2-3 sekunder
- Sa har i CapCut: markera musikklippet, dra den lilla vita triangeln i borjan/slutet av klippet

### Eventuella ljudeffekter

Lagga till diskreta ljud KAN hoja upplevelsen. Anvand sparksamt (0-3 effekter i hela videon).

| Effekt | Kalla | Nar |
|---|---|---|
| Kiai (kamprop) | Klippets eget ljud, om det ar bra kvalitet | Under en kraftfull teknik |
| Dobok-small (klattyg) | Fran klippet, eller sok "whoosh" i CapCuts ljudbibliotek | Under snabb spark eller slag |
| Mattsteg/fall | Fran klippet | Under kast/nedlaggning |
| Whoosh | CapCuts inbyggda ljud | Snabb overgang eller speed ramp |

> **Tumregel:** Om ljudeffekten kanns forcerad -- ta bort den. Musiken ska bara jobbet.

---

## 6. Textoverlagg och grafik

### Typsnitt

**Forstahands-val:** Inter (gratistypsnitt)
- Ladda ner fran [fonts.google.com/specimen/Inter](https://fonts.google.com/specimen/Inter)
- Installera pa datorn (dubbelklicka pa .ttf-filen > "Installera")
- Typsnnittet dyker upp i CapCut/DaVinci Resolve efter omstart

**Alternativ om Inter inte finns tillgangligt:**
- **Montserrat** (gratis, Google Fonts) -- liknande kansla
- **Poppins** (gratis, Google Fonts) -- lite rundare
- **Helvetica Neue** (foljer med Mac) -- klassiker
- **Arial** (foljer med alla datorer) -- noodloosning

**For koreansk text:** Ladda ner **Noto Sans KR** fran [fonts.google.com/noto/specimen/Noto+Sans+KR](https://fonts.google.com/noto/specimen/Noto+Sans+KR)

### Farger

Anvand foljande farger genomgaende:

| Element | Farg | Hexkod | Anvandning |
|---|---|---|---|
| Huvudtext | Vit | #FFFFFF | All loptext |
| Accentfarg | Orange | #FF6B35 | Nyckelord, understrykning, accentelement |
| Bakgrundsfarg (text) | Svart, halvtransparent | #000000, 60-70 % opacitet | Bakom text om bakgrunden ar rorig |
| Sekundartext | Ljusgra | #CCCCCC | Underrubriker, smarre info |

### Textanimationer

**Anvand:**

- **Fade in** (text tonar in): For de flesta texter. 0.3-0.5 sekund.
- **Slide in fran vanster/hoger**: For kortare texter/slogans. 0.3 sekund.
- **Tracking/karning** (bokstaverna sprids ut och samlas): For titlar. 0.5 sekund.

**Sa har i CapCut:**
1. Klicka pa **"Text"** > **"Default text"** och dra till tidslinjen.
2. Skriv din text.
3. I panelen till hoger: andra typsnitt, storlek, farg.
4. Klicka pa **"Animation"** fliken.
5. Valj **"In"** (hur texten kommer in), **"Out"** (hur den forsvinner), **"Loop"** (upprepande).
6. Valj t.ex. "Fade In" under "In".

**UNDVIK:**

- Snurrande text
- Studsande text
- Typewriter-effekt (om inte det ar ETT ord)
- Neonskugga eller glod-effekter
- Allt som tar uppmrksamhet fran videoinnehallet

### Placering av text

**16:9-versionen:**
```
┌────────────────────────────────────────┐
│                                        │
│  ┌──────────────────────────┐          │
│  │     HAPKIDO SVERIGE      │  (ovre tredjedelen)
│  │     Sjalvforsvar for alla│          │
│  └──────────────────────────┘          │
│                                        │
│                                        │
│                                        │
│                                        │
│         hapkidosweden.se     (nedre)   │
└────────────────────────────────────────┘
```

**9:16-versionen (VIKTIGT -- undvik kanter):**
```
┌──────────────────┐
│                  │
│                  │
│  ╔════════════╗  │
│  ║  HAPKIDO   ║  │  (mitten -- "safe zone")
│  ║  SVERIGE   ║  │
│  ╚════════════╝  │
│                  │
│                  │
│  ┌────────────┐  │
│  │  hemsida   │  │
│  └────────────┘  │
│ ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓│  <-- HER syns TikTok/Instagram-knappar
└──────────────────┘       Undvik att lagga text har!
```

**Safe zone for 9:16:** Hall all viktig text och grafik minst 250 pixlar fran botten och 150 pixlar fran ovekanten. TikTok och Instagram lagger interface-element dar.

### Koreansk text: 합기도

**Hur du lagger in det:**

1. Kopiera texten harifran: **합기도**
2. Skapa ett nytt textlager i CapCut.
3. Klistra in: 합기도
4. Valj typsnitt: **Noto Sans KR** (Regular eller Bold).
5. Farg: #FFFFFF (vit) eller #FF6B35 (orange) beroende pa kontext.
6. Storlek: Stor -- anvand som grafiskt element, inte som lrast text.

**Anvandning:**
- Som en subtil bakgrundstext (stor, halvtransparent, bakom video)
- Bredvid "HAPKIDO" pa engelska/svenska
- I intro- eller outro-sekvensen

**Ytterligare koreanska termer du kan anvanda:**

| Koreanska | Betydelse | Anvandning |
|---|---|---|
| 합기도 | Hapkido | Huvudtitel, grafiskt element |
| 한민족 | Hanminjok | Vid WKF-referens |
| 기합 | Kihap (kamprop) | Vid action-sekvens |

### WKF/Hanminjok-logotyp

1. Se till att logotypen ar i **PNG-format med transparent bakgrund**.
2. Importera den till CapCut.
3. Dra den till tidslinjen (pa ett videospar OVANFOR huvudvideon).
4. Placera den i ett horn -- normalt **ovre hogra hornet** eller **nedre hogra hornet**.
5. Storlek: ca 10-15 % av skarmbredden. Den ska synas men inte dominera.
6. Lagg till en subtil fade in pa 0.5 sekunder.

---

## 7. Fargkorrigering och grading

### Varfor det behovs

Material fran olika klubbar, filmade med olika kameror och i olika ljusforhallanden, kommer att se olika ut. Fargkorrigering gor att allt kanns som en enhetlig video.

### Steg 1: Grundlaggande exponering

For varje klipp, justera:

1. **Exponering/Brightness:** Ar klippet for morkt eller for ljust? Justera sa att ansikten ar tydliga.
2. **Kontrast:** Oka lite (10-20 %). Det gor bilden mer "popp-ig".
3. **Highlights:** Sank lite om ljusa omraden ar utbranda (t.ex. fonster i bakgrunden).
4. **Shadows:** Hoj lite om morka partier ar for morka.

**I CapCut:**
1. Markera klippet.
2. Klicka pa **"Adjust"** i verktygsfraltet.
3. Anvand reglagen for Brightness, Contrast, Highlights, Shadows.

### Steg 2: Vitbalans

Vitbalans handlar om att "vitt ska se vitt ut".

- Om bilden ar for **gul/varm**: dra Temperature at vanster (kallare).
- Om bilden ar for **bla/kall**: dra Temperature at hoger (varmare).
- Om bilden ar for **gron**: dra Tint at hoger (mer magenta).
- Om bilden ar for **magenta/lila**: dra Tint at vanster (mer gron).

> **Tips:** Titta pa en vit drakts farg. Om den ser gul ut -- korrigera at bla. Om den ser bla ut -- korrigera at gult.

### Steg 3: Skapa "looken" -- mork, varm stil

For att matcha hemsidans morkta, varma stil med orangea accenter:

1. **Sank Highlights** med 10-20 % (morkar ner ljusa partier = morkare kansla).
2. **Sank Blacks/Shadows** en aning (djupare morker).
3. **Oka Warmth/Temperature** mycket subtilt (5-10 % at varmt hall).
4. **Oka Saturation** pa orange/roda toner med 10-15 % om mojligt.
5. **Sank Saturation** pa ovriga farger med 5-10 % (om programmet tillater selektiv farg).

**I CapCut (snabbmetod):**
1. Klicka pa **"Filters"** i verktygsfraltet.
2. Under kategorin **"Film"** eller **"Cinematic"** -- prova filter som ger en varm, mork kansla.
3. Sank filterstyrkan till 30-50 % (100 % ar nastan alltid for mycket).
4. Finjustera med **"Adjust"**-reglagen.

**I DaVinci Resolve (mer kontroll):**
1. Ga till **Color-sidan** (nedre menyn).
2. Anvand **Lift** (skuggor), **Gamma** (mellantoner), **Gain** (hogdagrar) hjulen.
3. Dra Lift nagot nedat och at varmt (orange).
4. Dra Gain nagot nedat (morkar hogdagrar).
5. I **Curves** -- skapa en mild S-kurva for okad kontrast.

### Steg 4: Konsistens mellan klipp

**Den viktigaste regeln:** Alla klipp ska kanna som om de hor ihop.

1. Fargkorrigera ett klipp som ser bra ut och anvand det som referens.
2. **I CapCut:** Hogerkicka pa det korrrigerade klippet > **"Copy effects"**. Hogerkicka pa nasta klipp > **"Paste effects"**. Justera om det behovs.
3. **I DaVinci Resolve:** Hogerkicka > **"Grab Still"**. Pa nasta klipp, hogerkicka pa din Still > **"Apply Grade"**.
4. Spela igenom videon och se till att inga klipp "sticker ut" i farg eller ljusstyrka.

> **Vanliga problem:**
> - Klipp fran gymnastiksal med lysror = gront/gult sken. Korrigera med Tint at magenta.
> - Klipp fran lokal med fonster = mixat ljus (dagsljus + inomhusljus). Kan vara svart att fixa helt -- forsok fa vitbalansen nara.
> - Klipp fran morka lokaler = brusiog bild. Undvik att hoja exponering for mycket -- det forstarker brus.

---

## 8. Exportinstallningar per plattform

### Oversiktstabell

| Plattform | Format | Upplosning | FPS | Codec | Bitrate | Filformat | Max storlek |
|---|---|---|---|---|---|---|---|
| **YouTube** | 16:9 | 1920x1080 (eller 3840x2160) | 25/30 | H.264 | 10-16 Mbps (1080p) / 35-45 Mbps (4K) | .mp4 | 256 GB |
| **Facebook** | 16:9 | 1920x1080 | 25/30 | H.264 | 8-12 Mbps | .mp4 | 4 GB |
| **Hemsida** | 16:9 | 1920x1080 | 25/30 | H.264 | 5-8 Mbps | .mp4 | Sa liten som mojligt (under 15 MB idealt) |
| **TikTok** | 9:16 | 1080x1920 | 25/30 | H.264 | 6-10 Mbps | .mp4 | 287 MB |
| **Instagram Reels** | 9:16 | 1080x1920 | 25/30 | H.264 | 6-10 Mbps | .mp4 | 4 GB |

### Detaljerade exportinstallningar

#### YouTube (16:9, 60s)

**I CapCut:**
1. Klicka pa **"Export"** uppe till hoger.
2. Upplosning: **1080p** (eller 4K om materialet ar 4K).
3. Kvalitet: **High quality**.
4. FPS: **25** eller **30** (matcha ditt projekt).
5. Format: **mp4**.
6. Codec: H.264 (standard).

**I DaVinci Resolve:**
1. Ga till **Deliver-sidan**.
2. Valj preset **"YouTube"**.
3. Eller manuellt:
   - Format: MP4
   - Codec: H.264
   - Upplosning: 1920x1080 (eller 3840x2160)
   - Quality: Restrict to 16 000 Kbps (1080p) eller 45 000 Kbps (4K)
   - Audio: AAC, 48 kHz, 320 Kbps

#### Facebook (16:9, 60s)

- Samma som YouTube men bitrate: **8 000-12 000 Kbps**
- Filstorlek: hall under **4 GB** (inte ett problem for 60s)
- Facebook komprimerar kraftigt oavsett -- ladda upp sa hog kvalitet som mojligt

#### Hemsida hapkidosweden.se (16:9, 60s)

Har ar filstorlek viktigare an maximal kvalitet.

1. Exportera i 1080p med **lagre bitrate: 5 000-8 000 Kbps**.
2. Alternativt: exportera i full kvalitet och komprimera i efterhand med [HandBrake](https://handbrake.fr/) (gratis):
   - Oppna HandBrake, dra in din exporterade fil.
   - Preset: **"Fast 1080p30"** eller anpassat.
   - Malstorilk: under 15 MB ar idealt for snabb laddning pa hemsidan.
   - Det innebar ganska kraftig komprimering -- titta igenom resultatet och hitta en balans.

> **Bonustips for hemsidan:** Overag att anvanda en videovardtjanst som YouTube eller Vimeo och badda in videon pa hemsidan. Da slipper du oroa dig for filstorlek och bandbredd.

#### TikTok (9:16, 20-30s)

1. Exportera fran ditt 9:16-projekt.
2. Upplosning: **1080x1920**.
3. FPS: **30** (TikTok foredrar 30).
4. Bitrate: **6 000-10 000 Kbps**.
5. Format: **.mp4**.
6. Max langd for optimal rackvidd: **21-34 sekunder** ar sweet spot.

#### Instagram Reels (9:16, 20-30s)

- Identiska installningar som TikTok.
- Max langd: 90 sekunder (men 20-30 sekunder ar optimalt for rackvidd).
- Instagram komprimerar ocksa kraftigt -- ladda upp hog kvalitet.

### Namnge dina exporterade filer

```
hapkido-promo-youtube-1080p-YYYY-MM-DD.mp4
hapkido-promo-facebook-1080p-YYYY-MM-DD.mp4
hapkido-promo-hemsida-komprimerad-YYYY-MM-DD.mp4
hapkido-promo-tiktok-9x16-YYYY-MM-DD.mp4
hapkido-promo-reels-9x16-YYYY-MM-DD.mp4
```

---

## 9. Publiceringstips

### Titlar och beskrivningar per plattform

#### YouTube

**Titel (max 70 tecken):**
```
Hapkido Sverige -- Koreanskt sjalvforsvar for alla | WKF Hanminjok
```

**Beskrivning:**
```
합기도 -- Hapkido ar en koreansk kampsport som fokuserar pa sjalvforsvar,
kast, las och sparkar.

WKF/Hanminjok Hapkido finns pa flera platser i Sverige. Valkomna att
prova pa -- oavsett alder och erfarenhet.

Mer info: https://hapkidosweden.se

#hapkido #sjalvforsvar #kampsport #hapkidosverige #wkf #hanminjok
#koreanskkampsport #traning #합기도
```

#### Facebook

**Text (kort, inga hashtags i huvudtexten):**
```
Hapkido -- koreanskt sjalvforsvar for alla. Sparkar, kast, las och
sjalvforsvar i en komplett kampsport. Valkomna att prova pa!

Mer info: hapkidosweden.se
```

#### TikTok

**Beskrivning (kort och med hashtags):**
```
Hapkido -- koreanskt sjalvforsvar 🥋 Sparkar, kast och sjalvforsvar
for alla. Prova pa! hapkidosweden.se
```

**Hashtags for TikTok (lagg i beskrivningen):**
```
#hapkido #합기도 #martialarts #sjalvforsvar #kampsport #hapkidosverige
#selfdefense #kicksintikkok #kampsporttiktok #traning #fyp #foryou
#koreanskkampsport #wkf #koreanmartialarts
```

#### Instagram Reels

**Beskrivning:**
```
합기도 Hapkido -- koreanskt sjalvforsvar for alla.

Sparkar, kast, las och sjalvforsvar i en komplett kampsport. Oavsett
alder och erfarenhet -- du ar valkomlen!

Mer info: hapkidosweden.se (lank i bio)
```

**Hashtags (lagg som forsta kommentar, inte i beskrivningen):**
```
#hapkido #합기도 #martialarts #sjalvforsvar #kampsport #hapkidosverige
#selfdefense #koreanskkampsport #wkf #hanminjok #traning #kampkonst
#sweden #kampsportvideo #hapkidotraining
```

### Basta tider att publicera

| Plattform | Basta dagar | Basta tider | Notering |
|---|---|---|---|
| **YouTube** | Torsdag-Lordag | 14:00-16:00 eller 18:00-20:00 | Publicera 2 timmar fore "peak" for indexering |
| **Facebook** | Tisdag-Torsdag | 09:00-11:00 eller 18:00-20:00 | Undvik helger for organisationer |
| **TikTok** | Tisdag, Torsdag, Fredag | 18:00-21:00 | Eftermiddag/kvall for svensk publik |
| **Instagram Reels** | Onsdag, Fredag | 11:00-13:00 eller 19:00-21:00 | Lunchtid eller kvallstid |

> **Obs:** Dessa tider baseras pa generella riktlinjer for svensk publik. Nar kontona vaxer kan du se faktisk statistik i respektive plattforms analysverktyg.

### Thumbnail-tips for YouTube

YouTube-miniatyrbilden (thumbnail) ar avgorrande for om nagon klickar pa videon.

**Gor sa har:**

1. **Ta en stillbild** fran videon som visar action (spark, kast) eller exportera en bild fran ditt redigeringsprogram.
2. **Oppna en gratis bildeditor** som [Canva](https://www.canva.com/) (eller Photoshop/GIMP om du har det).
3. **Storlek:** 1280x720 pixlar (16:9).
4. **Lagg till:**
   - En stark bild (person i action, garna med tydlig rorelse)
   - Kort text: max 3-4 ord, stort typsnitt (t.ex. "HAPKIDO SVERIGE")
   - Typsnitt: Inter Bold eller liknande, vit text med tunn svart kantlinje
   - Orange accent (#FF6B35) pa ett nyckelord eller som understrykning
   - WKF-logotyp i ett horn (liten)
5. **Undvik:**
   - For mycket text (ska vara lasbart pa en mobilskarm)
   - Sma detaljer
   - Morka bilder utan kontrast

**Tumregel for bra thumbnail:** Kan du forsta vad bilden visar nar den ar 3 cm bred pa en mobilskarm? Om ja -- bra. Om nej -- forenka.

---

## Snabbreferens: checklista innan publicering

- [ ] Videon borjar starkt -- forsta 3 sekunderna fanger uppmarksamhet
- [ ] All text ar lasbar, aven pa mobil
- [ ] Inga stavfel i text pa skarmen
- [ ] Musiken har ratt licens for alla plattformar
- [ ] Logotypen syns tydligt
- [ ] hemsidoadressen (hapkidosweden.se) visas i slutet
- [ ] 합기도 anvands som grafiskt element minst en gang
- [ ] Fargerna ar konsekventa genom hela videon
- [ ] Inget viktigt innehall hamnar bakom TikTok/Instagram-knappar (9:16-versionen)
- [ ] Exporterad i ratt format for respektive plattform
- [ ] Spelat igenom hela videon pa en TELEFON (inte bara pa datorskarm)
- [ ] Spelat igenom hela videon med ljud
- [ ] Filerna ar namngivna korrekt

---

*Guide skapad for WKF/Hanminjok Hapkido Sverige -- hapkidosweden.se*
