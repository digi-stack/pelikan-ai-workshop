# AI Workshop - Pelikan - Cheat Sheet

## Gemini prompty (gemini.google.com)

### 1. Profesionalny email
```
Si profesionalny asistent zakaznickeho servisu cestovnej kancelarie.
Prepis nasledujuci nestrukturovany email do profesionalnej podoby:
[VLOZ SEM SVOJ EMAIL]
Poziadavky: formalne vykanie, jasna struktura (pozdrav, jadro, akcne body, pozdrav), max 150 slov.
```

### 2. Odpoved na reklamaciu
```
Si skuseny pracovnik zakaznickeho servisu cestovnej kancelarie Pelikan.
Zakaznik poslal nasledujucu staznost:
[VLOZ SEM STAZNOST]
Navrhni profesionalnu odpoved: ospravedlnenie, pochopenie, konkretne riesenie, dalsi postup. Formalne vykanie, empaticky ton, max 200 slov. Nepriznavaj vinu priamo.
```

### 3. Sumarizacia emailov
```
Sumarizuj nasledujuce emailove vlakno:
[VLOZ VLAKNO]
Format: 1. ZHRNUTIE (3-5 viet) 2. KLUCOVE ROZHODNUTIA 3. AKCNE BODY (kto + uloha + termin) 4. OTVORENE OTAZKY
```

### 4. Analyza sentimentu
```
Analyzuj ton spravy od zakaznika:
[VLOZ SPRAVU]
Uved: SENTIMENT, HLAVNA EMOCOA, CO CHCE, URGENCIA, STRATEGIA ODPOVEDE, NAVRH ODPOVEDE (5-7 viet).
```

### 5. Sablony odpovedi
```
Vygeneruj 5 sablon odpovedi na najcastejsie dotazy zakaznikov:
1. Zmena terminu 2. Zrusenie 3. Reklamacia ubytovania 4. Poistenie/dokumenty 5. Meskanie letu
Pre kazdu: predmet + telo (100-150 slov) + [PLACEHOLDER] pre udaje.
```

### 6. Preklad + lokalizacia
```
Preloz text do [JAZYK]. Nie doslovny preklad - kulturna adaptacia. Zachovaj profesionalny ton. Na konci: 1-2 kulturne tipy pre komunikaciu.
```

### 7. Brainstorming
```
Daj 10 napadov na zlepsenie [TEMA]. Pre kazdy: narocnost + prinos. Vyber top 3 + prvy krok implementacie. Kontext: cestovna kancelaria, ZS tym.
```

---

## NotebookLM prompty (notebooklm.google.com)

### 8. Chat so zdrojmi
```
Na zaklade nahratych zdrojov odpovedz: [OTAZKY]. Pre kazdu odpoved cituj konkretnu cast zdroja. Ak informacia nie je v zdrojoch, napis "Informacia nie je v nahratych zdrojoch."
```

### 9. FAQ generovanie
```
Vytvor FAQ (15 otazok) pre zakaznicky servis. Rozdelenie do kategorii (rezervacie, platby, reklamacie, dokumenty). Odpovede max 3 vety. Cituj zdroj. Tabulka: Otazka | Odpoved | Zdroj
```

### 10. Onboarding sprievodca
```
Vytvor onboarding sprievodcu: DEN 1 (pristupy, kontakty), TYZDEN 1 (zakladne procesy), MESIAC 1 (pokrocile + eskalacia), 10 FAQ novacikov, cheat sheet. Cituj zdrojove dokumenty.
```

### 11. Porovnanie dokumentov
```
Porovnaj dokument A (stara verzia) s B (nova verzia). Co sa zmenilo, pridane, odstranene? Ktore zmeny su KRITICKE? Zhrn do 5 bodov pre briefing.
```

### 12. Audio Overview
```
(Customize) Zameraj sa na [TEMA]. Vysvetli to pre noveho zamestnanca. Pouzi konkretne priklady z nahratych smernic. Po slovensky.
```

---

## Gems - system prompt pre reklamacneho asistenta
```
Si profesionalny asistent ZS cestovnej kancelarie Pelikan.
PRAVIDLA: formalne vykanie, empaticky ton, struktura (ospravedlnenie > pochopenie > riesenie > postup), nepriznavaj vinu, neslub co nevies splnit, max 200 slov, po slovensky.
POSTUP: 1. Analyzuj staznost 2. Navrhni odpoved 3. Opytaj sa na upravu.
```

---

## Klucove URL adresy

- **Gemini:** gemini.google.com
- **NotebookLM:** notebooklm.google.com
- **AI Studio:** aistudio.google.com
- **Google Stitch:** stitch.withgoogle.com

## 4 zlate pravidla

1. **Brain dump** - dajte AI co najviac kontextu
2. **Digitalny radca** - AI navrhuje, vy rozhodujete
3. **Expertiza** - vy viete viac o vasej praci
4. **Human in the loop** - vzdy skontrolujte vystup

## Anatomia dobreho promptu

**Rola** + **Kontext** + **Uloha** + **Format** = dobry prompt
