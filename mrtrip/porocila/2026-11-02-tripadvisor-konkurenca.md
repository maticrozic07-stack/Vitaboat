# MRTrip – raziskovalno poročilo (2026-11-02)
Tema: Tripadvisor kot glavni konkurent in podobne aplikacije (popularno, konkurenca, kaj izboljšati, inovacije)

> **Opomba o kontekstu:** `mrtrip/PROJEKT.md` je večinoma neizpolnjen. Znano je le, da je glavni konkurent Tripadvisor, podobne aplikacije pa so Google Maps/Travel, Yelp, Booking.com, Airbnb Experiences, GetYourGuide, Viator, Wanderlog in Polarsteps. Zato predpostavljam, da je **MRTrip aplikacija za odkrivanje, načrtovanje in organizacijo potovanj**, verjetno s poudarkom na Sloveniji in regiji. Ko bo PROJEKT.md izpolnjen (ciljni uporabniki, tehnologija, poslovni model), bodo priporočila lahko bolj ciljana.
>
> To je **prvo poročilo**, zato prejšnjih ugotovitev ni.

---

## Povzetek v 5 točkah
1. **Tripadvisor se umika iz hotelov in stavi na doživetja ter AI-distribucijo.** V Q2 2026 so prihodki iz hotelov padli za 21 %, Viator je zrasel za 10 %. TheFork prodajajo American Expressu za 700 mio USD, vsebino pa distribuirajo prek ChatGPT, Claude, Alexa+ in Perplexity. Njihov lasten "AI-native" izdelek je še MVP.
2. **AI uporabljajo za navdih, za rezervacijo pa ne.** 71 % popotnikov se strinja, da jim AI predlaga ideje, z AI pa je kaj rezerviralo le okoli 16 %. Pri drugem viru AI-ju dovoli rezervacijo samo 2 %. 51 % dvomi v točnost AI-priporočil. **Zaupanje je glavna valuta.**
3. **Google postaja neposreden konkurent celotnemu toku od navdiha do rezervacije.** Ponuja AI Mode (Canvas za itinerarje, sledenje cenam letov, rezervacija hotelov z Google Pay v ZDA od avgusta 2026) in "Ask Maps" z Gemini v Google Maps.
4. **Bolečine uporabnikov Tripadvisorja se ponavljajo.** Gre za lažne ocene in nepregledno brisanje pristnih ocen, nedosegljivo podporo (samo boti), težave pri rezervacijah in vračilih Viator ter plačane umestitve. Trustpilot: 1,8/5 (tripadvisor.com, 3.936 ocen).
5. **Priložnost za MRTrip so zaupanja vredne lokalne izkušnje in pretvorba "videl na TikToku" v izvedljiv načrt.** 48 % Gen Z se navdihuje na TikToku. Tripadvisor tako funkcijo (video v itinerarij) šele testira. Slovenija je imela leta 2025 rekordnih skoraj 7 mio prihodov turistov.

---

## 🔥 Kaj je popularno

**Dejstva:**
- **AI za načrtovanje je postal običajen, za rezervacije pa ne.**
  - Raziskava Skift Research in McKinsey (sept. 2026, več kot 1.000 popotnikov iz ZDA): 71 % se strinja, da AI predlaga ideje, 67 % pa, da zoži izbiro. Le približno 16 % je z AI kaj rezerviralo. Formulacijo tega podatka viri navajajo različno ([Skift](https://skift.com/insights/new-report-winning-hearts-in-an-age-of-infinite-travel-choices/), [Asianet/povzetek](https://newsable.asianetnews.com/business/report-travellers-embrace-ai-for-planning-draw-line-at-booking-articleshow-f724tdg)).
  - Poročilo Skift o agentskem AI: več kot 90 % zaupa informacijam AI, rezervacijo pa AI-ju prepusti le 2 % ([Skift, mar. 2026](https://skift.com/2026/03/03/travel-brands-are-building-ai-agents-for-a-consumer-that-doesnt-exist/), [Skift report](https://skift.com/insights/new-report-remapping-travel-with-agentic-ai/)).
- **Zaupanje je ozko grlo.** Na Skift Data + AI Summit Europe (13. 10. 2026) sta šefa Kayaka in Skyscannerja poudarila, da udobje ni dovolj. Ključni so zaupanje, izbira in preverjanje cen. 51 % vprašanih ima pomisleke glede točnosti AI-priporočil (raziskava Skyscanner). AI-napotitve pri Booking in Marriott še vedno predstavljajo manj kot 2 % prometa ([Skift, 13. 10. 2026](https://skift.com/2026/10/13/skift-data-ai-summit-europe-2026-ai-is-ubiquitous-yet-still-unconquered/)).
- **AI vidnost poganja število ocen na Googlu.** Študija na več kot 650 hotelih v Barceloni je pokazala, da je število Google ocen najmočnejši dejavnik vidnosti v AI-odgovorih, llms.txt pa ni imel merljivega učinka. Neodvisni hoteli so AI-sistemom 8-krat pogosteje neznani kot verige, ko pa jih AI pozna, jih priporoča enako pogosto ([Skift, 13. 10. 2026](https://skift.com/2026/10/13/skift-data-ai-summit-europe-2026-ai-is-ubiquitous-yet-still-unconquered/)).
- **Družbena omrežja so glavni vir navdiha.** Raziskava TUI Musement (ES, IT, UK; avg. 2026):
  - 48 % Gen Z navaja TikTok kot vir navdiha (prijatelji in družina 43 %).
  - 43 % vseh je rezerviralo potovanje ali aktivnost zaradi viralne objave (milenijci 52 %, Gen Z 50 %).
  - 27 % je zaradi influencerja zamenjalo destinacijo.
  
  ([Euronews, 21. 8. 2026](https://www.euronews.com/travel/2026/08/21/i-saw-it-on-tiktok-48-of-gen-z-travellers-turn-to-the-platform-for-travel-inspiration))
- **Regionalno (Slovenija) – leto 2025 je bilo rekordno.**
  - Skoraj 7 mio prihodov (+6,2 %) in 17,8 mio prenočitev.
  - Tuji gostje so ustvarili skoraj 13,4 mio prenočitev (+okoli 8 %, približno tri četrtine vseh).
  - Največ prenočitev so ustvarili Nemci (več kot 2 mio), sledijo Italijani in Avstrijci (vsak več kot 1 mio), nato Hrvati, Čehi in Nizozemci.
  
  ([RTV SLO/STA, 23. 1. 2026](https://www.rtvslo.si/zabava-in-slog/ture-avanture/slovenijo-lani-obiskalo-rekordno-stevilo-turistov/771021))
- **STO poudarja kakovost, trajnost in odpornost namesto rasti za vsako ceno** ([slovenia.info](https://www.slovenia.info/sl/novinarsko-sredisce/sporocila-za-javnost/36160-slovenski-turizem-v-2025-ob-zmerni-rasti-v-ospredju-kakovost-trajnost-in-dolgorocna-odpornost), [gov.si, 7. 1. 2026](https://www.gov.si/novice/2026-01-07-slovenski-turizem-v-2025-ob-zmerni-rasti-v-ospredju-kakovost-trajnost-in-dolgorocna-odpornost/)).

---

## 🥊 Konkurenca – kaj je novega

### Tripadvisor (glavni konkurent)
**Poslovna slika:**
- **Q2 2026:** prihodki iz nadaljevanih dejavnosti so znašali 441,9 mio USD (−7 %), prilagojeni EBITDA pa 76,4 mio USD (−21 %).
- **Hotels & Other:** prihodki 163 mio USD (−21 %). Napoved za Q3: −20 do −23 %.
- **Experiences:** rezervacije +5 %, Viator +10 %, bruto vrednost rezervacij (GBV) 1,4 mrd USD.

([Quartr, Q2 2026](https://quartr.com/events/tripadvisor-inc-trip-q2-2026_3Y1ZAk89))

**Prodaja TheFork:** 15. 6. 2026 so objavili dogovor o prodaji TheFork American Expressu za 700 mio USD v gotovini. Zaključek je predviden do konca leta 2026, pritisk za prodajo pa je prihajal od aktivističnega vlagatelja Starboard ([Tripadvisor, 15. 6. 2026](https://tripadvisor.mediaroom.com/2026-06-15-Tripadvisor-Enters-into-Agreement-to-Sell-TheFork-to-American-Express-for-700-Million), [AltexSoft](https://www.altexsoft.com/travel-industry-news/tripadvisor-sells-thefork-as-experiences-take-priority/)). Ali je posel že zaključen, nisem mogel preveriti.

**Napovedani rezultati:** Rezultati za Q3 2026 bodo objavljeni **5. 11. 2026**. Priporočam dopolnitev poročila po objavi ([Placera/PR](https://www.placera.se/pressmeddelanden/tripadvisor-tripadvisor-to-host-third-quarter-2026-financial-results-conference-call-on-november-5-2026-20261020)).

**AI-strategija: distribucija vsebine v tuje AI-platforme**
- **ChatGPT:** aplikacija Tripadvisor je bila med prvimi vgrajenimi aplikacijami (nov. 2025). Ponuja iskanje hotelov z interaktivnim zemljevidom in primerjavo ponudb, za rezervacijo pa uporabnika preusmeri na Tripadvisor ali partnerja. Po navedbah Tripadvisorja je na voljo samo v ZDA ([tripadvisor.com/ChatGPT](https://www.tripadvisor.com/ChatGPT), [Tom's Guide](https://www.tomsguide.com/ai/tripadvisor-and-peloton-are-chatgpts-first-built-in-apps-apple-and-google-should-be-worried)).
- **Viator v ChatGPT:** aplikacija je v živo (klic Q4 2025, 12. 2. 2026) ([AOL transkript](https://www.aol.com/finance/tripadvisor-trip-q4-2025-earnings-171701174.html)).
- **Claude in Alexa+ (apr. 2026):**
  - V Claudu uporabnik primerja fotografije, ocene, povzetke ocen in cene, nato pa za rezervacijo klikne na Tripadvisor oziroma Viator.
  - Alexa+ iz vsebine Tripadvisorja ustvarja personalizirane itinerarje.
  - Kot partnerja sta omenjena tudi OpenAI in Perplexity.
  
  ([Tripadvisor, 23. 4. 2026](https://tripadvisor.mediaroom.com/2026-04-23-How-AI-Is-Changing-the-Way-We-Plan-Travel))
- **"AI-native MVP" (Q4 2025):** po besedah CEO Matta Goldberga dosega večkrat višjo vključenost kot prejšnji AI-asistent, vpliv na finance pa je še prezgodaj oceniti. Ime in funkcije izdelka javno niso podrobno opisani ([AOL transkript](https://www.aol.com/finance/tripadvisor-trip-q4-2025-earnings-171701174.html), [MarketBeat](https://www.marketbeat.com/instant-alerts/tripadvisor-q4-earnings-call-highlights-2026-02-12/?.tsrc=rss)).
- **Video v itinerarij (prototip, GTC 2026, mar. 2026):** iz influencerjevega videa prepozna kraje in aktivnosti, jih poveže s podatki Tripadvisorja in sestavi itinerarij, pripravljen za rezervacijo. Funkcija je eksperimentalna, glavna izziva pa sta točnost prepoznave in personalizacija ([AltexSoft, 26. 3. 2026](https://www.altexsoft.com/travel-industry-news/tripadvisor-debuts-ai-planner-for-video-based-trips/)).
- **B2B: Best Western "Go for the Goal" (29. 1. 2026):** AI-načrtovalec potovanj za navijače na SP 2026 ([PR Newswire](https://www.prnewswire.com/news-releases/best-western-hotels--resorts-and-tripadvisor-launch-ai-powered-trip-planning-experience-to-help-soccer-fans-navigate-2026-travel-302673239.html)).

**Zaupanje in ocene (zadnji uradni podatki so iz poročila za 2025, ki zajema leto 2024):**
- Od 31,1 mio oddanih ocen je bilo okoli 8 % lažnih.
- Odstranili so več kot 200.000 ocen, napisanih z AI.

([NBC/CNBC](https://www.nbcnewyork.com/news/business/money-report/heres-how-many-fake-reviews-tripadvisor-found-on-its-website-in-2024/6277840/), [Tripadvisor 2025 Transparency Report](https://tripadvisor.mediaroom.com/2025-03-18-Tripadvisors-2025-Transparency-Report-reveals-strong-review-submissions-and-improved-fraud-detection?asPDF=1)). Uradnega poročila za 2026 nisem našel.

**API za razvijalce:** Uradna pogostih vprašanj (FAQ) za Content API navaja 5.000 brezplačnih klicev na mesec, za preseganje pa je potrebna kartica ([readme FAQ](https://tripadvisor-content-api.readme.io/reference/faq)). En vir iz leta 2026 trdi, da je bil star API ukinjen 31. 8. 2026 in nadomeščen s "Terra API" (1.000 brezplačnih klicev). **To ni potrjeno** ([SocialCrawl](https://www.socialcrawl.dev/blog/best-tripadvisor-data-apis-2026)).

### Google (Search AI Mode, Maps)
- **AI Mode (27. 8. 2026):**
  - Iskanje letov z cenami več kot 300 letalskih družb in sledenje cenam (v več kot 180 državah).
  - Rezervacija hotelov s "Continue on Google" in Google Pay (ZDA, angleščina). Partnerji so Booking.com, Expedia, Hilton, Marriott, IHG, Trip.com in drugi.
  - Cene v točkah in miljah.
  
  ([TechCrunch](https://techcrunch.com/2026/08/27/googles-ai-mode-can-now-track-flight-prices-help-book-hotels-and-more/))
- **Canvas** v AI Mode sestavlja načrte potovanj iz podatkov Flights, Hotels in Maps. **Ask Maps** (Gemini) je v Google Maps od marca 2026 ([eMarketer](https://www.emarketer.com/content/google-expands-ai-travel-planning-and-booking-tools), [Search Engine Journal](https://www.searchenginejournal.com/google-extends-ai-travel-planning-and-agentic-booking-in-search/)). Datume sem preveril le delno.

### Booking.com
- **Oktober 2025:** AI Trip Support (24/7, s predajo človeku), AI Voice Support, AI Rental Helper in povzetki iskanja letov. Za partnerje sta na voljo Smart Messenger in Auto-Reply ([Hospitality Net, 9. 10. 2025](https://www.hospitalitynet.org/news/4129287/bookingcom-debuts-agentic-ai-innovations-adding-to-its-robust-suite-of-genai-tools-for-customers)).
- Po sekundarnem viru aplikacija Booking v ChatGPT od maja 2026 ponuja tudi najem avtomobilov (nepreverjeno; [monkeytravel](https://monkeytravel.app/blog/best-ai-travel-agents-2026)).

### Airbnb
- **Summer Release (maj 2026):** dostava živil (Instacart), prevozi z letališča, shramba prtljage, prenovljene storitve in doživetja (Services/Experiences), butični hoteli, najem avtomobilov, skupni itinerarji in AI-povzetki ocen ([EFTM](https://eftm.com/2026/05/airbnb-expands-beyond-stays-with-ai-powered-customer-support-grocery-deliveries-pickups-and-more-experiences-276021), [AltexSoft](https://www.altexsoft.com/travel-industry-news/airbnb-adds-cars-hotels-ai-to-keep-trips-in-app/)).
- **Jesenska posodobitev (30. 9. 2026):** iskanje v naravnem jeziku in z glasom čez domove, doživetja in storitve ter družabne funkcije. Datum in podrobnosti izhajajo iz sekundarnega povzetka, primarnega vira (eMarketer) nisem mogel odpreti (403) ([eMarketer](https://www.emarketer.com/content/airbnb-transforms-super-app-services-experiences-with-ai)).

### GetYourGuide
- **Spring 2026 Release (22. 4. 2026):** AI-povzetki ocen preverjenih gostov, bolj personalizirano iskanje in AI-predlogi odgovorov za ponudnike. Cilj je zapolniti vrzel med "AI-načrtovanjem" in rezervacijo ([Skift, 22. 4. 2026](https://skift.com/2026/04/22/getyourguide-ai-updates/)).

### Polarsteps
- **Summer 2026 Release (9. 6. 2026):** zavihek Explore (trendi in kraji, ki so jih imeli radi prijatelji), načrtovanje na spletu, iskanje letov v aplikaciji, nastavitve zasebnosti lokacije in Trip Reels s preleti zemljevida. Aplikacijo uporablja več kot 20 mio uporabnikov.
- **Polarsteps Plus:** naročnina za zahtevnejše uporabnike, osnova ostaja brezplačna.

([Polarsteps](https://www.polarsteps.com/news/polarsteps-launches-summer-2026-release-new-tools-for-planning-privacy-and-sharing), [Polarsteps Plus](https://news.polarsteps.com/news/polarsteps-launches-polarsteps-plus-a-new-subscription-for-its-most-dedicated-travelers))

### Wanderlog
- Pro stane okoli 39,99 USD na leto, ocena v App Store je 4,9 (okoli 30.000 ocen). Pritožbe na Trustpilotu (majhen vzorec) zadevajo zaklenjene funkcije, samodejno podaljšanje naročnine in hrošče ([Trustpilot](https://www.trustpilot.com/review/wanderlog.com), [RecurDash](https://recurdash.com/subscription-pricing/wanderlog)).
- Novih funkcij v letu 2026 nisem našel.

### AI-zagonska podjetja
- **Layla:** več kot 1 mrd USD načrtovane vrednosti potovanj in 30 mio sporočil (mar. 2026). Krog financiranja aprila 2026 so vodili med drugim Baidu Capital in United Airlines Ventures ([Invest in Berlin](https://invest-in.berlin/n/berlins-layla-hits-1b-in-ai-planned-trip-value/), [Preqin](https://www.preqin.com/data/profile/asset/layla-ai-gmbh/575230)).
- **Mindtrip:** vlagatelji Amex, Capital One in United Ventures (dec. 2025), funkcije za dogodke in B2B za hotele ([BusinessWire](https://www.businesswire.com/news/home/20251208469469/en)).

---

## 🛠️ Kaj izboljšati v MRTrip (bolečine uporabnikov)

**Dejstva iz virov (Tripadvisor):**
- **Trustpilot tripadvisor.com:** 1,8/5 (3.936 ocen, 222 v zadnjih 12 mesecih). Ponavljajoče se teme v ocenah iz leta 2026 ([Trustpilot](https://www.trustpilot.com/review/www.tripadvisor.com)):
  1. *Nedosegljiva človeška podpora* (jan. in avg. 2026): "no possible human contact".
  2. *Pokvarjene rezervacije in izvedba ture*: vodnik ni prišel, ture so bile odpovedane, vstopnice niso prispele pravočasno (okt. 2026).
  3. *Plačila in vračila*: nepričakovano doplačilo pred turo, izgubljen denar (okt. 2026).
  4. *Moderacija ocen*: pristne ocene se "nepojasnjeno brišejo", prijavljene lažne pa ostanejo (okt. 2026).
  5. *Pretirana avtomatizacija*: "Extreme use of AI, and scripts that do not deal with problems" (maj 2026).
- **Trustpilot tripadvisor.ca:** 2,2/5. Pritožbe zadevajo zavrnjene ocene brez pojasnila, napačne podatke v listingih (npr. "State Parks" v Kanadi) in neveljaven kontaktni e-naslov (2026) ([Trustpilot CA](https://www.trustpilot.com/review/www.tripadvisor.ca)).
- **Zgodovinski kontekst:** britansko oglaševalsko nadzorstvo je presodilo, da so trditve o pristnosti ocen zavajajoče (datum ni potrjen, verjetno starejše) ([Pinsent Masons](https://www.pinsentmasons.com/out-law/news/tripadvisor-authenticity-claims-misleading-and-unsubstantiated-ad-watchdog-rules)). Raziskava Which? (okoli 2019, **zastarelo**) je pri 1 od 7 hotelov našla znake lažnih ocen ([Travel Weekly](https://travelweekly.co.uk/articles/342130/tripadvisor-flooded-with-fake-positive-reviews)).
- **Forumi:** ocene restavracij so "neuporabne", lokali, ki so zaprti, imajo še vedno ocene, kritike letijo tudi na plačane umestitve (forumi, mešani datumi; [early-retirement.org](https://www.early-retirement.org/forums/f46/rant-fake-tripadvisor-reviews-91471.html), [AFF](https://www.australianfrequentflyer.com.au/community/open-discussion/tripadvisor-do-you-use-it-65209.html)).

**Dejstva (podobne aplikacije):**
- **Wanderlog:** plačljivi zid pri načrtovanju, samodejno podaljšanje naročnine, hrošči ([Trustpilot](https://www.trustpilot.com/review/wanderlog.com)).
- **Skupinsko načrtovanje:** nove aplikacije se pozicionirajo proti "neskončnim skupinskim klepetom in preglednicam", z glasovanjem o predlogih. Med omejitvami se pogosto pojavlja delovanje brez povezave (iskanje offline ni mogoče) ([TripsTogether](https://apps.apple.com/mx/app/tripstogether-group-plans/id6746410460), [TripHugger](https://apps.apple.com/us/app/triphugger-travel-planner/id882313848), [Planiter](https://apps.apple.com/app/id6749773392)).
- **AI:** 51 % popotnikov dvomi v točnost AI-priporočil ([Skift](https://skift.com/2026/10/13/skift-data-ai-summit-europe-2026-ai-is-ubiquitous-yet-still-unconquered/)).

**Izluščene bolečine, ki jih MRTrip lahko reši bolje (moja interpretacija):**
1. **Zaupanje v ocene:** preglednost, zakaj je ocena prikazana ali odstranjena, ter značka "preverjen obisk".
2. **Ažurnost podatkov:** zaprti lokali in napačni delovni časi.
3. **Človeška podpora in jasni pogoji** pri rezervacijah in vračilih.
4. **Preprostost brez agresivnih plačljivih zidov.**
5. **Skupinsko odločanje in delovanje brez povezave.**

---

## 💡 Inovacije in ideje

**Dejstva (kaj se dogaja na trgu):**
- **Distribucija prek AI-asistentov:** Tripadvisor, Booking in Expedia gradijo aplikacije v ChatGPT, Claude in Alexa+ ([Tripadvisor](https://tripadvisor.mediaroom.com/2026-04-23-How-AI-Is-Changing-the-Way-We-Plan-Travel), [ShortTermRentalz](https://shorttermrentalz.com/news/chatgpt-launches-travel-apps-with-expedia-and-booking-com/)).
- **Od videa do itinerarija:** Tripadvisor ima prototip, PhocusWire poroča, da ima GetYourGuide podobno funkcijo ([AltexSoft](https://www.altexsoft.com/travel-industry-news/tripadvisor-debuts-ai-planner-for-video-based-trips/), [PhocusWire](https://www.phocuswire.com/getyourguide-product-launch-ai-influencer-video)).
- **AI-povzetki ocen** so postali standard (GetYourGuide, Airbnb) ([Skift](https://skift.com/2026/04/22/getyourguide-ai-updates/)).
- **AI-podpora z obvezno predajo človeku** (Booking) ([Hospitality Net](https://www.hospitalitynet.org/news/4129287/bookingcom-debuts-agentic-ai-innovations-adding-to-its-robust-suite-of-genai-tools-for-customers)).
- **Zasebnost lokacije in socialno odkrivanje** (Polarsteps Explore, Airbnb jesen 2026) ([Polarsteps](https://www.polarsteps.com/news/polarsteps-launches-summer-2026-release-new-tools-for-planning-privacy-and-sharing)).
- **Regulativa EU:** Digital Fairness Act je napovedan za konec leta 2026. Cilja na temne vzorce (dark patterns), lažne ocene, pasti pri naročninah in prikrito oglaševanje influencerjev. Besedilo še ni objavljeno ([Pinmeto](https://www.pinmeto.com/news/eu-digital-fairness-act-scope-split-2026/), [Evropski parlament](https://www.europarl.europa.eu/legislative-train/theme-protecting-our-democracy-upholding-our-values/file-digital-fairness-act)).
- **Stroški podatkov:**
  - Google Maps Platform je 1. 3. 2025 $200 mesečnega kredita zamenjal z brezplačnimi kvotami po posameznem SKU. Places API (New) obračunava po najvišjem SKU glede na zahtevana polja ([Google](https://developers.google.com/maps/billing-and-pricing/march-2025)).
  - Tripadvisor Content API: glej zgoraj (status ni potrjen).

**Ideje za MRTrip (moja priporočila):**
- **"Zaupanje kot funkcija":** ocene samo s preverjenim obiskom (geolokacija ali potrdilo o rezervaciji), javen prikaz razloga za moderacijo, jasna oznaka sponzoriranih vsebin (to tudi pripravi aplikacijo na DFA) in "Zadnjič preverjeno: datum" pri vsaki točki.
- **"Iz reela v načrt":** uporabnik prilepi povezavo TikTok/Instagram, AI izlušči kraje, MRTrip pa jih preveri z lastnimi ali Google podatki in sestavi dnevni načrt. Tripadvisor ima to šele kot prototip.
- **MRTrip kot vir za AI-asistente:** aplikacija ali MCP-strežnik za ChatGPT oziroma Claude z lokalnimi priporočili za Slovenijo in regijo. Tako se vidnost gradi tam, kjer uporabniki že načrtujejo.
- **Skupinsko načrtovanje:** glasovanje o predlogih, delitev stroškov in skupni itinerarij z delovanjem brez povezave.
- **Lokalni nišni podatki:** Slovenija ima 75 % tujih prenočitev, največ jih ustvarijo Nemci, Italijani in Avstrijci. Zato so pomembni večjezičnost (DE/IT/EN), "skriti biseri" in trajnostne alternative prenatrpanim točkam (npr. Bled), kar je usklajeno z usmeritvijo STO.

---

## ✅ Priporočila (prioritizirana)
| # | Ideja | Zakaj (vir) | Vpliv (V/S/N) | Trud (V/S/N) |
|---|---|---|---|---|
| 1 | **Pregledne ocene:** oznaka "preverjen obisk", javni razlog ob zavrnitvi ocene, jasna oznaka sponzoriranega | Brisanje ocen in lažne ocene sta glavni pritožbi pri Tripadvisorju ([Trustpilot](https://www.trustpilot.com/review/www.tripadvisor.com)); 51 % dvomi v točnost AI ([Skift](https://skift.com/2026/10/13/skift-data-ai-summit-europe-2026-ai-is-ubiquitous-yet-still-unconquered/)); prihaja DFA ([Pinmeto](https://www.pinmeto.com/news/eu-digital-fairness-act-scope-split-2026/)) | V | N–S |
| 2 | **"Zadnjič preverjeno" in gumb "Prijavi napako/zaprto"** pri vsaki točki | Pritožbe zaradi zastarelih in napačnih listingov ([Trustpilot CA](https://www.trustpilot.com/review/www.tripadvisor.ca), [forum](https://www.early-retirement.org/forums/f46/rant-fake-tripadvisor-reviews-91471.html)) | S–V | N |
| 3 | **AI-povzetek ocen z navedbo virov** (citati iz ocen, ne izmišljene trditve) | Standard pri GetYourGuide in Airbnb ([Skift](https://skift.com/2026/04/22/getyourguide-ai-updates/), [EFTM](https://eftm.com/2026/05/airbnb-expands-beyond-stays-with-ai-powered-customer-support-grocery-deliveries-pickups-and-more-experiences-276021)) | S | N |
| 4 | **Dosegljiva človeška podpora** (AI kot prvi odziv, vedno z gumbom "človek") | "No possible human contact" ([Trustpilot](https://www.trustpilot.com/review/www.tripadvisor.com)); Booking ima predajo človeku ([Hospitality Net](https://www.hospitalitynet.org/news/4129287/bookingcom-debuts-agentic-ai-innovations-adding-to-its-robust-suite-of-genai-tools-for-customers)) | V | S |
| 5 | **"Iz reela v načrt"** (povezava TikTok/IG pretvorjena v dnevni itinerarij za SLO/regijo) | 48 % Gen Z se navdihuje na TikToku ([Euronews](https://www.euronews.com/travel/2026/08/21/i-saw-it-on-tiktok-48-of-gen-z-travellers-turn-to-the-platform-for-travel-inspiration)); Tripadvisor ima to le kot prototip ([AltexSoft](https://www.altexsoft.com/travel-industry-news/tripadvisor-debuts-ai-planner-for-video-based-trips/)) | V | S |
| 6 | **AI kot pomočnik za načrtovanje, ne za samodejno rezervacijo** (rezervacija prek preverjenega partnerja) | 71 % sprejema AI-ideje, AI-ju rezervacijo prepusti le 2–16 % ([Skift](https://skift.com/2026/03/03/travel-brands-are-building-ai-agents-for-a-consumer-that-doesnt-exist/), [Skift/McKinsey](https://skift.com/insights/new-report-winning-hearts-in-an-age-of-infinite-travel-choices/)) | S | N |
| 7 | **Skupinsko načrtovanje z glasovanjem in offline itinerarijem** | Ponavljajoča se bolečina pri organizaciji skupin in delovanju brez povezave ([TripsTogether](https://apps.apple.com/mx/app/tripstogether-group-plans/id6746410460), [TripHugger](https://apps.apple.com/us/app/triphugger-travel-planner/id882313848)) | S–V | S |
| 8 | **Večjezičnost DE/IT/EN in vsebine "skritih biserov" ter trajnostnih alternativ** | Struktura gostov v SLO 2025 ([RTV SLO](https://www.rtvslo.si/zabava-in-slog/ture-avanture/slovenijo-lani-obiskalo-rekordno-stevilo-turistov/771021)); usmeritev STO ([slovenia.info](https://www.slovenia.info/sl/novinarsko-sredisce/sporocila-za-javnost/36160-slovenski-turizem-v-2025-ob-zmerni-rasti-v-ospredju-kakovost-trajnost-in-dolgorocna-odpornost)) | S | S |
| 9 | **Aplikacija ali MCP-strežnik MRTrip za ChatGPT/Claude** | Konkurenti distribuirajo prek AI-asistentov ([Tripadvisor](https://tripadvisor.mediaroom.com/2026-04-23-How-AI-Is-Changing-the-Way-We-Plan-Travel)); AI-napotitve so sicer še pod 2 % ([Skift](https://skift.com/2026/10/13/skift-data-ai-summit-europe-2026-ai-is-ubiquitous-yet-still-unconquered/)) | S | V |
| 10 | **Poštena monetizacija:** brez plačljivega zidu pri osnovnem načrtovanju, opomnik pred podaljšanjem naročnine | Pritožbe pri Wanderlogu ([Trustpilot](https://www.trustpilot.com/review/wanderlog.com)); model Polarsteps (brezplačna osnova + Plus) ([Polarsteps](https://news.polarsteps.com/news/polarsteps-launches-polarsteps-plus-a-new-subscription-for-its-most-dedicated-travelers)); DFA cilja na pasti pri naročninah | S | N |

*Hitre zmage: #2, #3, #1, #6, #10.*

---

## 🆕 Novo od zadnjega poročila
To je prvo poročilo, zato prejšnjih ugotovitev ni. Za naslednje poročilo predlagam:
- dopolnitev z rezultati Tripadvisorja za Q3 2026 (objava 5. 11. 2026);
- preverjanje statusa Tripadvisor Terra API in zaključka prodaje TheFork;
- spremljanje objave osnutka Digital Fairness Act.

---

## Viri
- Tripadvisor – How AI Is Changing the Way We Plan Travel (23. 4. 2026): https://tripadvisor.mediaroom.com/2026-04-23-How-AI-Is-Changing-the-Way-We-Plan-Travel
- Tripadvisor – prodaja TheFork (15. 6. 2026): https://tripadvisor.mediaroom.com/2026-06-15-Tripadvisor-Enters-into-Agreement-to-Sell-TheFork-to-American-Express-for-700-Million
- AltexSoft – TheFork (2026): https://www.altexsoft.com/travel-industry-news/tripadvisor-sells-thefork-as-experiences-take-priority/
- Quartr – Tripadvisor Q2 2026: https://quartr.com/events/tripadvisor-inc-trip-q2-2026_3Y1ZAk89
- AOL – Tripadvisor Q4 2025 transkript (12. 2. 2026): https://www.aol.com/finance/tripadvisor-trip-q4-2025-earnings-171701174.html
- MarketBeat – Q4 2025 poudarki: https://www.marketbeat.com/instant-alerts/tripadvisor-q4-earnings-call-highlights-2026-02-12/?.tsrc=rss
- Placera – napoved Q3 2026 (20. 10. 2026): https://www.placera.se/pressmeddelanden/tripadvisor-tripadvisor-to-host-third-quarter-2026-financial-results-conference-call-on-november-5-2026-20261020
- Tripadvisor v ChatGPT: https://www.tripadvisor.com/ChatGPT
- Tom's Guide – ChatGPT aplikacije (nov. 2025): https://www.tomsguide.com/ai/tripadvisor-and-peloton-are-chatgpts-first-built-in-apps-apple-and-google-should-be-worried
- AltexSoft – video-to-itinerary (26. 3. 2026): https://www.altexsoft.com/travel-industry-news/tripadvisor-debuts-ai-planner-for-video-based-trips/
- PR Newswire – Best Western × Tripadvisor (29. 1. 2026): https://www.prnewswire.com/news-releases/best-western-hotels--resorts-and-tripadvisor-launch-ai-powered-trip-planning-experience-to-help-soccer-fans-navigate-2026-travel-302673239.html
- Tripadvisor 2025 Transparency Report (18. 3. 2025): https://tripadvisor.mediaroom.com/2025-03-18-Tripadvisors-2025-Transparency-Report-reveals-strong-review-submissions-and-improved-fraud-detection?asPDF=1
- NBC/CNBC – lažne ocene 2024 (2025): https://www.nbcnewyork.com/news/business/money-report/heres-how-many-fake-reviews-tripadvisor-found-on-its-website-in-2024/6277840/
- Pinsent Masons – oglaševalsko nadzorstvo (datum ni potrjen): https://www.pinsentmasons.com/out-law/news/tripadvisor-authenticity-claims-misleading-and-unsubstantiated-ad-watchdog-rules
- Travel Weekly – Which? (okoli 2019, zastarelo): https://travelweekly.co.uk/articles/342130/tripadvisor-flooded-with-fake-positive-reviews
- Trustpilot – tripadvisor.com (dostopano 2. 11. 2026): https://www.trustpilot.com/review/www.tripadvisor.com
- Trustpilot – tripadvisor.ca (dostopano 2. 11. 2026): https://www.trustpilot.com/review/www.tripadvisor.ca
- Forum early-retirement.org: https://www.early-retirement.org/forums/f46/rant-fake-tripadvisor-reviews-91471.html
- Forum Australian Frequent Flyer: https://www.australianfrequentflyer.com.au/community/open-discussion/tripadvisor-do-you-use-it-65209.html
- Tripadvisor Content API FAQ: https://tripadvisor-content-api.readme.io/reference/faq
- SocialCrawl – Tripadvisor API 2026 (nepreverjeno): https://www.socialcrawl.dev/blog/best-tripadvisor-data-apis-2026
- Skift – Data + AI Summit Europe (13. 10. 2026): https://skift.com/2026/10/13/skift-data-ai-summit-europe-2026-ai-is-ubiquitous-yet-still-unconquered/
- Skift – AI agenti za neobstoječega potrošnika (3. 3. 2026): https://skift.com/2026/03/03/travel-brands-are-building-ai-agents-for-a-consumer-that-doesnt-exist/
- Skift – Remapping Travel With Agentic AI: https://skift.com/insights/new-report-remapping-travel-with-agentic-ai/
- Skift – Winning Hearts in an Age of Infinite Travel Choices: https://skift.com/insights/new-report-winning-hearts-in-an-age-of-infinite-travel-choices/
- Asianet – povzetek Skift/McKinsey (2026): https://newsable.asianetnews.com/business/report-travellers-embrace-ai-for-planning-draw-line-at-booking-articleshow-f724tdg
- Skift – GetYourGuide AI (22. 4. 2026): https://skift.com/2026/04/22/getyourguide-ai-updates/
- PhocusWire – GetYourGuide video: https://www.phocuswire.com/getyourguide-product-launch-ai-influencer-video
- TechCrunch – Google AI Mode (27. 8. 2026): https://techcrunch.com/2026/08/27/googles-ai-mode-can-now-track-flight-prices-help-book-hotels-and-more/
- eMarketer – Google AI potovanja: https://www.emarketer.com/content/google-expands-ai-travel-planning-and-booking-tools
- Search Engine Journal – Google agentic booking: https://www.searchenginejournal.com/google-extends-ai-travel-planning-and-agentic-booking-in-search/
- Hospitality Net – Booking.com agentic AI (9. 10. 2025): https://www.hospitalitynet.org/news/4129287/bookingcom-debuts-agentic-ai-innovations-adding-to-its-robust-suite-of-genai-tools-for-customers
- monkeytravel – AI travel agents 2026 (sekundarno): https://monkeytravel.app/blog/best-ai-travel-agents-2026
- ShortTermRentalz – ChatGPT aplikacije Expedia/Booking: https://shorttermrentalz.com/news/chatgpt-launches-travel-apps-with-expedia-and-booking-com/
- EFTM – Airbnb (maj 2026): https://eftm.com/2026/05/airbnb-expands-beyond-stays-with-ai-powered-customer-support-grocery-deliveries-pickups-and-more-experiences-276021
- AltexSoft – Airbnb: https://www.altexsoft.com/travel-industry-news/airbnb-adds-cars-hotels-ai-to-keep-trips-in-app/
- eMarketer – Airbnb super app (403, nepreverjeno): https://www.emarketer.com/content/airbnb-transforms-super-app-services-experiences-with-ai
- Polarsteps Summer 2026 (9. 6. 2026): https://www.polarsteps.com/news/polarsteps-launches-summer-2026-release-new-tools-for-planning-privacy-and-sharing
- Polarsteps Plus: https://news.polarsteps.com/news/polarsteps-launches-polarsteps-plus-a-new-subscription-for-its-most-dedicated-travelers
- Trustpilot – Wanderlog: https://www.trustpilot.com/review/wanderlog.com
- RecurDash – cene Wanderlog: https://recurdash.com/subscription-pricing/wanderlog
- Invest in Berlin – Layla (2026): https://invest-in.berlin/n/berlins-layla-hits-1b-in-ai-planned-trip-value/
- Preqin – Layla: https://www.preqin.com/data/profile/asset/layla-ai-gmbh/575230
- BusinessWire – Mindtrip (8. 12. 2025): https://www.businesswire.com/news/home/20251208469469/en
- Euronews – TUI Musement / TikTok (21. 8. 2026): https://www.euronews.com/travel/2026/08/21/i-saw-it-on-tiktok-48-of-gen-z-travellers-turn-to-the-platform-for-travel-inspiration
- RTV SLO – rekordno turistično leto 2025 (23. 1. 2026): https://www.rtvslo.si/zabava-in-slog/ture-avanture/slovenijo-lani-obiskalo-rekordno-stevilo-turistov/771021
- STO – slovenski turizem 2025: https://www.slovenia.info/sl/novinarsko-sredisce/sporocila-za-javnost/36160-slovenski-turizem-v-2025-ob-zmerni-rasti-v-ospredju-kakovost-trajnost-in-dolgorocna-odpornost
- gov.si (7. 1. 2026): https://www.gov.si/novice/2026-01-07-slovenski-turizem-v-2025-ob-zmerni-rasti-v-ospredju-kakovost-trajnost-in-dolgorocna-odpornost/
- Pinmeto – Digital Fairness Act (2026): https://www.pinmeto.com/news/eu-digital-fairness-act-scope-split-2026/
- Evropski parlament – Legislative train DFA: https://www.europarl.europa.eu/legislative-train/theme-protecting-our-democracy-upholding-our-values/file-digital-fairness-act
- Google – sprememba cen Maps Platform (1. 3. 2025): https://developers.google.com/maps/billing-and-pricing/march-2025
- App Store – TripsTogether: https://apps.apple.com/mx/app/tripstogether-group-plans/id6746410460
- App Store – TripHugger: https://apps.apple.com/us/app/triphugger-travel-planner/id882313848
- App Store – Planiter: https://apps.apple.com/app/id6749773392
