<div align="center">

![Vrachtplanner](docs/readme-banner.svg)

**Van rooster en vrachtgegevens naar een verwachte eindtijd voor de colli.**

[![Open de Vrachtplanner](https://img.shields.io/badge/Open_de_Vrachtplanner-BA2925?style=for-the-badge&logo=googlechrome&logoColor=white)](https://vrachtplanner.tijnd.nl/)

[Gebruikersgids](#gebruikersgids) · [Rekenregels](#hoe-rekent-de-planner)

</div>

---

## Gebruikersgids

1. **Kies je dag** in **Planning**. Selecteer de datum waarop je de vracht verwerkt.
2. **Controleer de invoer** onder **Personeel** en **Vrachtgegevens**.
3. **Bekijk de prognose** onder **Overzicht**. Daar staan ook de verdeling van de bezetting en de opties voor extra inzet.

Klap een functie uit voor de uitleg en gebruiksstappen. Welke knoppen je ziet, hangt af van je rol.

<details>
<summary><strong>📋 Dagplanning en bezetting bekijken</strong></summary>

Open **Planning → Overzicht**. Je ziet het aantal colli, de start van het vullen, de verwachte eindtijd en eventuele waarschuwingen over de bezetting.

- **Berekening bekijken** toont hoe voorbereiding, kassa, pauzes en overig werk meetellen.
- **Aantallen per taak tonen** maakt de verdeling van de capaciteit per tijdvak zichtbaar.
- **Vrachtgegevens** bevat het aantal colli, de trolleys en de vroegste start voor de voorbereiding. De verwerkingsdatum kan afwijken van de leverdatum.

</details>

<details>
<summary><strong>👥 Rooster bekijken, aanpassen of terugzetten</strong></summary>

Open **Planning → Personeel** en controleer de diensten en pauzeminuten. Leidinggevenden en beheerders kunnen diensten toevoegen, wijzigen of verwijderen. De prognose verandert direct mee.

Bij een handmatig rooster verschijnt **Gebruik bronrooster** zodra er een geldig WatsOnline-rooster voor die dag beschikbaar is. Klik daarop om de handmatige diensten en pauzes te vervangen door het bronrooster. Dezelfde knop staat bij **Vrachtgegevens**. Een bronverversing alleen laat handmatige wijzigingen staan.

</details>

<details>
<summary><strong>⏱️ Een streeftijd zetten en extra inzet berekenen</strong></summary>

1. Vul in **Overzicht** bij **Streeftijd colli klaar** de gewenste eindtijd in. Deze tijd wordt voor de geselecteerde vrachtdag opgeslagen.
2. Als het rooster tekortschiet of de streeftijd buiten bereik ligt, open je **Extra inzet berekenen**.
3. Het venster begint bij het kleinste aantal extra medewerkers waarvoor het een passend tijdvak vindt. Verschuif de regelaar om te zien welk tijdvak en welke eindtijd bij een ander aantal horen.
4. Kies **Oproep bekijken** om de tekst te lezen, of **Kopieer oproep** om die in de groepsapp te plakken.

Bij een lege streeftijd gebruikt de berekening het einde van de laatste dienst. Ze zoekt vanaf dat doel in kwartierstappen terug en stopt zodra een tijdvak voldoet. Wil je gericht in de ochtend klaar zijn, kies dan een ochtendtijd als doel. De berekening zoekt één gezamenlijk blok van maximaal zes uur per extra medewerker en slaat het voorstel niet op in het rooster.

</details>

<details>
<summary><strong>🚚 Vrachtaankomst en bronstatus lezen</strong></summary>

Bij **Vrachtaankomst** zie je de geplande tijd, het levervenster, de ETA en de werkelijke aankomst zodra die beschikbaar zijn. Met een werkelijke aankomst én een levervenster toont de planner of de levering vóór, binnen of na het venster viel.

Onder **Vrachtgegevens** staan de bronstatussen voor Simacan, WatsInStore en WatsOnline. Bij een storing kan de planner opgeslagen waarden blijven tonen, met hun laatste succesvolle ophaaltijd. Beheerders kunnen **Bronnen verversen** of via **Beheer → Bronnen** opnieuw aanmelden als de betreffende bron dat vraagt.

</details>

<details>
<summary><strong>💬 Planning delen via WhatsApp</strong></summary>

Open **WhatsApp-bericht maken** in het overzicht. Kies **Kort** voor de belangrijkste tijden en colli, of **Uitgebreid** voor voorbereiding, start vullen en eventueel trolleywerk. Het voorbeeld werkt direct bij.

Vink **Link naar deze planning toevoegen** aan als je de filiaal- en datumlink wilt meesturen. Klik op **Kopieer bericht** en plak het in WhatsApp.

</details>

<details>
<summary><strong>✅ Vracht klaar melden en terugkijken</strong></summary>

Leidinggevenden en beheerders klikken op **Vracht klaar**, controleren de werkelijke eindtijd en kunnen het aantal gereedgemaakte trolleys invullen. Bij de registratie bewaart de server de berekende prognose, het rooster, de normen en de gebruikte brongegevens. Correcties vragen om een reden en worden aan de historie toegevoegd.

Beheerders openen **Historie & analyse** om registraties, voorspelfouten, brongegevens en normversies te bekijken. De periodefilter geldt ook voor CSV- en JSON-exports.

</details>

<details>
<summary><strong>⚙️ Rekeninstellingen, accounts en filialen beheren</strong></summary>

Onder **Beheer → Rekeninstellingen** stel je openingstijden, tempo, kassacapaciteit en **Voorbereiding en overige werkzaamheden** in. Die instellingen gelden per filiaal. Bij **Kassa opmaken** vul je klokminuten in. De planner reserveert twee medewerkers tegelijk, dus 30 minuten kost samen één persoonuur. Trek dat alleen van **Overig werk** af als het daar al in zat.

Bij **Gebruikers** beheer je accounts, rollen en actieve toegang. Platformbeheerders kunnen ook **Filialen** beheren en tussen filialen wisselen. Onder **Account** kies je lichte of donkere modus. Bij aanmelden kun je kiezen om 30 dagen aangemeld te blijven op dat apparaat.

</details>

<details>
<summary><strong>🔑 Medewerkers uitnodigen en zelf hun wachtwoord laten kiezen</strong></summary>

1. Open **Beheer → Gebruikers → Medewerker uitnodigen**. Kies een gebruikersnaam, rol en filiaal.
2. Klik op **Maak uitnodigingslink** en deel de link en de gebruikersnaam privé met de medewerker.
3. De medewerker opent de link, kiest een wachtwoord en meldt zich daarna aan. Het account wordt aangemaakt zodra het wachtwoord is opgeslagen.

Voor een bestaand actief account gebruik je **Account bewerken → Wachtwoord resetten → Maak resetlink**. Zodra de medewerker een nieuw wachtwoord opslaat, worden bestaande sessies van dat account ingetrokken. Beide links werken één keer en zijn 24 uur geldig. Maak voor dezelfde gebruiker een nieuwe link om de vorige te vervangen.

</details>

---

## Wie kan wat?

👁️ **Verkoopmedewerker** — Compact of uitgebreid alleen-lezen overzicht, afhankelijk van het account.

📋 **Leidinggevende** — Dagplanning en rooster aanpassen, planning delen en vrachtafhandeling registreren of corrigeren.

🏪 **Filiaalmanager** — Ook bronverversing en bronaanmelding, rekeninstellingen, historie en gebruikersbeheer voor het eigen filiaal.

🗂️ **Platformbeheerder** — Ook filialen aanmaken en filiaaloverstijgend beheren.

---

## Hoe rekent de planner?

<details>
<summary><strong>⏱️ Tempo, pauzes en kassa</strong></summary>

- **Vrachttempo** — Standaard 80 colli per persoonuur vóór 18:00 en 100 vanaf 18:00. Beide zijn instelbaar.
- **Pauzes en kassa** — Pauzes worden geschat binnen de dienst en vanaf 10:00. De kassa gebruikt tijdens openingstijd standaard 0,50 medewerker tot 12:00 en daarna 0,75.

</details>

<details>
<summary><strong>📦 Kassa-opmaak, voorbereiding en overig werk</strong></summary>

- **Kassa-opmaak** — Bij een ingestelde duur zoekt de planner het eerste aaneengesloten blok waarin twee medewerkers beschikbaar zijn. Met 0 minuten staat deze taak uit.
- **Binnenhalen en splitsen** — Standaard 30 minuten met twee vrije medewerkers. De planner zoekt vanaf de vroegste start een aaneengesloten blok met voldoende bezetting. Het vullen begint na dit blok zodra er vulcapaciteit beschikbaar is.
- **Overig werk** — Standaard één persoonuur, zo vroeg mogelijk ingepland. Tijdens het splitsen komt dit werk bij andere vrije medewerkers terecht. Resterend werk kan het vullen uitstellen.

</details>

<details>
<summary><strong>🛒 Trolleywerk</strong></summary>

- **Trolleywerk** — Schatting van 15 persoonsminuten per trolley. De weergegeven eindtijd geldt voor de colli.

</details>

De prognose gebruikt geplande inzet en geschatte pauzes. Werkelijk verwerkte colli, individuele werksnelheid en verschillen in vrachtmix worden niet gemeten. Bij onvoldoende bezetting toont de planner een tekort. Een eventuele uitloopprognose gaat uit van dezelfde vulbezetting na de laatste dienst.

---
