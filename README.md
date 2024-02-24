Steam (2024-02)
<br/>
Včetně CZ dabingu. Velikost 417MB https://drive.google.com/drive/folders/1obLBgt45g4XJpu-ugXTyqO2FZhYQAzVA
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
Autohotkey v1.1 https://github.com/hornster02/Runaway-2001-CZ/raw/main/script.rar
<br/>
-ESC (držet 1 vteřinu) - vypnout hru (nemusí být v popředí a ani reagovat)

-kolečko myši nahoru - ESC

-kolečko myši dolu - tab (inventář)
<br/>
<br/>
<br/>
Chyby
<br/>
-pro hraní bude třeba vkládat CD (k tomu stačí jednoduchý portable program "PortableWinCDEmu" - je možné je vložit všechny najednou do tří virtuálních mechanik). Pokud se někdy najde crack nebo EXE soubor vyžadující vložené pouze 1 DVD, tak by to bylo lepší...
<br/>
https://github.com/hornster02/Runaway-2001-CZ/raw/main/mini-image.rar

-největší problém ale zřejmě bude "zamrzání" hry (ESC funguje) na konci jednotlivých předrenderovaných videí (71 souborů) - jedna scéna může být složená z několika souborů a vznikají tedy prodlevy trvající většinou několik vteřin. Při přehrávání videa s parukou ale "zamrznutí" hry trvalo odhadem 4-6 minut. Řešení je několik
<br/>
1 - zřejmě nejhorší je použít "dgVoodoo2" wrapper a v jeho pokročilých možnostech nastavit limit 20FPS = velký lag myši a trhaný obraz
<br/>
2 - "Autohotkey" skript na mém profilu. 1 vteřinu dlouhé podržení klávesy F10 se aktivní proces (tedy hra) pozastaví (suspend - ve správci úloh bude stav procesu uveden jako "neodpovídá") a opětovným podržením klávesy F10 se proces spustí čímž "zamrznutí" hry okamžitě končí a je možno pokračovat dál
<br/>
3 - zřejmě nejlepší řešení je použít portable program "Battle Encoder Shirasé" a omezit herní proces. Stačí spustit příkaz níže (nejdříve upravit cesty k EXE souborům a případně upravit číslo na konci v rozmezí 1-99 - čím vyšší číslo, tím větší omezení), "Battle Encoder Shirasé" bude v pozadí systému spuštěný a automaticky herní proces omezí
<br/>
```c:\BES\BES.exe -J "c:\Runaway A Road Adventure\Runaway.exe" 20 -m```
<br/>
I tento problémový bod může vyřešit jiný EXE soubor
