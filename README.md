Níže jsou popsané kroky pro jednotlivé části webové stránky, které budeme upravovat. Pokud se to bude hodit, využij CSS proměnné:

## 1. Nastavení základních stylů pro `body`

- **Nastavte písmo stránky:** na "Montserrat", pokud se nanačte, pak "sans-serif"

- **Nastavte barvu textu:** na hodnotu `#333`

- **Nastavte barvu pozadí stránky:** na hodnotu `#f3f4f6`

- **Řádková výška pro lepší čitelnost:** zvětšte výšku řádku na `1.6` (tedy o 60% větší než je výška textu)

## 2. Styl pro hlavní nadpis

- **Nastavte barvu textu:** na `#512da8`, aby byl nadpis výrazný.

- **Zarovnání na střed:** text zarovnějte tak, aby byl nadpis umístěn uprostřed stránky.

- **Nastavte velikost písma:** na `40px` pro větší a čitelnější nadpis.

- **Zvýrazněte nadpis tučně:** text udělejte tučný, aby nadpis vynikl.

## 3. Styl pro všechny sekce

> **Poznámka:** `section` je sémantický element, což znamená, že naznačuje významnou část stránky. Nastavení těchto stylů zde zajistí, že se budou aplikovat na všechny elementy `section` v dokumentu.

- **Nastavte barvu pozadí:** na `#f9f9fc`, aby sekce měly jemné světle šedé pozadí.

- **Přidejte zaoblené rohy:** Přidejte vlastnost `border-radius` s hodnotou `10px`, aby sekce měly mírně zakulacené rohy.

- **Nastavte rámeček:** přidejte vlastnost `border` s hodnotou `1px solid #ddd` pro jemný rámeček, který sekce vizuálně oddělí.

## 4. Styl pro nadpisy sekcí

- **Nastavte barvu textu:** na `#4a148c`, aby byly nadpisy sekcí výraznější a snadněji rozpoznatelné.

- **Nastavte velikost písma:** na `28px`, aby nadpisy byly dobře viditelné a odlišné od běžného textu.

- **Přidejte spodní rámeček:** přidejte vlasnost `border-bottom` s hodnotou `2px solid rgba(74, 20, 140, 0.2)` pro jemné zvýraznění nadpisu.

- **Změňte text na velká písmena:** tak, aby se celý nadpis zobrazoval velkými písmeny.

## 5. Styl pro profilovou fotografii

> **Poznámka:** V této části budeme stylovat obrázek profilové fotografie, aby vypadal profesionálněji a lépe zapadal do designu stránky.

- **Zobrazte obrázek jako blokový element:** přidejte vlastnost `display` a nastavte ho na `block`, což umožní centrující efekty pomocí `margin`.

- **Zaoblete obrázek:** přidejte vlastnost `border-radius` s hodnotou `50%`, aby byl obrázek kruhový.

- **Přidejte rámeček:** Přidejte vlastnost `border` s hodnotou `3px solid #9575cd`, což vytvoří jemný fialový rámeček kolem profilové fotografie.

## 6. Styl pro odkazy uvnitř `.info-list` a `.job-responsibilities`

> **Poznámka:** V tomto kroku stylujeme specifické odkazy (`a` elementy) nacházející se uvnitř seznamů `.info-list` a `.job-responsibilities`. Tímto způsobem zaměříme styl pouze na odkazy v těchto konkrétních částech stránky, aniž bychom ovlivnili jiné odkazy.

- **Nastavte barvu textu odkazu:** na `#512da8`, aby odkazy ladily se stylem celé stránky.

- **Přidejte podtržení pro vizuální zvýraznění:**, aby odkazy byly viditelnější.

- **Nastavte typ kurzoru pro interaktivitu:** Přidejte vlastnost `cursor` s hodnotou `pointer` – tím zajistíte, že se kurzor změní při najetí myší na odkaz, což naznačuje, že je interaktivní.

## 7. Hover efekt pro odkazy uvnitř `.info-list` a `.job-responsibilities`

> **Poznámka:** V tomto kroku stylujeme odkazy (`a` elementy) uvnitř seznamů `.info-list` a `.job-responsibilities`. Tentokrát se zaměříme na přidání efektu při najetí myší, což se nazývá **hover efekt**. Tento efekt použijeme pouze na odkazy uvnitř těchto specifických seznamů, aniž bychom ovlivnili ostatní odkazy na stránce.

> Když použijeme pseudo-třídu `:hover`, styl se aplikuje pouze ve chvíli, kdy uživatel najede myší na daný prvek. Tento efekt dodává odkazům interaktivitu a uživateli ukazuje, že jsou klikatelné.

- **Vytvořte odpovídající selektor a jeho blok:** vytvoř selektor odkazující na odkazy a následnou pseudotřídou `:hover`
- **Změňte barvu textu při hover efektu:** na `#311b92`, aby se barva odkazu změnila při najetí myší na tmavší odstín.

- **Odstraňte podtržení odkazu při hover efektu:** zrušte podtržení (hodnota `none`), aby se podtržení odkazu při najetí myší odstranilo a vytvořil se tak elegantní efekt.

## 8. Styl pro nadpis pracovních pozic

- **Nastavte barvu textu:** na `#4a148c`, aby byl nadpis pracovních pozic sladěn s celkovou barevnou schémou stránky.

- **Nastavte velikost písma:** na `21px`, aby byl nadpis čitelný a snadno odlišitelný od ostatního textu.

- **Zvýrazněte nadpis tučným písmem:**, aby nadpis pracovních pozic více vynikl.

## 9. Styl pro nadpis vzdělání

- **Nastavte velikost písma:** na `20px`, aby byl nadpis vzdělání dostatečně viditelný a odlišný od ostatního textu.

- **Zvýrazněte nadpis tučným písmem:** aby nadpis více vynikl a upoutal pozornost.
