# NASA App
## Verze 1

Roman Krof <br/>
krof.roman.2018@skola.ssps.cz <br/>
15. 11. 2021

* Úvod
  * Účel dokumentu
    * Dokument slouží k rychlému seznámení se systémem a jeho vlastnostmi
  * Konvence dokumentu
    * Důležitost - 1 nejvyšší, 3 nejnižší
    * Všechny kritické požadavky budou tučně
  * Kontakty
    * Roman Krof krof.roman.2018@skola.ssps.cz, tel. 999 888 777, Facebook: Roman Krof
* Celkový popis
  * Funkce
    * Program má jednoduchou funkci: zobrazení vesmírných těles, která se přiblížila k Zemi, a jejich stručný popis (rychlost, kdy se přiblížila)
  * Uživatelské skupiny
    * Široká veřejnost, vesmírní nadšenci
  * Omezení návrhu a implementace
    * Pomalejší odezva
* Požadavky na rozhraní
  * Uživatelská rozhraní
    * **WPF**
  * Softwarová rozhraní
    * **Windows**
* Vlastnosti systému
  1. **Podrobnosti tělesa**
    * Důležitost: 1
    * Vstup: název položky a dílčí informace: čas a datum, průměr, rychlost, vzdálenost od Země
    * Akce: po kliknutí na těleso se otevře okno s podrobnějšími podrobnostmi tělesa
    * Výstup: podrobnějíš informace
  2. **Aktualizace**
    * Důležitost: 1
    * Vstup: informace z API od NASA
    * Akce: po kliknutí na tlačítko se přijmou nová data
    * Výstup: vypsání aktualizovaného seznamu těles
* Nefunkční požadavky
  * Odezva
    * Program aktualizuje data do 10-ti sekund od zažádání
  * Spolehlivost
    * Program při správných podmínkách ve více jak 99% případů správně aktualizuje informace a vypíše informace
  * Bezpečnost
    * Program pracuje s pouze s daty od NASA
