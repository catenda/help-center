# Sorteringsrekkefølge for lister

Lister rundt Catenda sorteres etter Unicode-verdier. For å finne ut hvilke bokstaver som har hvilke Unicode-verdier, se [denne Wikipedia-artikkelen](https://en.wikipedia.org/wiki/List_of_Unicode_characters). Klikk her for å lese mer om typiske strategier som brukes ved navngiving av elementer slik at de ender opp i riktig rekkefølge.

## 1. **Lister som bruker denne sorteringen**

Prosjektliste Modelltabell Bokmerker-siden Saksliste-rekkefølge Sakstabelle Dokumenttabelle Merkelappetabell Merkelappegruppe-tabell Egendefinert felttabell Medlemsliste Teams-liste Revisjonvelger Objekttabell QTO-tabell Merkelappeorder

## 2. **Unicode-tegnrekkefølge**

For en rask oversikt over Unicode-tegn, se nedenfor:

### 2.1 **1. Mellomrom ( )**

Mellomrom er ofte ikke tillatt som første tegn, men kan brukes i modell- og dokumentdelen. Selv om mellomrom sikrer at dette alltid vil være 100% først på listen, anbefales det ikke da et mellomrom foran et ord kan se forvirrende ut for brukere. Et mellomrom i begynnelsen av et navn kan også føre til problemer da dette ikke er tillatt i Windows.

### 2.2 **2. ASCII-tegnsetting og symboler**

Tegn med halv bredde `!"#%&()*+-/` ! er det andre Unicode-tegnet og er det beste valget hvis du vil være sikker på at listen element vises først på listen.

### 2.3 **3. ASCII-tall**

Tall `0001` Tall sorteres alfanumerisk. Dette betyr at rekkefølgen kan se merkelig ut hvis du har tall med ulik lengde på en liste: 1 10 11 12 2 20 21 22

For å bekjempe dette legger du til 0 foran tall som ikke er veldig lange. 00001 00002 00003 00004 00011 00111 00365 osv. Dette sikrer at tallene dine ender opp i riktig rekkefølge.

### 2.4 **4. ASCII-tegnsetting og symboler**

`<>@`

### 2.5 **5. BOKSTAVER - STORE - HALV BREDDE**

`STORE BOKSTAVER`

### 2.6 **6. ASCII-tegnsetting og symboler**

`[\]_`

### 2.7 **7. bokstaver - små - halv bredde**

`små bokstaver`

### 2.8 **8. ASCII-tegnsetting og symboler**

`{|}~¨´`

### 2.9 **Internasjonale språk**

9\. Europeisk Latin - Store og små bokstaver (ÅÆØß)(âäåæçèéø) 10\. Ikke-europeisk og historisk Latin - Store og små bokstaver (gresk, russisk, arabisk, thai) 11\. CJK-symboler og tegnsetting (「」) 12\. ひらがな (Hiragana) 13\. カタカナ (Katakana - full bredde) 14\. Katakana-symboler (・) 15\. Bopomofo 16\. Hangul Jamo og kompatibilitet Jamo 17\. Kanbun 18\. Lukkede CJK-bokstaver og måneder 19\. Alkymisymboler 20\. Kanji (漢字) 21\. Symboler (／) 22\. ０００１－ｆｕｌｌ－ｗｉｄｔｈ－ｎｕｍｂｅｒｓ 23\. ＬＥＴＴＥＲＳ－ＦＵＬＬ－ＷＩＤＴＨ－ＣＡＰＩＴＡＬ 24.ｌｅｔｔｅｒｓ－ｆｕｌｌ－ｗｉｄｔｈ－ｌｏｗｅｒｃａｓｅ 25\. ｶﾀｶﾅ - (Katakana - halv bredde)
