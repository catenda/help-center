# Sortierreihenfolge von Listen

Listen in Catenda werden nach Unicode-Werten sortiert. Um zu erfahren, welche Buchstaben welche Unicode-Werte haben, siehe [diesen Wikipedia-Artikel](https://en.wikipedia.org/wiki/List_of_Unicode_characters). Klicken Sie hier, um mehr über typische Strategien zu erfahren, die beim Benennen von Elementen angewendet werden, damit sie in der richtigen Reihenfolge angezeigt werden.

## 1. **Listen, die diese Sortierung verwenden**

Projektliste Modelle-Tabelle Lesezeichen-Seite Themen-Board-Reihenfolge Themen-Tabelle Dokumente-Tabelle Etiketten-Tabelle Etiketten-Gruppentabelle Benutzerdefinierte Felder-Tabelle Mitgliederliste Teams-Liste Revisions-Selektor Objekte-Tabelle QTO-Tabelle Etiketten-Reihenfolge

## 2. **Unicode-Zeichenreihenfolge**

Für einen schnellen Überblick über Unicode-Zeichen siehe unten:

### 2.1 **1. Leerzeichen ( )**

Leerzeichen ist oft nicht als erstes Zeichen zulässig, kann aber in den Modellen und Dokumente-Abschnitten verwendet werden. Obwohl ein Leerzeichen garantiert, dass dies zu 100% immer an erster Stelle in der Liste steht, wird es nicht empfohlen, da ein Leerzeichen vor einem Wort für Benutzer verwirrend aussehen kann. Ein Leerzeichen am Anfang eines Namens kann auch zu Problemen führen, da dies in Windows nicht zulässig ist.

### 2.2 **2. ASCII-Interpunktion & Symbole**

Halbbreite Zeichen `!"#%&()*+-/` ! ist das zweite Unicode-Zeichen und die beste Wahl, wenn Sie sicherstellen möchten, dass Ihr Listenelement zuerst in der Liste angezeigt wird.

### 2.3 **3. ASCII-Ziffern**

Zahlen `0001` Zahlen werden alphanumerisch sortiert. Dies bedeutet, dass die Reihenfolge seltsam aussehen kann, wenn Sie Zahlen unterschiedlicher Länge in einer Liste haben: 1 10 11 12 2 20 21 22

Um dies zu vermeiden, fügen Sie vor Zahlen, die nicht sehr lang sind, eine 0 ein. 00001 00002 00003 00004 00011 00111 00365 usw. Dies stellt sicher, dass Ihre Zahlen in der richtigen Reihenfolge enden.

### 2.4 **4. ASCII-Interpunktion & Symbole**

`<>@`

### 2.5 **5. BUCHSTABEN - GROSSBUCHSTABEN - HALBBREITE**

`GROSSBUCHSTABEN`

### 2.6 **6. ASCII-Interpunktion & Symbole**

`[\]_`

### 2.7 **7. Buchstaben - Kleinbuchstaben - Halbbreite**

`Kleinbuchstaben`

### 2.8 **8. ASCII-Interpunktion & Symbole**

`{|}~¨´`

### 2.9 **Internationale Sprachen**

9\. Europäisches Latein - Großbuchstaben dann Klein (ÅÆØß)(âäåæçèéø) 10\. Nicht-europäisches & historisches Latein - Großbuchstaben dann Klein (Griechisch, Russisch, Arabisch, Thai) 11\. CJK-Symbole und Interpunktion (「」) 12\. ひらがな (Hiragana) 13\. カタカナ (Katakana - Vollbreite) 14\. Katakana-Symbole (・) 15\. Bopomofo 16\. Hangul Jamo und Kompatibilität Jamo 17\. Kanbun 18\. Eingeschlossene CJK-Buchstaben und Monate 19\. Alchemische Symbole 20\. Kanji (漢字) 21\. Symbole (／) 22\. ０００１－ｆｕｌｌ－ｗｉｄｔｈ－ｎｕｍｂｅｒｓ 23\. ＬＥＴＴＥＲＳ－ＦＵＬＬ－ＷＩＤＴＨ－ＣＡＰＩＴＡＬ 24.ｌｅｔｔｅｒｓ－ｆｕｌｌ－ｗｉｄｔｈ－ｌｏｗｅｒｃａｓｅ 25\. ｶﾀｶﾅ - (Katakana - Halbbreite)
