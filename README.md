# Praha Parking – iPhone PWA

## Nasazení zdarma
1. Nahraj do kořene repozitáře `R64L/Parking` soubory `index.html`, `manifest.webmanifest`, `sw.js` a složku `icons` (oba PNG soubory).
2. GitHub > Settings > Pages > Deploy from a branch > main / (root).
3. Otevři na iPhonu v Safari `https://r64l.github.io/Parking/`.
4. V Safari klepni Sdílet > Přidat na plochu (případně Otevřít jako webovou aplikaci).
5. Spusť ikonou na ploše a povol polohu.

## Poznámky
- Externí služby Photon, OSRM, OpenStreetMap a pražský ArcGIS vyžadují internet; veřejná API nemají garantovanou dostupnost.
- Provozní hodiny parkovacích zón nejsou automaticky ověřeny. Doby návštěvnického parkování jsou pouze orientační. Místní značení má přednost.
- Navigace je orientační, při odbočení sama nepřepočítá trasu; GPS nefunguje spolehlivě při uzamčení iPhonu.
- Při řízení ovládá aplikaci pouze spolujezdec, řidič jedině po zastavení.
