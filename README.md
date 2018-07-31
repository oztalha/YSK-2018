# YSK-2018

This repo contains Turkish General Election (Presidential and Parliamentary) 2018 ballot box level results scraped from <ysk.gov.tr>.

- `CB-2018.zip` and `MV-2018.zip`: All the raw files downloaded (N=`1082` precincts).
- `YSK-CB-18.csv` and `YSK-MV-18.csv`: All of the `180065` ballot boxes (within `1082` precincts) combined.
- `YSK-MVCB-18.csv`: All results combined (contains almost all the info of `2164` raw files; good for any text editor or statistical program other than MS Excel*).

Column descriptions for `YSK-MVCB-18.csv` file:
- **BALLOT BOX IDENTIFIER (USED IN JOINING MV & CB RESULTS*):** İL ADI, İLÇE ADI, MAHALLE/KÖY, SANDIK NO
- **MV RESULTS:** SEÇMEN SAYISI MV, OY KULLANAN SEÇMEN SAYISI MV, İTİRAZSIZ GEÇERLİ OY SAYISI, İTİRAZLI GEÇERLİ OY SAYISI, GEÇERLİ OY TOPLAMI MV, GEÇERSİZ OY TOPLAMI MV, AK PARTİ, MHP, HÜDA PAR, VATAN PARTİSİ, HDP, CHP, SAADET, İYİ PARTİ, CUMHUR İTTİFAKI, MİLLET İTTİFAKI, BAGIMSIZ
- **CB RESULTS:** SEÇMEN SAYISI CB, OY KULLANAN SEÇMEN SAYISI CB, GEÇERLİ OY TOPLAMI CB, GEÇERSİZ OY TOPLAMI CB, MUHARREM İNCE, MERAL AKŞENER, RECEP TAYYİP ERDOĞAN, SELAHATTİN DEMİRTAŞ, TEMEL KARAMOLLAOĞLU, DOĞU PERİNÇEK

*: To make Excel happy, open the CSV file in any text editor other than EXCEL and save as the file in UTF-16 format. Now MS Excel should show the content of that file fine.
