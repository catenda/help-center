# Sorting order of lists

Lists around Catenda are sorted after the unicode values. To find out what letters have which unicode values see [this Wikipedia article](https://en.wikipedia.org/wiki/List_of_Unicode_characters). Click here to read more about typical strategies that are applied to the naming of elements so they end up in the right order.

## 1. **Lists that use this sorting**

Project list Models table Bookmarks page Topic board order Topics table Documents table Label table Label group table Custom field table Members list Teams list Revision selector Objects table QTO table Label order

## 2. **Unicode character order**

For a quick overview of unicode characters see below:

### 2.1 **1. Space ( )**

Space is often not allowed as a first character but can be used in the models and documents section. Although space ensures this will 100% always be the first in the list it is not recommended as a space in front of a word can look confusing to users. A space at the beginning of a name can also lead to problems as this is not allowed in Windows.

### 2.2 **2. ASCII Punctuation & Symbols**

Half-width characters `!"#%&()*+-/` ! is the second unicode character and is the best choice if you want to make sure your list item appears first in the list.

### 2.3 **3. ASCII Digits**

Numbers `0001` Numbers are sorted alphanumerically. This means that the order can look weird if you have numbers of different length in a list: 1 10 11 12 2 20 21 22

To combat this add a 0 in front of numbers that are not very long. 00001 00002 00003 00004 00011 00111 00365 etc. This will ensure your numbers end up in the correct order.

### 2.4 **4. ASCII Punctuation & Symbols**

`<>@`

### 2.5 **5. LETTERS - CAPITAL - HALF WIDTH**

`CAPITAL LETTERS`

### 2.6 **6. ASCII Punctuation & Symbols**

`[\]_`

### 2.7 **7. letters - lowercase - half width**

`lowercase letters`

### 2.8 **8. ASCII Punctuation & Symbols**

`{|}~¨´`

### 2.9 **International languages**

9\. European Latin - Capital then lower (ÅÆØß)(âäåæçèéø) 10\. Non-European & historic Latin - Capital then lower (Greek, Russian, Arabic, Thai) 11\. CJK Symbols and Punctuation (「」) 12\. ひらがな (Hiragana) 13\. カタカナ (Katakana - full width) 14\. Katakana symbols (・) 15\. Bopomofo 16\. Hangul Jamo and Compatibility Jamo 17\. Kanbun 18\. Enclosed CJK Letters and Months 19\. Alchemical symbols 20\. Kanji (漢字) 21\. Symbols (／) 22\. ０００１－ｆｕｌｌ－ｗｉｄｔｈ－ｎｕｍｂｅｒｓ 23\. ＬＥＴＴＥＲＳ－ＦＵＬＬ－ＷＩＤＴＨ－ＣＡＰＩＴＡＬ 24.ｌｅｔｔｅｒｓ－ｆｕｌｌ－ｗｉｄｔｈ－ｌｏｗｅｒｃａｓｅ 25\. ｶﾀｶﾅ - (Katakana - Half width)
