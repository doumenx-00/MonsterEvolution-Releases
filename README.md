# MonsterEvolution — Windows-testversies

Download de game via [de nieuwste release](https://github.com/doumenx-00/MonsterEvolution-Releases/releases/latest). Dit is de downloadrepository; de ontwikkelcode en spelersaves staan hier niet.

## Eerste keer spelen

1. Download het bestand met **Windows.zip** in de naam. Gebruik niet de automatisch gegenereerde Source code-bestanden van GitHub.
2. Pak de volledige ZIP uit in een gewone map.
3. Open **MonsterEvolutionLauncher.exe** en klik **Spelen**.

Godot hoef je niet te installeren. Deze versie is voor Windows 10/11 op een 64-bits pc.

## Updates

Sluit de game en klik **Updates controleren** in de launcher. Nieuwe versies worden na je bevestiging gedownload en gecontroleerd. Zonder internet kun je een ontvangen **update.zip** via **Updatebestand openen** installeren. De update-ZIP hoef je niet zelf uit te pakken.

Je save staat apart in `%APPDATA%\Godot\app_userdata\MonsterEvolution\monster_evolution_save.cfg`. De launcher raakt deze niet aan. Maak vóór grote spelupdates een back-up van je voortgang.

## Online duels vanaf 0.2.0

Jullie kunnen via een gedeelde code tegen elkaar vechten, ook vanuit twee huizen. Beide spelers hebben een opgeslagen starter/team en dezelfde actuele spelversie nodig. Kies **Online duel → Internet · duelcode** in het hoofdmenu. De host kiest **Duel hosten** en deelt de code privé. De andere speler vult die code in en kiest **Aansluiten**. Beiden klikken **Klaar voor duel**.

De verbinding loopt via een Cloudflare-relay; jullie hoeven geen IP-adressen of routerpoorten in te stellen. Ieder gebruikt zijn eigen team, maximaal zes monsters. Het duel gebruikt tijdelijke kopieën en verandert gewone HP, PP, XP of voortgang niet. Samen rondlopen is nog niet ingebouwd.

Getest met twee afzonderlijke Windows-gameprocessen via de publieke relay: 18 beurten en dezelfde eindstatus/winnaar. Jullie daadwerkelijke twee pc's en thuisnetwerken moeten nog worden uitgeprobeerd.

## Besturing en teststatus

WASD/ZQSD of pijltjes: lopen · Shift: sprinten · E: interactie · Tab: wereldkaart.

Dit blijft een testversie. Nieuwe monsteranimaties en verdere verbeteringen volgen als updates. Meld bij problemen je versienummer en wat je vlak daarvoor deed; deel geen persoonlijke saves of duelcodes openbaar.
