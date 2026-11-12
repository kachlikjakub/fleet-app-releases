# Fleet – vydané verze

Tady jsou instalátory aplikace **Fleet** (správce vozového parku pro Autoholubku).
Zdrojový kód je soukromý, tohle repozitář obsahuje jen hotové verze ke stažení.

## Instalace

1. Otevřete [poslední verzi (Releases)](../../releases/latest).
2. Stáhněte soubor `Fleet-Setup-x.y.z.exe` a spusťte ho. Instalace proběhne bez dalších dotazů.
3. Při spuštění Windows může zobrazit upozornění „Windows ochránil váš počítač“, protože instalátor zatím není podepsaný. Zvolte *Další informace → Přesto spustit*.

Aplikace se po instalaci **aktualizuje sama**: při spuštění zkontroluje nové verze a nabídne instalaci.
Data (vozidla, fotky) se při aktualizaci ani odinstalaci nemažou.

## Pro vývojáře

Release se vytváří automaticky z privátního repozitáře `kachlikjakub/fleet-app` (GitHub Actions) po nahrání tagu `vX.Y.Z`.
Do tohoto repozitáře se nic neposílá ručně.
