IDÉCAFÉ 2026 – MESSEJAGTEN (LOKAL TESTVERSION)

INSTALLATION
1. Pak ZIP-filen ud.
2. Upload index.html, style.css og app.js til roden af GitHub-repository Idécafe2026.
3. GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root).
4. Besøg https://nduru88-wq.github.io/Id%C3%A9cafe2026/ (GitHub viser den endelige URL under Pages).

TEST
- Åbn Administration, og tilpas prøvejagten eller opret en ny.
- Åbn Deltager, og opret et hold på 2–4 deltagere.
- Besvar opgaver, spring over, gå tilbage og aflever.
- Åbn Administration > Hold og bedømmelse, bedøm svar og offentliggør point.
- Data kan eksporteres som JSON fra administrationen.

VIGTIGE BEGRÆNSNINGER
- Alle data gemmes KUN i browserens localStorage. Data på to telefoner deles ikke.
- Ingen sikker administratorlogin eller serverbaseret databeskyttelse.
- QR-deltagerlink og QR-scanning er endnu ikke implementeret; QR-opgaver bruger manuel kodeindtastning.
- Foto gemmes komprimeret i browseren; lokalStorage har en begrænset kvote.
- Holdkoder er kun til lokal genoptagelse; ikke sikker autentifikation.
- Tilfældig opgaverækkefølge bruger forskudt startposition, ikke en fuld blanding.
- Ved pointlighed sorteres efter afleveringstidspunkt, ikke reel gennemførselstid; dette ændres i Supabase-versionen.
- Intet slettes automatisk efter 30 dage i denne testversion.
- Brug kun opdigtede testdata, ikke personfølsomme oplysninger.

NÆSTE FASE
Supabase: serverlagring, sikker adminlogin, QR-scanning, hold på tværs af telefoner, ægte tidsmåling, billedopbevaring med 30-dages oprydning, og realtidsresultater.
