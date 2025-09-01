Steam (2024-02)
<br/>
Velikost 417MB https://drive.google.com/drive/folders/1obLBgt45g4XJpu-ugXTyqO2FZhYQAzVA
<br/>
<br/>
<br/>
Postup
<br/>
-aplikovat CZ patch
<br/>
-nakopírovat obsah složky "_CZ-PART2" do hry. Steam klient je pro hraní zbytečný
<br/>
<br/>
<br/>
Překlad už obsahuje níže uvedený patch opravující černou obrazovku, kdy hra nejde spustit
<br/>
https://www.xzone.cz/download/rw_patch_cz.exe
<br/>
<br/>
<br/>
Chyby
<br/>
-pro hraní bude třeba vkládat 3CD (nebo zkusit 1DVD, k tomu stačí jednoduchý portable program "PortableWinCDEmu" - je možné je vložit všechny najednou do tří virtuálních mechanik) https://github.com/hornster02/Runaway-2001-CZ/raw/main/mini-image.rar

-největší problém ale zřejmě bude "zamrzání" hry (ESC funguje) na konci jednotlivých předrenderovaných videí (71 souborů) - jedna scéna může být složená z několika souborů a vznikají tedy prodlevy trvající většinou několik vteřin. Při přehrávání videa s parukou ale "zamrznutí" hry trvalo odhadem 4-6 minut. Řešení je několik
<br/>
1 - zřejmě nejhorší je použít "dgVoodoo2" wrapper a v jeho pokročilých možnostech nastavit limit 20FPS = velký lag myši a trhaný obraz
<br/>
2 - "Autohotkey" skript - F10 (držet 1 vteřinu) se hra pozastaví (suspend) a 2x stisknutím F10 se hra spustí čímž "zamrznutí" okamžitě končí a je možno pokračovat dál
<br/>
3 - zřejmě nejlepší řešení je použít portable program "Battle Encoder Shirasé" a omezit herní proces. Stačí spustit příkaz níže (nejdříve upravit cesty k EXE souborům a případně upravit číslo na konci v rozmezí 1-99 - čím vyšší číslo, tím větší omezení), "Battle Encoder Shirasé" bude v pozadí systému spuštěný a automaticky herní proces omezí ```c:\BES\BES.exe -J "c:\Runaway A Road Adventure\Runaway.exe" 20 -m```

-pokud se přehrává zvuk ale ne videa, tak jsou problémy s videokodeky (pokud není možné pokračovat přes intro, tak je možné načíst hru)
<br/>
<br/>
<br/>
Autohotkey v1.1 https://github.com/hornster02/Runaway-2001-CZ/raw/main/script.rar
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
