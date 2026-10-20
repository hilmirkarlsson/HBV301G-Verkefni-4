# Notkunartilvik

## Helstu notkunartilvik

| ID | Heiti | Aðalgerandi | Markmið |
|---|---|---|---|
| UC-1 | Kaupa miða á netinu | Kaupandi | Skoða miða, taka þá frá og kaupa þá án hjálpar frá starfsmanni |
| UC-2 | Færa miða á annan dag eða sýningu | Kaupandi | Breyta miða sem er þegar keyptur |
| UC-3 | Bóka aðgengissæti | Kaupandi með fötlun | Bóka sæti sem hentar þörfum hans |
| UC-4 | Fá aðstoð í netspjalli | Kaupandi | Fá svar við spurningu eða ná í starfsmann kl. 8–16 |
| UC-5 | Fylgjast með sölu viðburðar | Viðburðarhaldari | Sjá vinsælustu sætin og hvort sýning er að fyllast |
| UC-6 | Setja upp viðburð | Rekstraraðili | Skrá viðburð í kerfið |

## Ítarleg lýsing á einu notkunartilviki

**ID:** UC-1  
**Heiti:** Kaupa miða á netinu  
**Aðalgerandi:** Kaupandi  
**Aukagerendur:** Greiðslulausn, viðburðarhaldari (setur reglurnar)

## Forsendur
- Viðburðurinn er í sölu og viðburðarhaldari hefur sett upp reglur fyrir hann.
- Kaupandi kemst á vefinn.

## Eftirskilyrði
- Miðarnir eru keyptir og sætin frátekin fyrir kaupandann.
- Viðburðarhaldari hefur upplýsingar um kaupandann og salan sést hjá honum.

## Aðalflæði
1. Kaupandi opnar BookIt og velur viðburð og sýningu.
2. Kerfið sýnir hvaða miðar og sæti eru laus.
3. Kaupandi velur sæti og fjölda miða, innan þess hámarks sem viðburðarhaldari hefur sett.
4. Kerfið tekur miðana frá í körfu.
5. Kaupandi fær afslátt eða áskriftarafslátt ef það á við.
6. Kaupandi fer í greiðsluleiðina og greiðir.
7. Kerfið staðfestir kaupin og kaupandi fær miðana.

## Valflæði
- A1: Vinsæll viðburður er að fara í sölu. Kaupandi fer fyrst í forstofu og er afgreiddur þaðan í röð eða af handahófi, áður en skref 1 hefst.
- A2: Kaupandi þarf aðgengissæti. Þá býður kerfið sérstök sæti fyrir fatlaða í skrefi 2.
- A3: Foreldri kaupir fyrir barn. Kaupin eru á nafni foreldrisins.
- A4: Kaupandi hefur spurningu í ferlinu. Hann opnar netspjallið.

## Undantekningar
- E1: Frátekningin rennur út áður en kaupandi greiðir. Miðarnir fara aftur í almenna sölu. Nákvæmur tími er óákveðinn.
- E2: Greiðsla tekst ekki. Viðmælendur svöruðu ekki hvað á að gerast.
- E3: Miðarnir seljast upp. Viðmælendur svöruðu ekki hvað á að gerast.
- E4: Netið rofnar. Þau sögðu að það væri ekki gert ráð fyrir því.
- E5: Kaupandi velur rangan dag eða ranga sýningu. Hann getur fært miðann með UC-2.

## Forgangur
- Ekki rætt í viðtalinu.

## Tíðni notkunar
- Ekki rætt í viðtalinu.

## Viðskiptareglur
- BR-1, BR-2, BR-3, BR-4, BR-5, BR-6, BR-7

## Forsendur (Assumptions)
- Greiðsluleiðin er ekki alfarið í höndum BookIt (C-1).

## Annað
- Ekkert annað :)