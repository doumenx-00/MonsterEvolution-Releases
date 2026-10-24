# MonsterEvolution — Windows-testversies

**Actuele versie: 0.3.0.** [Download de Windows-ZIP](https://github.com/doumenx-00/MonsterEvolution-Releases/releases/download/v0.3.0/MonsterEvolution-0.3.0-Windows.zip) · [Release en wijzigingen](https://github.com/doumenx-00/MonsterEvolution-Releases/releases/tag/v0.3.0)

Dit is de downloadrepository; de ontwikkelcode en spelersaves staan hier niet.

## Eerste keer spelen

1. Download **MonsterEvolution-0.3.0-Windows.zip**. Gebruik niet de automatisch gegenereerde Source code-bestanden van GitHub.
2. Pak de volledige ZIP uit in een gewone map.
3. Open **MonsterEvolutionLauncher.exe** en klik **Spelen**.

Godot hoef je niet te installeren. Deze versie is voor Windows 10/11 op een 64-bits pc.

## Updates

Sluit de game en klik **Updates controleren** in de launcher. Nieuwe versies worden na je bevestiging gedownload en gecontroleerd. Zonder internet kun je een ontvangen **update.zip** via **Updatebestand openen** installeren. De update-ZIP hoef je niet zelf uit te pakken.

Je save staat apart in `%APPDATA%\Godot\app_userdata\MonsterEvolution\monster_evolution_save.cfg`. De launcher raakt deze niet aan. Maak vóór grote spelupdates een back-up van je voortgang.

## Online arena in 0.3.0

Jullie kunnen via een gedeelde code tegen elkaar vechten, ook vanuit twee huizen. **Beide spelers moeten 0.3.0 gebruiken** en een opgeslagen starter/team hebben.

1. Kies **Online duel → Internet · duelcode**.
2. Kies vooraf maximaal zes eigen monsters, ook uit opslag, en kies **1 tegen 1** of **2 tegen 2**. De eerste twee starten bij 2v2.
3. De host kiest **Duel hosten** en deelt de code privé. De andere speler vult dezelfde code in en kiest **Aansluiten**, met hetzelfde gevechtsformaat.
4. Beiden klikken **Klaar voor duel**. In 2v2 kies je voor beide actieve monsters een aanval en doelwit en klik je **Beurt versturen**.

De verbinding loopt via een Cloudflare-relay; jullie hoeven geen IP-adressen of routerpoorten in te stellen. Gevechten gebruiken tijdelijke kopieën en veranderen gewone HP/PP niet. Na een uitgespeeld duel krijgt ieder meegenomen monster eenmalig XP: **200 bij winst, 75 bij verlies, 100 bij gelijkspel**. Opgeven of een verbroken duel geeft geen XP. Samen rondlopen is nog niet ingebouwd.

Getest met twee afzonderlijke Windows-gameprocessen via de publieke relay: een volledige 2v2 van elf beurten met dezelfde eindstatus en winnaar. Jullie daadwerkelijke twee pc's en thuisnetwerken moeten nog worden uitgeprobeerd.

## Verder nieuw

- 300 Engelse aanvallen met leerlijsten en maximaal vier actieve aanvallen.
- 60 effecten voor supersterke en ultra-aanvallen, met opbouw, mondankers en groeiende wortels.
- Zes geschilderde battleachtergronden die de locatie volgen; online duels gebruiken de arena.
- Mythisch-type en ultrabeesten. Bestaande voortgang blijft behouden.

De effecten delen type-illustraties en bewegingspatronen; het zijn geen zestig afzonderlijk getekende spriteanimaties. Verdere monsteranimaties volgen later.

## Besturing en teststatus

WASD/ZQSD of pijltjes: lopen · Shift: sprinten · E: interactie · Tab: wereldkaart.

Dit blijft een testversie. Meld bij problemen je versienummer en wat je vlak daarvoor deed; deel geen persoonlijke saves of duelcodes openbaar.
