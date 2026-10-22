# Scenlista – WinWin Support, presentationsvideo för föreningar

**Färger (från logotypen, 7 okt 2026):** mörkblå `#144772`, gul `#FFD103` (bara som accent/punkt, aldrig som text på vitt), vit `#FFFFFF`.
Stödfärger i videon: ljusblå bakgrund `#EAF1F8`, mycket ljus `#F5F8FB`, djupblå för undertextplatta `#0E3356`, brödtext `#1F2A37`.
Ingen korall. Den gamla WPSS-färgen `#FF6D54` används inte alls.

**Typsnitt:** Oswald Bold (rubriker, versaler i logotypen), Oswald Regular, Open Sans (brödtext, undertexter). Båda fria (SIL OFL) och finns i Google Fonts.

**Undertexter:** hela vägen, vit text på djupblå platta längst ner (16:9) eller i nedre tredjedelen ovanför appgränssnittet (9:16).

**Övergångar:** mjuk övertoning 0,6 s mellan scener. Inom scenen glider element in underifrån (0,55 s). Inga wipes, inga snabba zoomar.

| # | Tid | Bakgrund | Bild / grafik | Text i bild | Rörelse | Övergång ut |
|---|---|---|---|---|---|---|
| 1 | 0:00–0:07 | Mycket ljus (#F5F8FB) | Illustration: mötesbord uppifrån med fem abstrakta personer (cirklar, inga ansikten). En pratbubbla tänds vid en av dem. **Alternativ:** eget filmklipp från ett riktigt styrelsemöte, se 03-musik-och-material.md. | Etikett: *Styrelsemötet* · Rubrik: **Vem i styrelsen tar hand om hemsidan?** ("hemsidan" med gul understrykning) | 0,3 s: bord och personer. 1,0 s: etikett. 1,8 s: rubriken. 3,5 s: pratbubbla med "?" | Övertoning till blått |
| 2 | 0:07–0:16 | Mörkblå (#144772), vit text | Vit liggande logotyp. Två platshållare (streckade ramar) för filmklipp: **Maya Raw Granholm, Hemsida & innehåll** och **Anders Granholm, Teknik & support**. Liten kartnål + "Täby, Stockholm". | **Det gör vi.** (stort) · *WinWin Support förvaltar föreningars WordPress-hemsidor* · platshållartexter · *Täby, Stockholm · Svenskt aktiebolag* | 0,2 s: "Det gör vi." 1,3 s: logotyp + underrad. 2,6 s / 3,2 s: platshållarna. 4,5 s: Täby-raden. | Övertoning till vitt |
| 3 | 0:16–0:31 | Vit | Tre kort med enkla ikoner (klocka, person, nyckel/hus). Under: tagline med gul punkt. | Etikett: *Tre löften till styrelsen* · Kort 1: **Svar inom 24 timmar** / oftast samma arbetsdag · Kort 2: **Samma kontaktperson** / Maya eller Anders, aldrig en supportkö i ett annat land · Kort 3: **Ni äger hemsidan** / domän, webbhotell och innehåll är era · Tagline: **Ni äger. Vi stöttar.** | Korten tänds i takt med rösten: 0,5 s, 4,0 s, 8,5 s. Tagline 12,5 s. | Övertoning till ljusblått |
| 4 | 0:31–0:44 | Ljusblå (#EAF1F8) | Vänster: statusruta "Det här sköter vi åt er" med tre bockar som tänds. Höger: prisbricka och tre chips. Längst ner ett citat. | Rubrik: **Det här slipper styrelsen tänka på** · Bockar: Uppdateringar testade och installerade · Säkerhetskopia tas varje dag, inom EU · Övervakningen är igång dygnet runt · Prisbricka: **350 kr/mån** exkl. moms, fast pris, samma för alla föreningar · Chips: Svenskt aktiebolag med svensk personal · Ingen bindningstid · Prova i tre månader, annars pengarna tillbaka · Citat: *"Händer något är vi oftast redan igång, innan någon i styrelsen hunnit märka det."* | Rubrik 0,3 s. Bockar 1,0 / 2,0 / 3,0 s. Citat 5,0 s. Prisbricka 8,5 s. Chips 9,5 / 10,2 / 10,9 s. | Övertoning till vitt |
| 5 | 0:44–0:51 | Vit | Tre kort "Styrelsen 2024 / 2025 / 2026" där personprickarna byter färg mellan åren. Under korten ett sammanhängande blått band med WW-märket. | Rubrik: **Vi finns kvar när styrelsen byts ut** · Band: *WinWin Support, samma kontakt hela vägen* · Underrad: *Vi vet hur hemsidan är byggd.* | Rubrik 0,3 s. Kort 1,0 / 1,8 / 2,6 s. Band växer fram 3,2 s. Underrad 4,5 s. | Övertoning till blått |
| 6 | 0:51–1:00 | Mörkblå (#144772), vit text | Vit logotyp. CTA-ruta med gul kant. Kontaktrad. Liten avsändarrad längst ner. | **Föreningar och styrelser är det bästa vi vet.** · CTA: **Be om en kostnadsfri genomgång av er hemsida** / Inga lösenord behövs · Inget säljsamtal · Svar inom 24 timmar · Kontakt: **0707-92 32 52** · anders@winwinsupport.se · **winwinsupport.se** · Avsändare: WinWin Support är en tjänst från Win Win Web AB, Täby. Tidigare WordPress Support Sverige. | Rubrik 0,3 s. Logotyp 1,5 s. CTA 3,0 s. Kontakt 4,5 s. Avsändarrad 6,0 s. Slutbilden ligger kvar. | Håll 3–4 s, sedan fade till svart i klippprogrammet |

## Så används HTML-filen

`video.html` spelar upp allt ovan med rätt tider, undertexter och animationer.

- Öppna filen i Chrome eller Edge. Klicka på startrutan (eller tryck mellanslag).
- **16:9** är standard. Tryck **F** för 9:16 (eller öppna `video.html?format=9x16`).
- **Mellanslag** = paus/spela · **R** = börja om · **H** = helskärm · **U** = undertexter av/på · **F** = byt format.
- För inspelning: `video.html?format=16x9&autoplay=1` startar direkt utan startruta, och kontrollerna döljs. Spela in i helskärm (H) med EaseUS eller annan skärminspelare, 1920×1080 för 16:9 och 1080×1920 för 9:16.
- Platshållarna för Maya och Anders är streckade rutor i bilden. I klippprogrammet (FilmCraft) läggs de riktiga klippen ovanpå på exakt samma plats, eller så klipps scen 2 om med klippen i helbild och logotypen i hörnet.
