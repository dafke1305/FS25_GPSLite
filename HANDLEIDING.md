# GPSLite — Handleiding

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

Voor het pakket **1.3.0.2** uit [deze release](https://github.com/dafke1305/FS25_GPSLite/releases/tag/v1.3.0.2). Deze instructies horen bij die ZIP, niet bij een andere build met hetzelfde versienummer.

## Installatie

1. Download **FS25_GPSLite.zip** onder Assets van de release. Behoud de bestandsnaam en pak de ZIP niet uit. De automatische GitHub Source code-archieven zijn niet de mod.
2. Plaats de ZIP in de ingestelde FS25-modsmap (op Windows gewoonlijk `Documents\My Games\FarmingSimulator2025\mods`) en schakel de mod in vóór het laden van de savegame. Deze scriptmods zijn voor PC/Mac.
3. Server en alle multiplayerclients moeten **dezelfde ZIP** hebben, niet alleen hetzelfde versienummer. Sluit het spel/stop de server en maak vóór bijwerken een saveback-up.

## Navigatie starten

1. Open de grote kaart via **ESC** en stel een normaal FS25-kaartdoel in. Je kunt ook **Alt** ingedrukt houden en met de **rechtermuisknop** een vrije kaartpositie kiezen.
2. GPSLite berekent een route over bruikbare native wegsplines en je opgenomen routes. De grote kaart toont de resterende berekende route; de minimap toont het nabije gedeelte.
3. Sluit de kaart en volg **RECHTDOOR**, **VOLGENDE LINKS**, **VOLGENDE RECHTS** of **KEER OM** in de optionele bovenbalk. Deze versie toont daar geen afstand.
4. Verwijder het kaartdoel om de navigatie te stoppen. Een normale kaartklik wist een vrij doel of vervangt het door een native kaartdoel. Dicht bij aankomst wordt de instructie leeg; het kaartdoel wordt daardoor niet automatisch verwijderd.

GPSLite geeft aanwijzingen; het bestuurt het voertuig niet.

## Een ontbrekende weg opnemen

1. Zet routeopname aan onder **ESC > Spelinstellingen > GPSLite**, of gebruik **Ctrl+Alt+R** als de sneltoets is ingeschakeld.
2. Rijd het traject. Een sprong van meer dan **15 meter** splitst de opname, zodat geen onjuiste verbindingsweg ontstaat.
3. Stop de opname met dezelfde schakelaar of toets. Stoppen bewaart de route automatisch voor de huidige map en voegt die aan je lokale netwerk toe.
4. Gebruik **Laatste opname verwijderen** alleen na het stoppen. Nieuwe opnamen verliezen daarbij alle bijbehorende segmenten; oude bestanden zonder groepsgegevens alleen hun laatste segment.

De instellingen regelen ook GPSLite zelf, de bovenbalk, de kaartroute, de opnamesneltoets en een van acht lijnkleuren. Opnemen staat na iedere herstart **uit**. Opnamen en voorkeuren blijven lokaal bewaard; het actieve doel niet.

## Multiplayer en problemen oplossen

- Iedere speler heeft eigen doelen, opnamen, instellingen en cache. De server deelt die niet met anderen en berekent of tekent zelf geen spelersroute.
- Ontbrekende routes wijzen vaak op ontbrekende of losstaande verkeers-/AI-splines. Alleen geschilderde wegen leveren geen navigatiegegevens; neem waar nodig zelf een bruikbaar traject op.
- Kaartspecifieke eenrichtingsregels zijn niet beschikbaar via de gebruikte native spline-interface. Volg de werkelijke verkeersborden en weginrichting.
- Controleer bij ontbrekende lijnen de GPSLite-/kaartrouteschakelaars en je doel. Controleer bij een ontbrekende opnamesneltoets zowel de instelling als de toewijzing onder **Besturing**.

## Hulp vragen

Gebruik [het bug-/supportformulier van deze mod](https://github.com/dafke1305/FS25_GPSLite/issues/new/choose). Vermeld release/ZIP, FS25- en mapversie, singleplayer/host/client/dedicated, stappen, tijdstip en het volledige clientbestand `log.txt`; bij een dedicated-serverprobleem ook `server.log` van dezelfde sessie. Voeg relevante screenshots/video toe. De pakketcontrolecode staat in [PUBLICATION.json](PUBLICATION.json). Verwijder wachtwoorden, tokens en privéverbindingsgegevens vóór openbaar plaatsen. Gebruik voor privébewijs alleen een goedgekeurd privékanaal.

Standaardtoetsen zijn aanpasbaar. De actuele F1-hulp en je instellingen onder Besturing zijn leidend.
