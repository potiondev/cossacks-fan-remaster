# Cossacks: Back to War – Fan Remaster

A free fan remaster of GSC Game World's **Cossacks: Back to War** (2002) for
Windows. It installs over your own GOG or Steam copy of the game.

**[Download the setup](https://github.com/potiondev/cossacks-fan-remaster/releases/latest/download/Cossacks-Fan-Remaster-Setup.exe)**
· [All releases](https://github.com/potiondev/cossacks-fan-remaster/releases)
· [Support the project](#supporting-the-project)
· [Magyarul](#magyarul) · [По-русски](#по-русски)

> **The original game, not a remake.** The Fan Remaster is not a
> reimplementation like the new wave of games. It is made from this: https://github.com/ereb-thanatos/cossacks-revamp-2017. So huge thanks to him!!!

## Contents

- [What's new, in short](#whats-new-in-short)
- [What you need](#what-you-need)
- [Installing](#installing)
- [Updates](#updates)
- [Playing together](#playing-together)
- [Privacy](#privacy)
- [Something went wrong?](#something-went-wrong)
- [Supporting the project](#supporting-the-project)
- [What changed compared to the original](#what-changed-compared-to-the-original)
- [Uninstalling](#uninstalling)
- [Credits](#credits)

## What's new, in short

- **Up to 16 players** in skirmish and multiplayer, on maps up to giant size.
- **New computer opponents**, from Easy to Brutal. The levels differ in how
  well they play, not in how fast they build. The four 2002 levels are still
  there.
- **A map generator that shows the map before you play**, with land shapes,
  islands, peninsulas, water, stone, riches, snow, desert and more.
- **Deep snow** (beta) that units wade through and slow down in, leaving
  tracks behind them.
- **Zoom** from close up out to the whole map, drawn by the graphics card.
- **Battles of up to 1,000,000 units:** the simulation uses every processor
  core.
- **Smooth movement** and turning at any frame rate, and VSync.
- **A modern interface** that scales up to 4K.
- **Online play:** a list of open games, Quick and ranked 1v1 with a
  leaderboard, invite links, rejoining after a crash, and saved multiplayer
  games. Online games go through a relay, so players never see each other's
  IP address (except in private games).
- **Twelve languages:** English, Czech, German, Spanish, French, Hungarian,
  Italian, Polish, Brazilian Portuguese, Russian, Turkish and Ukrainian.
- **Period paintings** of real places in the menus and on the loading
  screens.
- **Battlefield effects** to try (beta): smoke, dust, weather, cloud shadows,
  wakes and swaying grass.
- **Report a bug** from inside the game with a screenshot.
- **Automatic updates**, and you can roll back to any previous version.

## What you need

- Windows 10 or 11, and a screen of at least 1280x720.
- A graphics card with Direct3D 11.
- **Cossacks: Back to War** from [GOG](https://www.gog.com/) or
  [Steam](https://store.steampowered.com/).
- About 1.5 GB of free disk space, and about 320 MB more for each
  language other than English, and an internet connection while
  installing.

## Installing

1. Install Cossacks: Back to War from GOG or Steam, if you haven't yet.
2. Download **Cossacks-Fan-Remaster-Setup.exe** (link at the top).
3. Run it. Windows may say *"Windows protected your PC"*, because the setup is
   not code-signed. Click **More info**, then **Run anyway**.
4. Choose the setup's language, and on the *Game languages* page the
   languages you want to play in.
5. The setup finds your GOG or Steam copy by itself. If it can't, point it at
   the game's folder. It checks that the copy is the one it knows, then copies
   the game data it needs. It only reads your copy: the GOG or Steam game
   stays as it is and still plays as before.
6. It downloads the rest, about 535 MB. Each language other than English
   adds about 316 MB, mostly its own loading screens.
7. Play from the Start menu or the desktop shortcut. The first time, the game
   asks for your name.

Everything goes into your own user folder
(`%LOCALAPPDATA%\Programs\Cossacks Fan Remaster` unless you choose another),
so nothing asks for administrator rights.

## Updates

When a new version is out, the game says so on the main menu and shows what
changed:
- **Update now** closes the game, updates it and starts it again.
- **Later** asks again next time.
- **Skip this version** stops asking until the next one.

The **Updates** button at the top right of the main menu lists every release
with its notes. From there you can update, or go back to an older version and
forward again. Running the setup again also updates and repairs the game. If
you don't want the game to check, untick "Check for updates when the game
starts" in the setup.

## Playing together

**Multiplayer** has three pages:
- **Public:** every open game in one list. Join with one click, host a game
  with an optional password, play Quick 1v1 or ranked 1v1, or send an invite
  link to a friend. No port forwarding and no extra software are needed.
- **Private:** a game over Direct IP, with a password. It connects the
  players directly, so they can see each other's IP addresses.
- **Legacy:** the original LAN and Direct TCP/IP games and Historical Battle.

Everyone needs the **same version**. Yours is shown on the main menu. In the
lobby, a player on another version has it shown next to their name, and the
game can't start until they update.

## Privacy

- Before your first online game, the game asks you to accept a short notice
  of what online play sends. Single player needs nothing.
- **Play statistics** are sent only if you say yes when the game asks. You
  can change your answer, download your data or delete all of it from the
  Options page.
- What is stored, why and for how long is on the
  [privacy page](https://cossacks-lobby.potiondev.workers.dev/privacy).

## Something went wrong?

- **In the game:** use **Report a bug** in the main menu's top bar or in the
  in-game menu. Write what happened; a screenshot is added if you want it.
  After a crash, the game offers to report it the next time it starts.
- **On GitHub:**
  [open an issue](https://github.com/potiondev/cossacks-fan-remaster/issues)
  and attach the file that goes with it, from the game folder:
  `Remaster\update.log` if the setup or an update failed, or `crash.log` if
  the game crashed.

## Supporting the project

The Fan Remaster is free and always will be. If you enjoy it, you can leave a
tip on **[Buy Me a Coffee](https://buymeacoffee.com/potion26)**. The
**DONATE** button on the main menu goes to the same page.

---

## What changed compared to the original

The starting point is Cossacks: Back to War 1.35 (2002), as reworked in 2017
by Ereb into
[version 1.42](https://github.com/ereb-thanatos/cossacks-revamp-2017). That
version fixed the game for modern Windows: its speed on modern processors,
the colour palette, crashes with many units or long walls, windowed modes and
an interface size setting. Everything below was built on top of that code.
It is not a list of every change, but of what was done to each part of the
game.

### The engine stays the engine

- The game is still the 2002 C++ engine: about 270 source files, 32-bit, built
  with a current Microsoft compiler. No part of it was replaced by a
  re-creation.
- **The computer players' libraries.** The twenty per-nation AI libraries
  shipped with the game only as compiled 2002 binaries. They were decompiled
  back into C++ and are now built from that source. They were checked against
  the originals by logging every engine call each one makes and comparing:
  the same calls at load, and the same calls when one recorded game is
  replayed with each.
- **Multiplayer is still lockstep.** Every player's computer runs the same
  simulation from the same commands, as in 2002. Every change that touches
  the simulation keeps it exactly deterministic: the same random numbers
  drawn in the same order, and the same integer edge cases. A build number in
  the lobby keeps different versions apart.

### Graphics

- **The GPU renderer.** The 2002 game draws every pixel on the processor into
  an 8-bit, 256-colour picture, and the graphics card only shows the result.
  The Fan Remaster moved that drawing to the graphics card through Direct3D
  11, in stages, inside the same 32-bit program: the sprites, the terrain (now
  a mesh), the sea and the fog of war. The original colour tables for
  shadows, see-through effects and team colours are applied on the graphics
  card too, so the game looks as it did.
- **Zoom** from close up out to the whole map, even a giant one. Nothing is
  thinned out or hidden to save time at any zoom: far away, units are drawn
  more simply, but they are always drawn.
- **Smooth movement.** The simulation advances 40 steps a second, as before.
  Units are now drawn in between the steps, and they turn smoothly, so
  movement is smooth at any frame rate. The camera glides, and a VSync option
  was added.
- **The sea** washes up the shore and back, and looks smooth up close.
- **Resolutions up to 4K and beyond**, with the interface scaled to match and
  sharp text at every size.
- **Battlefield effects** (beta, off unless you turn them on), twelve of them,
  each with its own switch: cloud shadows, musket and cannon smoke, burning
  buildings, dust, ship wakes and splashes, rain, snow and mist, the fog of
  war as drifting mist, worn paths and craters, soft shadows under units,
  screen shake, swaying grass, and F10 to hide the interface. They are only
  pictures and never touch the simulation.
- **Zoom-out markers:** far out, each unit and building is marked in its
  owner's colour.
- **Frame rate and ping** can be shown in a corner (Options).

### Simulation and performance

- **Every processor core.** Target searching, orders, movement, the map's
  cell tables, the fog, the minimap and the sorting of sprites for drawing
  now run on all cores. Their results are applied in the original order, so
  every player's game still computes the same battle.
- **Bigger battles, up to a million units.** The limit on objects in a game
  rose from 65,535 to 1,048,576. A 200,000-unit battle with the whole battle in view went from
  about 15 frames a second to about 240 (1080p, on an 8-core processor),
  with the simulation holding its 40 steps a second.
- **Faster searches.** Path finding plays about 1.7 times as many games an
  hour with identical results, and the search for the nearest storehouse is
  faster too.
- **Bugs that only showed at scale** were fixed. One example: a nation's food
  counter overflowed past about 21,800 eaters.

### Sixteen players

- The 2002 engine had eight nation slots: seven players and the neutral
  nation. It now has seventeen: sixteen players and the neutral nation.
- That meant widening the alliance masks from 8 to 32 bits (every
  friend-or-foe test is one), the per-cell tables of which nations are
  present, and the per-unit selection fields. It also meant rebuilding the
  start-game message and the lobby, and adding sixteen player colours.
- Maps made for the original game, and the map editor's files, still load as
  they did.

### Computer players

- **What a difficulty level was.** In 2002 the four levels differed in one
  thing only: how long the computer took to produce. They used the same
  build order, the same armies, the same aggression and the same mistakes.
- **A commander.** A new strategic layer in the engine makes the decisions a
  player makes: when and where to attack, when to fall back, what to defend
  and how to answer what it sees. It sits on top of the nation libraries,
  which still know each nation's units.
- **Difficulty means skill.** Every new level produces at the player's own
  rate. What separates Easy, Normal, Hard, Very hard and Brutal is which
  decisions they may use and how often they look at the board. The four
  original 2002 levels are still in the list.
- **Measured.** Changes to the computer players are kept only if they win
  more. That is measured over many full-length games that run unattended,
  several at once, with every pairing played from both seats.

### Maps

- **The random map generator** now draws the map on the skirmish page before
  the game starts. The preview and the real map come from the same plan, so
  what you see is what you play. It has land shapes (islands, peninsulas, and
  extreme shapes), one versus all, sliders for water, stone, ruggedness,
  woodland and riches, the ground (snow, desert, shallows), start positions
  you can drag, hidden maps and a full-random option. Maps go up to giant
  size, 3,840 tiles across.
- **Deep snow** (beta) is part of the simulation, so it is the same for every player
  and is kept in saved games. Units sink in and slow down. Their tracks are
  worn down gradually, and only fill in again while snow falls.
- **The map editor** zooms with the mouse wheel and uses the modern look.

### Multiplayer and online play

- **The lobby is the skirmish page with a chat.** The host's map settings go
  to every player, and each player's game builds the same map from them.
- **Public** is backed by a small lobby server. It holds the list of games,
  passwords, Quick 1v1 and ranked 1v1 matchmaking with ratings and a
  leaderboard (ranked games are on mirrored maps with fixed settings), and
  invite links. The game itself still runs between the players' computers,
  through a relay that hides their IP addresses. If the relay's monthly
  allowance runs out, games connect directly instead, and the game says so
  before you join. Private games always connect directly.
- **Rejoining.** A player whose game crashed, or who left, can come back: the
  game starts again from where it stopped with everyone who returned.
- **Saved multiplayer games** can be carried on later. The host sends the
  save and the map to everyone.
- **Accounts need no sign-up.** You can add an email to log in on a new
  computer with a code sent to you. There are no passwords.
- The original networking core is kept, and was hardened after a security
  review.

### Interface

- **A modern look** that the game draws itself at any size: menus, buttons,
  the top bar, the in-game menu and the panels.
- **Redesigned menus**, laid out around their content, over period paintings
  of real places for each nation.
- **New pages:** statistics after a game, My games (your game history), the
  version list, Report a bug, Donate and Privacy. The Options pages were
  rearranged into two columns.
- **Smaller things:** a top-bar counter of mines that aren't full (click it to
  go to the next one), a damage bar, a rally-point cursor, and a formation
  arrow that follows the zoom.

### Languages

- Eleven languages besides English. Each is a pack of text files, its own
  fonts and its own loading screens, and each is an optional download.
- The 2002 bitmap fonts were extended with each language's accented letters
  and with Cyrillic.

### Installing and updating

- **None of GSC's data is in the download** except 26 entries of the game's
  archive that the remaster changes. The setup finds your GOG copy from the
  registry or your Steam copy from Steam's libraries. It checks the game's
  main archive byte for byte, then copies the 1,781 files it needs, checking
  each one.
- **The updater** downloads packs and checks each one's SHA-256 hash before
  anything is replaced. A pack that didn't change is never downloaded again.
  If anything fails, the files are swapped back, so a failed update leaves
  the old version working. Running it again repairs missing files, and it
  updates itself.
- **The soundtrack** plays from your own copy: through GOG's CD stand-in, or
  Steam's equivalent.

### A few of the fixes to the 2002 game

- Units step off the site of a new building instead of blocking it.
- Units react sooner to enemies right next to them.
- Cannon shells fly the course they were aimed on.
- Priests no longer heal units that have become enemies.
- Orders to a huge selection no longer leave part of it standing idle.
- A random map no longer goes out of sync when a player has the same map from
  an earlier game.
- The game speed setting no longer changes the outcome of a game.
- A crash when computer players looked for targets for their warships.
- The chat word filter is removed.

---

## Uninstalling

Go to Windows **Settings → Apps → "Cossacks: Back to War - Fan Remaster"**. It
asks whether to keep your saved games and settings.

## Credits

See [CREDITS.md](CREDITS.md) for the pictures, the map data and the fonts.

- **Cossacks: Back to War** (2002) by **GSC Game World**.
- Built on the game's source code as reworked in 2017 by **Ereb**
  ([cossacks-revamp-2017](https://github.com/ereb-thanatos/cossacks-revamp-2017)).

This is a fan project. It is not made, endorsed or supported by GSC Game World,
GOG or Valve. You need your own copy of Cossacks: Back to War: the download
does not contain the game, and the setup copies what it needs from your copy.

---

## Magyarul

A GSC Game World **Cossacks: Back to War** (2002) című játékának ingyenes
rajongói felújítása Windowsra. A játék saját GOG-os vagy Steames
példányodra települ.

**[A telepítő letöltése](https://github.com/potiondev/cossacks-fan-remaster/releases/latest/download/Cossacks-Fan-Remaster-Setup.exe)**
· [Összes kiadás](https://github.com/potiondev/cossacks-fan-remaster/releases)
· [A projekt támogatása](#a-projekt-támogatása)

> **Az eredeti játék, nem remake.** A Fan Remaster nem újraírás, mint az új
> hullám játékai. Ebből készült: https://github.com/ereb-thanatos/cossacks-revamp-2017.
> Hatalmas köszönet neki!!!

### Tartalom

- [Röviden az újdonságokról](#röviden-az-újdonságokról)
- [Ami kell](#ami-kell)
- [Telepítés](#telepítés)
- [Frissítések](#frissítések)
- [Közös játék](#közös-játék)
- [Adatvédelem](#adatvédelem)
- [Valami nem működik?](#valami-nem-működik)
- [A projekt támogatása](#a-projekt-támogatása)
- [Mi változott az eredetihez képest](#mi-változott-az-eredetihez-képest)
- [Eltávolítás](#eltávolítás)
- [Köszönet](#köszönet)

### Röviden az újdonságokról

- **Legfeljebb 16 játékos** skirmish és többjátékos módban, akár óriás
  térképeken.
- **Új gépi ellenfelek** a Könnyűtől a Brutálisig. A szintek abban
  különböznek, hogy mennyire jól játszanak, nem abban, hogy milyen gyorsan
  építenek. A 2002-es négy szint is megmaradt.
- **Térképgenerátor, amely játék előtt megmutatja a térképet**:
  szárazföldformák, szigetek, félszigetek, víz, kő, kincsek, hó, sivatag és
  még sok más.
- **Mély hó** (béta), amelyben az egységek gázolnak és lelassulnak, és
  nyomot hagynak maguk után.
- **Nagyítás** közelről egészen az egész térképig, a videókártya rajzolja.
- **Akár 1 000 000 egységes csaták:** a szimuláció minden processzormagot
  használ.
- **Sima mozgás** és fordulás bármilyen képkockasebességnél, és VSync.
- **Modern felület**, amely 4K-ig méreteződik.
- **Online játék:** a nyitott játékok listája, Gyors és Értékelt 1v1
  ranglistával, meghívó linkek, visszatérés összeomlás után, és mentett
  többjátékos játékok. Az online játékok egy relén át mennek, így a
  játékosok nem látják egymás IP-címét (kivéve a privát játékokban).
- **Tizenkét nyelv:** angol, cseh, német, spanyol, francia, magyar, olasz,
  lengyel, brazil portugál, orosz, török és ukrán.
- **Korabeli festmények** valódi helyekről a menükben és a
  töltőképernyőkön.
- **Kipróbálható csatatéri effektek** (béta): füst, por, időjárás,
  felhőárnyékok, hajók nyomvonala és hajladozó fű.
- **Hibajelentés** a játékból képernyőképpel.
- **Automatikus frissítések**, és bármelyik korábbi verzióra
  visszaléphetsz.

### Ami kell

- Windows 10 vagy 11, és legalább 1280x720-as képernyő.
- Direct3D 11-et támogató videókártya.
- A **Cossacks: Back to War** a [GOG](https://www.gog.com/)-ról vagy a
  [Steam](https://store.steampowered.com/)-ről.
- Kb. 1,5 GB szabad hely, és minden angolon kívüli nyelvhez további kb.
  320 MB, valamint internetkapcsolat a telepítés alatt.

### Telepítés

1. Telepítsd a Cossacks: Back to War játékot a GOG-ról vagy a Steamről, ha
   még nincs meg.
2. Töltsd le a **Cossacks-Fan-Remaster-Setup.exe**-t (fent a link).
3. Futtasd. A Windows kiírhatja, hogy *„A Windows megvédte a
   számítógépet”*, mert a telepítő nincs digitálisan aláírva. Kattints a
   **További információ**, majd a **Futtatás mindenképp** gombra.
4. Válaszd ki a telepítő nyelvét, a játék nyelveinél pedig azokat a
   nyelveket, amelyeken játszani szeretnél.
5. A telepítő magától megtalálja a GOG-os vagy Steames példányodat. Ha nem,
   mutasd meg neki a játék mappáját. Ellenőrzi, hogy általa ismert
   példányról van-e szó, majd átmásolja a szükséges játékadatokat. A
   példányodat csak olvassa: a GOG-os vagy Steames játék változatlan marad,
   és ugyanúgy játszható, mint eddig.
6. A többit letölti, kb. 535 MB-ot. Minden angolon kívüli nyelv kb.
   316 MB-tal több, főleg a saját töltőképernyői miatt.
7. Indítsd a Start menüből vagy az asztali parancsikonról. Első indításkor
   a játék megkérdezi a neved.

Minden a saját felhasználói mappádba kerül
(`%LOCALAPPDATA%\Programs\Cossacks Fan Remaster`, hacsak nem választasz
másikat), így semmi sem kér rendszergazdai jogot.

### Frissítések

Ha új verzió jelenik meg, a játék a főmenüben szól, és megmutatja, mi
változott:
- **Frissítés most:** bezárja a játékot, frissíti és újraindítja.
- **Később:** legközelebb újra rákérdez.
- **Ezt kihagyom:** a következő verzióig nem kérdez.

A főmenü jobb felső sarkában lévő frissítések gomb felsorol minden kiadást
a leírásával. Innen frissíthetsz, vagy visszaléphetsz egy régebbi
verzióra, majd újra előre. A telepítő újbóli futtatása is frissíti és
javítja a játékot. Ha nem szeretnéd, hogy a játék frissítést keressen, a
telepítőben kapcsold ki a frissítések keresését a játék indításakor.

### Közös játék

A **Többjátékos** mód három oldalból áll:
- **Nyilvános:** minden nyitott játék egy listában. Csatlakozás egy
  kattintással, saját játék indítása jelszóval vagy anélkül, Gyors 1v1 vagy
  Értékelt 1v1, vagy meghívó link küldése egy barátnak. Nem kell
  porttovábbítás, és más program sem.
- **Privát:** játék közvetlen IP-n, jelszóval. A játékosok közvetlenül
  kapcsolódnak, így látják egymás IP-címét.
- **Hagyományos:** az eredeti LAN- és Direct TCP/IP-játékok és a
  Történelmi csata.

Mindenkinek **ugyanaz a verzió** kell. A sajátod a főmenüben látható. A
lobbiban a más verziót használó játékos neve mellett ott a verziója, és a
játék addig nem indulhat, amíg nem frissít.

### Adatvédelem

- Az első online játék előtt a játék megkéri, hogy fogadj el egy rövid
  tájékoztatót arról, mit küld az online játék. Az egyjátékos módhoz semmi
  sem kell.
- **Játékstatisztikát** csak akkor küld, ha igent mondasz, amikor a játék
  megkérdezi. A válaszodat megváltoztathatod, az adataidat letöltheted vagy
  mind törölheted a Beállítások oldalon.
- Hogy mit tárol, miért és meddig, az az
  [adatvédelmi oldalon](https://cossacks-lobby.potiondev.workers.dev/privacy)
  olvasható (angolul).

### Valami nem működik?

- **A játékban:** használd a **Hibajelentést** a főmenü felső sávjában vagy
  a játék menüjében. Írd le, mi történt; ha szeretnéd, képernyőkép is megy
  vele. Összeomlás után a játék a következő indításkor felajánlja, hogy
  jelentsd.
- **A GitHubon:**
  [nyiss egy issue-t](https://github.com/potiondev/cossacks-fan-remaster/issues),
  és csatold hozzá a megfelelő fájlt a játék mappájából:
  `Remaster\update.log`, ha a telepítés vagy egy frissítés nem sikerült,
  vagy `crash.log`, ha a játék összeomlott.

### A projekt támogatása

A Fan Remaster ingyenes, és az is marad. Ha tetszik, borravalót hagyhatsz a
**[Buy Me a Coffee](https://buymeacoffee.com/potion26)** oldalon. A főmenü
**DONATE** gombja ugyanide visz.

### Mi változott az eredetihez képest

A kiindulópont a Cossacks: Back to War 1.35 (2002), ahogy 2017-ben Ereb
átdolgozta
[1.42-es verzióvá](https://github.com/ereb-thanatos/cossacks-revamp-2017).
Az a verzió hozzáigazította a játékot a modern Windowshoz: a sebességét a
mai processzorokon, a színpalettát, az összeomlásokat sok egységnél vagy
hosszú falaknál, az ablakos módokat és a felületméret beállítását. Minden,
ami alább következik, erre a kódra épült. Ez nem minden változás listája,
hanem annak összefoglalása, mi történt a játék egyes részeivel.

#### A motor ugyanaz a motor

- A játék továbbra is a 2002-es C++ motor: kb. 270 forrásfájl, 32 bites,
  mai Microsoft-fordítóval fordítva. Egyetlen részét sem írták újra.
- **A gépi játékosok könyvtárai.** A húsz nemzetenkénti AI-könyvtár a
  játékkal csak lefordított 2002-es binárisként érkezett. Ezeket
  visszafejtették C++-ra, és most ebből a forrásból készülnek. Az
  eredetiekkel úgy vetették össze őket, hogy naplózták és összehasonlították
  mindegyik minden motorhívását: ugyanazok a hívások betöltéskor, és
  ugyanazok, amikor egy felvett játékot mindegyikkel visszajátszanak.
- **A többjátékos mód továbbra is lockstep.** Minden játékos gépe
  ugyanazt a szimulációt futtatja ugyanazokból a parancsokból, mint
  2002-ben. Minden változtatás, amely a szimulációt érinti, pontosan
  determinisztikus marad: ugyanazok a véletlenszámok ugyanabban a
  sorrendben, és ugyanazok az egész számos határesetek. A lobbiban egy
  buildszám tartja külön a különböző verziókat.

#### Grafika

- **A GPU-s megjelenítő.** A 2002-es játék minden képpontot a processzoron
  rajzol egy 8 bites, 256 színű képbe, a videókártya csak megjeleníti az
  eredményt. A Fan Remaster ezt a rajzolást lépésenként a videókártyára
  vitte Direct3D 11-en keresztül, ugyanabban a 32 bites programban: a
  sprite-okat, a terepet (ma már hálóként), a tengert és a háború ködét. Az
  eredeti színtáblák az árnyékokhoz, az áttetszőséghez és a csapatszínekhez
  szintén a videókártyán érvényesülnek, így a játék úgy néz ki, mint régen.
- **Nagyítás** közelről egészen az egész térképig, akár óriás térképen is.
  Egyik nagyításnál sem ritkít vagy rejt el semmit, hogy időt spóroljon:
  messziről az egységek egyszerűbben látszanak, de mindig látszanak.
- **Sima mozgás.** A szimuláció másodpercenként 40 lépést tesz, mint régen.
  Az egységek most a lépések között is kirajzolódnak, és simán fordulnak,
  így a mozgás bármilyen képkockasebességnél sima. A kamera siklik, és van
  VSync beállítás.
- **A tenger** kicsap a partra és visszahúzódik, közelről pedig simának
  látszik.
- **Felbontások 4K-ig és tovább**, a felület ehhez méreteződik, a szöveg
  minden méretben éles.
- **Csatatéri effektek** (béta, csak ha bekapcsolod), tizenkettő, mindegyik
  külön kapcsolóval: felhőárnyékok, muskéta- és ágyúfüst, égő épületek,
  por, hajók nyomvonala és fröccsenések, eső, hó és pára, a háború köde
  gomolygó ködként, kitaposott utak és kráterek, lágy árnyék az egységek
  alatt, képernyőrázkódás, hajladozó fű, és F10 a felület elrejtéséhez.
  Ezek csak képek, a szimulációhoz soha nem nyúlnak.
- **Jelölők távolról:** messziről minden egység és épület a tulajdonosa
  színével van megjelölve.
- **Képkockasebesség és ping** kijelezhető egy sarokban (Beállítások).

#### Szimuláció és teljesítmény

- **Minden processzormag.** A célkeresés, a parancsok, a mozgás, a térkép
  cellatáblái, a köd, a minitérkép és a sprite-ok rajzolási sorrendbe
  rendezése most minden magon fut. Az eredmények az eredeti sorrendben
  érvényesülnek, így minden játékos gépe továbbra is ugyanazt a csatát
  számolja.
- **Nagyobb csaták, akár egymillió egységig.** Az objektumok korlátja egy
  játékban 65 535-ről 1 048 576-ra nőtt. Egy 200 000 egységes csata,
  egészében látva, kb. 15 képkocka/másodpercről kb. 240-re gyorsult (1080p,
  8 magos processzoron), miközben a szimuláció tartja a másodpercenkénti
  40 lépést.
- **Gyorsabb keresés.** Az útkereséssel kb. 1,7-szer annyi játék fut le
  óránként, azonos eredménnyel, és a legközelebbi raktár keresése is
  gyorsabb.
- **A csak nagy léptékben előjövő hibák** javítva. Egy példa: egy nemzet
  élelemszámlálója kb. 21 800 evő felett túlcsordult.

#### Tizenhat játékos

- A 2002-es motorban nyolc nemzethely volt: hét játékos és a semleges
  nemzet. Most tizenhét van: tizenhat játékos és a semleges nemzet.
- Ehhez 8-ról 32 bitre kellett szélesíteni a szövetségi maszkokat (minden
  barát-vagy-ellenség vizsgálat ilyen), a cellánkénti táblákat arról, mely
  nemzetek vannak jelen, és az egységenkénti kijelölési mezőket. Újra
  kellett építeni a játékindító üzenetet és a lobbit is, és tizenhat
  játékosszín kellett.
- Az eredeti játékhoz készült térképek és a térképszerkesztő fájljai
  ugyanúgy betöltődnek, mint eddig.

#### Gépi játékosok

- **Mi volt a nehézségi szint.** 2002-ben a négy szint egyetlen dologban
  különbözött: mennyi ideig termelt a gép. Ugyanaz az építési sorrend,
  ugyanazok a seregek, ugyanaz az agresszió és ugyanazok a hibák.
- **Egy parancsnok.** A motor egy új stratégiai rétege hozza meg azokat a
  döntéseket, amelyeket egy játékos: mikor és hol támadjon, mikor vonuljon
  vissza, mit védjen, és hogyan válaszoljon arra, amit lát. A nemzetek
  könyvtárai fölött működik, azok továbbra is ismerik az egyes nemzetek
  egységeit.
- **A nehézség tudást jelent.** Minden új szint ugyanolyan ütemben termel,
  mint a játékos. A Könnyű, Normál, Nehéz, Nagyon nehéz és Brutális szintet
  az választja el, hogy mely döntéseket használhatják, és milyen gyakran
  néznek rá a táblára. Az eredeti négy 2002-es szint is megmaradt a
  listában.
- **Mérve.** A gépi játékosokon csak az a változtatás marad meg, amelytől
  többet nyernek. Ezt sok, teljes hosszúságú, felügyelet nélkül futó
  játékon mérik, egyszerre többön, minden párosítást mindkét oldalról
  lejátszva.

#### Térképek

- **A véletlen térképgenerátor** most már a játék indulása előtt kirajzolja
  a térképet a skirmish oldalon. Az előnézet és a valódi térkép ugyanabból
  a tervből készül, így azon játszol, amit látsz. Vannak szárazföldformák
  (szigetek, félszigetek és extrém formák), egy mindenki ellen mód,
  csúszkák a vízhez, a kőhöz, a tagoltsághoz, az erdőhöz és a kincsekhez,
  talajtípus (hó, sivatag, sekély víz), húzható kezdőpozíciók, rejtett
  térképek és teljesen véletlen lehetőség. A térképek óriás méretig, 3840
  mező szélességig mennek.
- **A mély hó** (béta) a szimuláció része, ezért minden játékosnál
  ugyanaz, és a mentésekbe is bekerül. Az egységek belesüppednek és
  lelassulnak. A nyomaik fokozatosan taposódnak ki, és csak havazás közben
  telnek be újra.
- **A térképszerkesztő** egérgörgővel nagyít, és a modern kinézetet
  használja.

#### Többjátékos és online játék

- **A lobbi a skirmish oldal csevegéssel.** A házigazda térképbeállításai
  minden játékoshoz eljutnak, és mindenki gépe ugyanazt a térképet építi
  fel belőlük.
- **A Nyilvános** módot egy kis lobbiszerver szolgálja ki. Ez tárolja a
  játékok listáját, a jelszavakat, a Gyors 1v1 és az Értékelt 1v1
  párosítását értékszámokkal és ranglistával (az értékelt játékok
  tükrözött térképeken, rögzített beállításokkal mennek), és a meghívó
  linkeket. Maga a játék továbbra is a játékosok gépei között fut, egy
  relén át, amely elrejti az IP-címeiket. Ha a relé havi kerete elfogy, a
  játékok közvetlenül kapcsolódnak, és a játék ezt csatlakozás előtt
  jelzi. A privát játékok mindig közvetlenül kapcsolódnak.
- **Visszatérés.** Az a játékos, akinek a játéka összeomlott, vagy aki
  kilépett, visszatérhet: a játék onnan indul újra, ahol megállt,
  mindenkivel, aki visszajött.
- **A mentett többjátékos játékok** később folytathatók. A házigazda
  mindenkinek elküldi a mentést és a térképet.
- **A fiókhoz nem kell regisztráció.** Megadhatsz egy e-mail-címet, hogy új
  gépen egy neked küldött kóddal lépj be. Jelszó nincs.
- Az eredeti hálózati mag megmaradt, és egy biztonsági átvizsgálás után
  megerősítették.

#### Felület

- **Modern kinézet**, amelyet a játék maga rajzol bármilyen méretben:
  menük, gombok, a felső sáv, a játékbeli menü és a panelek.
- **Újratervezett menük**, a tartalmuk köré rendezve, minden nemzethez
  valódi helyeket ábrázoló korabeli festményekkel.
- **Új oldalak:** statisztika egy játék után, Játékaim (a
  játékelőzményeid), a verziólista, Hibajelentés, Támogatás és
  Adatvédelem. A Beállítások oldalai két oszlopba rendeződtek.
- **Apróságok:** a felső sávban számláló a nem teli bányákról (kattintásra
  a következőhöz ugrik), sebzéssáv, gyülekezőpont-kurzor, és alakzatnyíl,
  amely követi a nagyítást.

#### Nyelvek

- Tizenegy nyelv az angolon kívül. Mindegyik szövegfájlok csomagja saját
  betűkészletekkel és saját töltőképernyőkkel, és mindegyik választható
  letöltés.
- A 2002-es bitképes betűkészleteket kiegészítették minden nyelv ékezetes
  betűivel és a cirill írással.

#### Telepítés és frissítés

- **A GSC adataiból semmi sincs a letöltésben**, kivéve a játék
  archívumának 26 bejegyzését, amelyet a felújítás megváltoztat. A telepítő
  a GOG-os példányt a rendszerleíró adatbázisból, a Steamest a Steam
  könyvtáraiból találja meg. Bájtról bájtra ellenőrzi a játék fő
  archívumát, majd átmásolja a szükséges 1781 fájlt, mindegyiket
  ellenőrizve.
- **A frissítő** csomagokat tölt le, és mindegyik SHA-256 ellenőrzőösszegét
  megvizsgálja, mielőtt bármit lecserélne. A változatlan csomagot soha nem
  tölti le újra. Ha bármi elromlik, visszacseréli a fájlokat, így egy
  sikertelen frissítés után is működik a régi verzió. Újra futtatva pótolja
  a hiányzó fájlokat, és önmagát is frissíti.
- **A zene** a saját példányodból szól: a GOG CD-helyettesítőjén vagy a
  Steam megfelelőjén keresztül.

#### Néhány javítás a 2002-es játékban

- Az egységek lelépnek egy új épület helyéről, ahelyett hogy elállnák.
- Az egységek hamarabb reagálnak a közvetlenül mellettük álló ellenségre.
- Az ágyúgolyók azon a pályán repülnek, amelyre célozták őket.
- A papok már nem gyógyítják az ellenséggé vált egységeket.
- Egy hatalmas kijelölésnek adott parancs már nem hagyja tétlenül a sereg
  egy részét.
- A véletlen térkép már nem csúszik szét, ha egy játékosnak ugyanez a
  térkép egy korábbi játékból megvan.
- A játéksebesség beállítása már nem változtatja meg egy játék
  kimenetelét.
- Javítva egy összeomlás, amikor a gépi játékosok célpontot kerestek a
  hadihajóiknak.
- A csevegés szószűrője eltávolítva.

### Eltávolítás

Windowsban: **Gépház → Alkalmazások → „Cossacks: Back to War - Fan
Remaster”**. Megkérdezi, megtartsa-e a mentett játékaidat és
beállításaidat.

### Köszönet

A képek, a térképadatok és a betűkészletek forrásai a
[CREDITS.md](CREDITS.md) fájlban vannak.

- **Cossacks: Back to War** (2002): **GSC Game World**.
- A játék forráskódjára épül, ahogy 2017-ben **Ereb** átdolgozta
  ([cossacks-revamp-2017](https://github.com/ereb-thanatos/cossacks-revamp-2017)).

Ez rajongói projekt. Nem a GSC Game World, a GOG vagy a Valve készítette,
hagyta jóvá vagy támogatja. Saját Cossacks: Back to War példány kell hozzá:
a letöltés nem tartalmazza a játékot, a telepítő a te példányodból másolja
át, amire szüksége van.

---

## По-русски

Бесплатный фанатский ремастер игры **Cossacks: Back to War** (2002) от GSC
Game World для Windows. Он устанавливается поверх вашей копии игры из GOG
или Steam.

**[Скачать установщик](https://github.com/potiondev/cossacks-fan-remaster/releases/latest/download/Cossacks-Fan-Remaster-Setup.exe)**
· [Все выпуски](https://github.com/potiondev/cossacks-fan-remaster/releases)
· [Поддержать проект](#поддержать-проект)

> **Оригинальная игра, а не ремейк.** Fan Remaster не переписан заново, как
> игры новой волны. Он сделан на основе этого:
> https://github.com/ereb-thanatos/cossacks-revamp-2017. Огромное спасибо
> ему!!!

### Содержание

- [Коротко о новом](#коротко-о-новом)
- [Что нужно](#что-нужно)
- [Установка](#установка)
- [Обновления](#обновления)
- [Совместная игра](#совместная-игра)
- [Конфиденциальность](#конфиденциальность)
- [Что-то пошло не так?](#что-то-пошло-не-так)
- [Поддержать проект](#поддержать-проект)
- [Что изменилось по сравнению с оригиналом](#что-изменилось-по-сравнению-с-оригиналом)
- [Удаление](#удаление)
- [Благодарности](#благодарности)

### Коротко о новом

- **До 16 игроков** в одиночной и сетевой игре, на картах вплоть до
  гигантских.
- **Новые компьютерные противники**, от лёгкого до брутального. Уровни
  отличаются тем, насколько хорошо они играют, а не тем, как быстро
  строят. Четыре уровня 2002 года тоже остались.
- **Генератор карт, который показывает карту до начала игры**: формы суши,
  острова, полуострова, вода, камень, богатства, снег, пустыня и многое
  другое.
- **Глубокий снег** (бета), в котором войска вязнут и замедляются,
  оставляя за собой следы.
- **Масштаб** от крупного плана до всей карты, рисует видеокарта.
- **Сражения до 1 000 000 воинов:** симуляция использует все ядра
  процессора.
- **Плавное движение** и повороты при любой частоте кадров, и VSync.
- **Современный интерфейс**, масштабируемый до 4K.
- **Сетевая игра:** список открытых игр, Быстрый и Рейтинговый 1v1 с
  таблицей лидеров, ссылки-приглашения, возвращение после вылета и
  сохранённые сетевые игры. Сетевые игры идут через ретранслятор, поэтому
  игроки не видят IP-адреса друг друга (кроме приватных игр).
- **Двенадцать языков:** английский, чешский, немецкий, испанский,
  французский, венгерский, итальянский, польский, бразильский
  португальский, русский, турецкий и украинский.
- **Картины эпохи** с реальными местами в меню и на экранах загрузки.
- **Эффекты на поле боя** на пробу (бета): дым, пыль, погода, тени облаков,
  следы кораблей и колышущаяся трава.
- **Сообщение об ошибке** прямо из игры со снимком экрана.
- **Автоматические обновления**, и можно откатиться к любой предыдущей
  версии.

### Что нужно

- Windows 10 или 11 и экран не меньше 1280x720.
- Видеокарта с поддержкой Direct3D 11.
- **Cossacks: Back to War** из [GOG](https://www.gog.com/) или
  [Steam](https://store.steampowered.com/).
- Около 1,5 ГБ свободного места, ещё около 320 МБ на каждый язык, кроме
  английского, и подключение к интернету во время установки.

### Установка

1. Установите Cossacks: Back to War из GOG или Steam, если ещё не
   установили.
2. Скачайте **Cossacks-Fan-Remaster-Setup.exe** (ссылка вверху).
3. Запустите его. Windows может показать *«Система Windows защитила ваш
   компьютер»*, потому что установщик не подписан. Нажмите **Подробнее**,
   затем **Выполнить в любом случае**.
4. Выберите язык установщика, а среди языков игры отметьте те, на которых
   хотите играть.
5. Установщик сам найдёт вашу копию из GOG или Steam. Если не найдёт,
   укажите папку игры. Он проверит, что это знакомая ему копия, и
   скопирует нужные данные игры. Вашу копию он только читает: игра из GOG
   или Steam остаётся как есть и запускается как раньше.
6. Остальное он загрузит, около 535 МБ. Каждый язык, кроме английского,
   добавляет около 316 МБ, в основном собственные экраны загрузки.
7. Запускайте игру из меню «Пуск» или с ярлыка на рабочем столе. При первом
   запуске игра спросит ваше имя.

Всё устанавливается в вашу пользовательскую папку
(`%LOCALAPPDATA%\Programs\Cossacks Fan Remaster`, если не выберете другую),
поэтому права администратора не нужны.

### Обновления

Когда выходит новая версия, игра сообщает об этом в главном меню и
показывает, что изменилось:
- **Обновить** закрывает игру, обновляет её и запускает снова.
- **Позже** спросит в следующий раз.
- **Пропустить** не спрашивает до следующей версии.

Кнопка обновлений в правом верхнем углу главного меню показывает все
выпуски с их описанием. Оттуда можно обновиться или вернуться к более
старой версии и обратно. Повторный запуск установщика тоже обновляет и
восстанавливает игру. Если не хотите, чтобы игра проверяла обновления,
отключите в установщике проверку обновлений при запуске игры.

### Совместная игра

В **сетевой игре** три страницы:
- **Публичные:** все открытые игры в одном списке. Вход одним щелчком,
  своя игра с паролем или без, Быстрый 1v1 или Рейтинговый 1v1, или
  ссылка-приглашение другу. Не нужны ни проброс портов, ни дополнительные
  программы.
- **Приватные:** игра по прямому IP с паролем. Игроки соединяются
  напрямую, поэтому видят IP-адреса друг друга.
- **Классические:** оригинальные игры по LAN и Direct TCP/IP и
  Историческое сражение.

У всех должна быть **одна и та же версия**. Ваша показана в главном меню.
В лобби у игрока с другой версией она показана рядом с именем, и игра не
начнётся, пока он не обновится.

### Конфиденциальность

- Перед первой сетевой игрой игра попросит принять короткое уведомление о
  том, что отправляет сетевая игра. Для одиночной игры ничего не нужно.
- **Статистика игры** отправляется, только если вы согласитесь, когда игра
  спросит. Ответ можно изменить, а свои данные скачать или полностью
  удалить на странице настроек.
- Что хранится, зачем и как долго, описано на
  [странице конфиденциальности](https://cossacks-lobby.potiondev.workers.dev/privacy)
  (на английском).

### Что-то пошло не так?

- **В игре:** воспользуйтесь **сообщением об ошибке** в верхней панели
  главного меню или в игровом меню. Опишите, что произошло; по желанию
  добавится снимок экрана. После вылета игра при следующем запуске
  предложит сообщить о нём.
- **На GitHub:**
  [создайте issue](https://github.com/potiondev/cossacks-fan-remaster/issues)
  и приложите нужный файл из папки игры: `Remaster\update.log`, если не
  удалась установка или обновление, или `crash.log`, если игра вылетела.

### Поддержать проект

Fan Remaster бесплатен и всегда будет бесплатным. Если он вам нравится,
можно оставить чаевые на **[Buy Me a Coffee](https://buymeacoffee.com/potion26)**.
Кнопка **DONATE** в главном меню ведёт туда же.

### Что изменилось по сравнению с оригиналом

Отправная точка: Cossacks: Back to War 1.35 (2002) в переработке Ereb 2017
года, [версия 1.42](https://github.com/ereb-thanatos/cossacks-revamp-2017).
Та версия приспособила игру к современной Windows: скорость на современных
процессорах, цветовая палитра, вылеты при большом числе юнитов или длинных
стенах, оконные режимы и настройка размера интерфейса. Всё, что ниже,
построено поверх этого кода. Это не список всех изменений, а рассказ о том,
что сделано с каждой частью игры.

#### Движок остался тем же движком

- Игра по-прежнему работает на движке 2002 года на C++: около 270 исходных
  файлов, 32 бита, сборка современным компилятором Microsoft. Ни одна его
  часть не переписана заново.
- **Библиотеки компьютерных игроков.** Двадцать библиотек ИИ, по одной на
  нацию, поставлялись с игрой только в виде скомпилированных двоичных
  файлов 2002 года. Их декомпилировали обратно в C++, и теперь они
  собираются из этого кода. С оригиналами их сверили, записав и сравнив
  каждый вызов движка, который делает каждая из них: те же вызовы при
  загрузке и те же вызовы, когда одна записанная игра воспроизводится с
  каждой.
- **Сетевая игра по-прежнему идёт в lockstep.** Компьютер каждого игрока
  выполняет одну и ту же симуляцию по одним и тем же командам, как в 2002
  году. Каждое изменение, касающееся симуляции, сохраняет её строго
  детерминированной: те же случайные числа в том же порядке и те же
  граничные случаи целых чисел. Номер сборки в лобби разделяет разные
  версии.

#### Графика

- **Рендерер на видеокарте.** Игра 2002 года рисует каждый пиксель на
  процессоре в 8-битную картинку на 256 цветов, а видеокарта только
  показывает результат. Fan Remaster перенёс это рисование на видеокарту
  через Direct3D 11, поэтапно, внутри той же 32-битной программы: спрайты,
  ландшафт (теперь это сетка), море и туман войны. Оригинальные таблицы
  цветов для теней, полупрозрачности и цветов команд тоже применяются на
  видеокарте, поэтому игра выглядит как прежде.
- **Масштаб** от крупного плана до всей карты, даже гигантской. Ни на каком
  масштабе ничего не прореживается и не скрывается ради скорости: издалека
  юниты рисуются проще, но рисуются всегда.
- **Плавное движение.** Симуляция делает 40 шагов в секунду, как раньше.
  Теперь юниты рисуются и между шагами и плавно поворачиваются, поэтому
  движение плавное при любой частоте кадров. Камера скользит, добавлена
  настройка VSync.
- **Море** набегает на берег и откатывается, а вблизи выглядит гладким.
- **Разрешения до 4K и выше**, интерфейс масштабируется вместе с ними,
  текст чёткий при любом размере.
- **Эффекты на поле боя** (бета, выключены, пока вы их не включите),
  двенадцать, каждый со своим переключателем: тени облаков, дым мушкетов и
  пушек, горящие здания, пыль, следы и брызги кораблей, дождь, снег и
  дымка, туман войны в виде плывущей дымки, протоптанные тропы и воронки,
  мягкие тени под юнитами, тряска экрана, колышущаяся трава и F10, чтобы
  скрыть интерфейс. Это только картинка, на симуляцию они не влияют.
- **Метки при отдалении:** издалека каждый юнит и здание отмечены цветом
  владельца.
- **Частоту кадров и пинг** можно показать в углу (Настройки).

#### Симуляция и производительность

- **Все ядра процессора.** Поиск целей, приказы, движение, таблицы клеток
  карты, туман, миникарта и сортировка спрайтов для отрисовки теперь
  работают на всех ядрах. Их результаты применяются в исходном порядке,
  поэтому игра у каждого игрока по-прежнему рассчитывает одно и то же
  сражение.
- **Большие сражения, до миллиона юнитов.** Предел объектов в игре вырос с
  65 535 до 1 048 576. Сражение на 200 000 юнитов, видимое целиком,
  ускорилось примерно с 15 до 240 кадров в секунду (1080p, 8-ядерный
  процессор), а симуляция держит свои 40 шагов в секунду.
- **Более быстрый поиск.** С новым поиском пути за час проходит примерно в
  1,7 раза больше игр с теми же результатами, и поиск ближайшего склада
  тоже стал быстрее.
- **Ошибки, которые проявлялись только в большом масштабе**, исправлены.
  Пример: счётчик еды нации переполнялся, когда едоков было больше
  примерно 21 800.

#### Шестнадцать игроков

- В движке 2002 года было восемь мест для наций: семь игроков и
  нейтральная нация. Теперь их семнадцать: шестнадцать игроков и
  нейтральная нация.
- Для этого пришлось расширить маски союзов с 8 до 32 бит (на них
  построена каждая проверка «свой или чужой»), таблицы присутствия наций в
  каждой клетке и поля выделения у каждого юнита. Пришлось также
  переделать сообщение о начале игры и лобби и добавить шестнадцать цветов
  игроков.
- Карты для оригинальной игры и файлы редактора карт загружаются как
  раньше.

#### Компьютерные игроки

- **Чем был уровень сложности.** В 2002 году четыре уровня отличались
  одним: тем, как долго компьютер производил войска. Тот же порядок
  строительства, те же армии, та же агрессия и те же ошибки.
- **Командир.** Новый стратегический слой в движке принимает решения,
  которые принимает игрок: когда и где атаковать, когда отступить, что
  защищать и как отвечать на увиденное. Он работает поверх библиотек
  наций, которые по-прежнему знают войска каждой нации.
- **Сложность означает мастерство.** Каждый новый уровень производит в
  темпе игрока. Лёгкий, Нормальный, Сложный, Очень сложный и Брутальный
  различаются тем, какие решения им разрешены и как часто они смотрят на
  поле. Четыре оригинальных уровня 2002 года остались в списке.
- **Всё измерено.** Изменения компьютерных игроков остаются, только если
  они выигрывают чаще. Это измеряется на множестве полных игр, которые
  идут без участия человека, по нескольку одновременно, и каждая пара
  играет с обеих сторон.

#### Карты

- **Генератор случайных карт** теперь рисует карту на странице одиночной
  игры ещё до начала. Превью и настоящая карта строятся по одному плану,
  поэтому вы играете на том, что видите. Есть формы суши (острова,
  полуострова и экстремальные формы), один против всех, ползунки для воды,
  камня, рельефа, лесов и богатств, тип земли (снег, пустыня, мели),
  стартовые позиции, которые можно перетаскивать, скрытые карты и
  полностью случайный вариант. Карты бывают до гигантских, 3840 клеток в
  ширину.
- **Глубокий снег** (бета) входит в симуляцию, поэтому он одинаков для
  всех игроков и попадает в сохранения. Юниты увязают и замедляются. Их
  следы протаптываются постепенно и заметаются снова только во время
  снегопада.
- **Редактор карт** масштабируется колесом мыши и использует современный
  вид.

#### Сетевая игра и игра онлайн

- **Лобби — это страница одиночной игры с чатом.** Настройки карты хоста
  передаются всем игрокам, и игра каждого строит по ним ту же карту.
- **Публичные** игры обслуживает небольшой сервер лобби. Он хранит список
  игр, пароли, подбор соперников для Быстрого и Рейтингового 1v1 с
  рейтингами и таблицей лидеров (рейтинговые игры идут на зеркальных картах
  с фиксированными настройками) и ссылки-приглашения. Сама игра
  по-прежнему идёт между компьютерами игроков, через ретранслятор, который
  скрывает их IP-адреса. Если месячный лимит ретранслятора исчерпан, игры
  соединяются напрямую, и игра предупреждает об этом до входа. Приватные
  игры всегда соединяются напрямую.
- **Возвращение.** Игрок, у которого игра вылетела или который вышел,
  может вернуться: игра начинается заново с того места, где остановилась,
  со всеми, кто вернулся.
- **Сохранённые сетевые игры** можно продолжить позже. Хост отправляет
  сохранение и карту всем.
- **Учётная запись без регистрации.** Можно добавить email, чтобы входить
  на новом компьютере по присланному коду. Паролей нет.
- Оригинальное сетевое ядро сохранено и укреплено после проверки
  безопасности.

#### Интерфейс

- **Современный вид**, который игра рисует сама при любом размере: меню,
  кнопки, верхняя панель, игровое меню и панели.
- **Переработанные меню**, выстроенные вокруг содержимого, на фоне картин
  эпохи с реальными местами каждой нации.
- **Новые страницы:** статистика после игры, Мои игры (история ваших игр),
  список версий, сообщение об ошибке, поддержка проекта и
  конфиденциальность. Страницы настроек разложены в два столбца.
- **Мелочи:** счётчик неполных шахт на верхней панели (щелчок ведёт к
  следующей), полоса урона, курсор точки сбора и стрелка строя, которая
  следует за масштабом.

#### Языки

- Одиннадцать языков помимо английского. Каждый из них — набор текстовых
  файлов со своими шрифтами и своими экранами загрузки, и каждый
  загружается по желанию.
- Растровые шрифты 2002 года дополнены буквами с диакритикой для каждого
  языка и кириллицей.

#### Установка и обновление

- **В загрузке нет данных GSC**, кроме 26 записей архива игры, которые
  меняет ремастер. Установщик находит копию GOG по реестру, а копию Steam
  по библиотекам Steam. Он побайтно проверяет главный архив игры, затем
  копирует 1781 нужный файл, проверяя каждый.
- **Программа обновления** загружает пакеты и проверяет хеш SHA-256
  каждого, прежде чем что-либо заменить. Неизменённый пакет никогда не
  загружается повторно. Если что-то идёт не так, файлы возвращаются на
  место, поэтому после неудачного обновления старая версия продолжает
  работать. Повторный запуск восстанавливает недостающие файлы, и
  программа обновляет сама себя.
- **Музыка** играет из вашей копии: через заменитель CD из GOG или его
  аналог из Steam.

#### Некоторые исправления игры 2002 года

- Юниты уходят с места нового здания, а не загораживают его.
- Юниты быстрее реагируют на врагов рядом с собой.
- Пушечные ядра летят по той траектории, по которой их навели.
- Священники больше не лечат юнитов, ставших врагами.
- Приказ огромному выделению больше не оставляет часть войск без дела.
- Случайная карта больше не рассинхронизируется, если у игрока есть та же
  карта из прошлой игры.
- Настройка скорости игры больше не меняет исход игры.
- Исправлен вылет, когда компьютерные игроки искали цели для своих
  военных кораблей.
- Фильтр слов в чате убран.

### Удаление

В Windows: **Параметры → Приложения → «Cossacks: Back to War - Fan
Remaster»**. Программа спросит, оставить ли ваши сохранённые игры и
настройки.

### Благодарности

Источники картинок, данных карт и шрифтов указаны в
[CREDITS.md](CREDITS.md).

- **Cossacks: Back to War** (2002): **GSC Game World**.
- Основано на исходном коде игры в переработке **Ereb** 2017 года
  ([cossacks-revamp-2017](https://github.com/ereb-thanatos/cossacks-revamp-2017)).

Это фанатский проект. Он не создан, не одобрен и не поддерживается GSC Game
World, GOG или Valve. Нужна своя копия Cossacks: Back to War: загрузка не
содержит игру, установщик копирует нужное из вашей копии.
