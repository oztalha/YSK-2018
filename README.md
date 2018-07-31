# YSK-2018

This repo contains Turkish General Election (Presidential and Parliamentary) 2018 ballot box level results scraped from <ysk.gov.tr>.

- Raw files downloaded for all the `1082` precincts are available in zip files `CB-2018.zip` and `MV-2018.zip`.
- There are `180065` ballot boxes in total when `1082` files combined. They are available in `YSK-CB-18.csv` and `YSK-MV-18.csv`
- I also combined the two election results (the total of `2164` raw files) and made it available as a single file.
- `YSK-MVCB-18.csv` contains all results combined (good for any text editor or statistical program other than MS Excel).
- `YSK-MVCB-18-EXCEL.csv` is identical to `YSK-MVCB-18.csv` but encoded in UTF-16 (for MS Excel to show the content fine).

Column descriptions for `YSK-MVCB-18.csv` file:
- **BALLOT BOX IDENTIFIER (USED IN JOINING MV & CB RESULTS*):** İL ADI, İLÇE ADI, MAHALLE/KÖY, SANDIK NO
- **MV RESULTS:** SEÇMEN SAYISI MV, OY KULLANAN SEÇMEN SAYISI MV, İTİRAZSIZ GEÇERLİ OY SAYISI, İTİRAZLI GEÇERLİ OY SAYISI, GEÇERLİ OY TOPLAMI MV, GEÇERSİZ OY TOPLAMI MV, AK PARTİ, MHP, HÜDA PAR, VATAN PARTİSİ, HDP, CHP, SAADET, İYİ PARTİ, CUMHUR İTTİFAKI, MİLLET İTTİFAKI, BAGIMSIZ
- **CB RESULTS:** SEÇMEN SAYISI CB, OY KULLANAN SEÇMEN SAYISI CB, GEÇERLİ OY TOPLAMI CB, GEÇERSİZ OY TOPLAMI CB, MUHARREM İNCE, MERAL AKŞENER, RECEP TAYYİP ERDOĞAN, SELAHATTİN DEMİRTAŞ, TEMEL KARAMOLLAOĞLU, DOĞU PERİNÇEK
