# FLOWTIME.AI — AI automatizációs kalkulátor

Egyszerű, önálló weboldal, amellyel megbecsülhető, hogy egy marketingfolyamat AI-alapú automatizálása mennyi időt szabadíthat fel, milyen havi értéket képviselhet, és várhatóan mikor térül meg.

## Használat

Nyisd meg az `index.html` fájlt egy modern böngészőben. Nincs szükség telepítésre, buildlépésre vagy külső könyvtárra. A stílusok, a működés és a háttérkép adatai is a HTML-fájlban vannak.

Az oldal bemutatja az automatizálható marketingfolyamatokat, a kalkulátor használatát, az időmegtakarítás szempontjait és a gyakori kérdéseket. Mobilon is alkalmazkodó, aszimmetrikus elrendezést használ, finom görgetési animációkkal és csökkentett mozgás beállítással.

## Mit lehet beállítani?

- Automatizálandó marketingfolyamat: érdeklődőszerzés, utánkövetés, kampányok, tartalomterjesztés, riportolás vagy ügyfélmegtartás
- Heti alkalomszám és alkalmankénti kézi munkaidő
- Emberi ellenőrzési idő és automatizálható munkaarány
- Munkaidő becsült értéke, elkészítési idő, eszközdíj és külső elkészítési díj

## A becslés képletei

- Havi alkalmak = heti alkalmak × 52 ÷ 12
- Automatizált idő = havi alkalmak × kézi perc × automatizálható arány ÷ 60
- Ellenőrzési idő = havi alkalmak × ellenőrzési perc ÷ 60
- Visszanyert idő = az automatizált idő és az ellenőrzési idő különbsége, legalább nulla
- Havi időérték = visszanyert idő × megadott óradíj
- Havi nettó előny = havi időérték − eszközök havi díja
- Induló ráfordítás = elkészítési idő × óradíj + külső elkészítési díj
- Megtérülési idő = induló ráfordítás ÷ havi nettó előny, ha a nettó előny pozitív
- Első évi egyenleg = 12 × havi nettó előny − induló ráfordítás

Az eredmények tájékoztató becslések. A megadott óradíjból számolt időérték nem garantált pénzbevétel.
