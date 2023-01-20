# SA-LiamHamelryck-Logboek-2223
<ol>
<li>Week 1 (19-25/09)
<ul>
<li>Nog geen voortgang wegens onduidelijkheden i.v.m. ISP.</li>
</ul>
</li>
<li>Week 2 (26/09-2/10)
<ul>
<li>Projectvoorstel FKA "BeerReal" uit de doeken gedaan</li>
<li>Sociale media app op basis van bier met OCR-functionaliteit</li>
<li>Naam bier wordt via OCR opgehaald en gebruikt voor API-request RateBeer.com om info over bier op te vragen</li>
<li>Repos voor project en logboek aangemaakt</li>
<li>Uiteindelijk aangesloten bij groep Stanislas en Mohamed - discussie over eventuele OCR-implementatie in project "F*ckPaper" volgt</li>
</ul>
</li>
<li>Week 3 (3-9/10)</li>
<ul>
<li>Figma-mockup afgewerkt en uitgebreid om OCR-functionaliteit te demonstreren - UI geinspireerd op UNIX-style file explorers (cf. GNOME, MacOS voor desktop, Android, iOS voor mobile)</li>
<li>Gebrainstormd over OCR-implementatie in F*ckPaper</li>
<li>Gebrainstormd over welke bestandtypes ondersteund zullen worden in de app: PDF en EPUB zijn musts, de rest nice-to-have</li>
<li>Er zal ook in de UI een onderscheid bestaan tussen boeken en notities (OCR-gescande docs zullen automatisch onder notities vallen)</li>
<li>Gestart aan crash course ReactJS ter voorbereiding van code schrijven vanaf volgende week</li>
</ul>
<li>Week 4 (10-16/10)</li>
<ul>
<li>Rollen verdeeld (uiteraard met ruimte voor flexibiliteit)</li>
<li>Ik zal de backend doen en de verbinding met Firebase verzorgen</li>
<li>Firebase-gerelateerde codelabs van bij Advanced Web & Mobile hermaakt</li>
<li>As-is repository (frontend) in React met Stan doorlopen zodat ik zijn practices kan overnemen bij bijdragen tot frontend (uniformiteit)</li>
<li>Firebase-project en -database aangemaakt</li>
<li>Branch in repository aangemaakt voor Firebase-verbinding en testen checksumberekening (om duplicate uploads te vermijden)</li>
</ul>
</li>
<li>Week 5 (17-23/10)</li>
<ul>
<li>User authenticatie toegevoegd</li>
<li>Eerste poging om files naar storage bucket te uploaden (zonder hash)</li>
</ul>
</li>
<li>Week 6 (24-30/10)</li>
<ul>
<li>User authenticatie toegevoegd</li>
<li>Eerste poging om files naar storage bucket te uploaden (zonder hash)</li>
</ul>
</li>
<li>Week 7 (31/10-6/11)</li>
<ul>
<li>HTML-projectje aangemaakt voor makkelijker contact met de backend</li>
<li>Manipulatie van user account toegevoegd (wachtwoord veranderen, account verwijderen...)</li>
</ul>
</li>
<li>Week 8 (7-13/11)</li>
<ul>
<li>Boekenupload toegevoegd met hashberekening</li>
<li>Firestore collectie toegevoegd voor boeken per gebruiker. Hash en user ID worden opgeslagen samen met metadata</li>
<li>Notes-functionaliteit toegevoegd</li>
</ul>
</li>
<li>Week 9 (14-20/11)</li>
<ul>
<li>Mogelijkheid toegevoegd om notes up te loaden via tekstbestand</li>
</ul>
</li>
<li>Week 10 (21-27/11)</li>
<ul>
<li>Geen verandering</li>
</ul>
</li>
<li>Week 11 (28/11-4/12)</li>
<ul>
<li>PDF-lib toegevoegd om metadata uit upgeloade files te halen en vopor te stellen als voor de gebruiker specifieke metadata</li>
<li>iframe toegevoegd als proof of concept om boeken in de browser te tonen (lukt niet op alle mobiele browsers)</li>
<li>Volledige CRUD van boeken per gebruiker (bv. verwijderen van Firestore document voor boek voor gebruiker zonder dat de file in de bucket wordt verwijderd)</li>
</ul>
</li>
<li>Week 12 (5-11/12)</li>
<ul>
<li>Geen verandering</li>
</ul>
</li>
<li>Week 13 (13-19/12)</li>
<ul>
<li>Samengewerkt met Stan om de backend in het (tot nu toe "mockup") React project te verwerken</li>
</ul>
</li>
<li>Week 14 (20-26/12)</li>
<ul>
<li>Verdere verwerking van backend in tot nog toe lege frontend. React-app heeft nu alle functionaliteit van het HTML-projectje</li>
<li>Gewerkt aan functionaliteiten i.v.m. PWA (service workers, web manifest, lighthouse tests)</li>
</ul>
</li>
<li>Week 15 (27/12-2/1)</li>
<ul>
<li>Geen verandering (feestdagen)</li>
</ul>
</li>
<li>Week 16 (3/1-9/1)</li>
<ul>
<li>Boekcovers toegevoegd</li>
<li>Bugfixes en UI inconsistencies weggewerkt</li>
<li>TinyMCE toegevoegd om notes te formatteren</li>
<li>Tesseract.js toegevoegd om notes uit foto's te extracten</li>
</ul>
</li>
<li>Week 17 (10/1-17/1)</li>
<ul>
<li>Finishing touches</li>
<li>Persistence voor logins gefixd</li>
<li>Recents tab toegevoegd per gebruiker</li>
<li>Fixes i.v.m. IndexedDB</li>
</ul>
</li>
