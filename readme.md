# Minecraft Server s Mody

Tento repozitář obsahuje konfiguraci a modifikace pro vytvoření vlastního Minecraft serveru s módy. Následující kroky vám pomohou nastavit server a připojit se k němu s klientem obsahujícím požadované módy.

## Požadovaný software

1. **Git:** nainstalujte Git podle návodu dostupného na [git-scm.com](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
2. **Docker Desktop s WSL:** Nainstalujte Docker Desktop s Windows Subsystem for Linux (WSL) podle pokynů dostupných na [docker.com](https://docs.docker.com/desktop/install/windows-install-wsl/).
3. **Curse Forge:** Stáhněte Curse Forge z oficiálního webu [curseforge.com](https://www.curseforge.com/). 
4. **Minecraft:** Nainstalujte Minecraft, ideálně ve verzi kompatibilní s modifikacemi na serveru.
5. **Visual Studio Code:** Stáhněte Visual Studio Code z [code.visualstudio.com](https://code.visualstudio.com/).

## Nastavení serveru

1. Naklonujte tento repozitář pomocí příkazu: ```git clone https://github.com/Yorrii/LTP```
2. Otevřete staženou složku v terminálu.
3. Spusťte Docker Desktop a následně spusťte server pomocí příkazu: ```docker compose up -d```
4. Po chvíli by měl být server připravený k použití.

## Připojení klienta

1. V Curse Forgi se přihlašte a vyhledejte mod pack, který je kompatibilní se serverem.
2. Stáhněte a nainstalujte požadovaný mod pack.
3. Spusťte Minecraft a vyberte stažený mod pack.
4. Připojte se k serveru a začněte hrát!

## Poznámky

- Ujistěte se, že máte správnou verzi mod packu pro server a klienta.
- Pokud narazíte na problémy, zkontrolujte konzoli Dockeru a logy serveru ve Visual Studio Code.

Těšíme se na společnou hru na našem vlastním Minecraft serveru s módy! 🎮