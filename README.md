Steam (2024-02)
<br/>
Velikost 406MB https://drive.google.com/drive/folders/1obLBgt45g4XJpu-ugXTyqO2FZhYQAzVA

Postup -
<br/>
■ aplikovat CZ patch
<br/>
■ nakopírovat obsah složky ```_CZ-PART2``` do hry

Chyby -
<br/>
■ "zamrzání" hry (ESC funguje) na konci jednotlivých předrenderovaných videí (71 souborů) - jedna scéna může být složená z několika souborů a vznikají tedy prodlevy trvající většinou několik vteřin. Při přehrávání videa s parukou ale "zamrznutí" hry trvalo odhadem 4-6 minut. Řešení je několik -
<br/>
1 - zřejmě nejhorší je použít "dgVoodoo2" wrapper a v jeho pokročilých možnostech nastavit limit 20FPS = velký lag myši a trhaný obraz
<br/>
2 - "Autohotkey" skript - F10 (držet 1 vteřinu) se hra pozastaví (suspend) a 2x stisknutím F10 se hra spustí čímž "zamrznutí" okamžitě končí a je možno pokračovat dál
<br/>
3 - zřejmě nejlepší je použít portable program "Battle Encoder Shirasé" a omezit herní proces. Stačí spustit příkaz níže (nejdříve upravit cesty k EXE souborům a případně upravit číslo v rozmezí 1-99 - čím vyšší, tím větší omezení), "Battle Encoder Shirasé" bude v pozadí systému spuštěný a automaticky herní proces omezí ```c:\BES.exe -J "c:\Runaway.exe" 20 -m```

■ závislost na systémových audio/video kodecích -
<br/>
-crash při spuštění EXE (při vypnutém "Color Space Converter" + "AVI Splitter" + "LAV Filters")
<br/>
-černá obrazovka (při zapnutém "AVI" v "LAV Splitter" ```"C:\Windows\system32\rundll32.exe" "c:\LAV Filters\x86\LAVSplitter.ax",OpenConfiguration```) = pokud se hned po spuštění EXE nezobrazí logo "TOP Distributor", ale přehraje se jenom zvuk, tak je to problém který rozbije hru (ne pouze videa) = může se také vyřešit vypnutím "LAV Splitter"

Jiné -
<br/>
■ CZ obsahuje opravu nemožnosti spustit hru (černá obrazovka) https://www.xzone.cz/download/rw_patch_cz.exe
<br/>
■ jiná verze (Velikost 1178MB) https://steamcommunity.com/sharedfiles/filedetails/?id=3156354546

Autohotkey v1.1 (AHK)
<br/>
```CTRL+ALT+INS``` pozastavit/spustit skript (globální klávesa)
<br/>
```CTRL+ALT+HOME``` restartovat skript (globální klávesa)
<br/>
```Launch_App2``` vypnout hru (stisknout/držet/2x stisknout - globální klávesa) - deaktivováno, uživatelsky specifický komplexnější skript
<br/>
```F10``` pozastavit/spustit hru (držet 1 vteřinu/2x stisknout - suspend, globální klávesa)
<br/>
```F11``` (držet) zabrání kurzoru myši pohyb mimo aktivní okno - přepínač
<br/>
```F12``` (držet) zapnout/vypnout borderless fullscreen - přepínač
<br/>
```kolečko myši nahoru``` ESC
<br/>
```kolečko myši dolu``` inventář
