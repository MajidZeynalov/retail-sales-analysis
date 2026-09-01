# retail-sales-analysis
-Retail sales data analysis and interactive dashboard
## Layihə haqqında
-Bu layihədə 25,000+ sətirlik satış datası təmizlənib və analiz edilib.
## Biznes sualları
-Hansı regionlar zəifdir?
-Harda problem var?
## İstifadə olunan alətlər
-Excel: PivotTable, PivotChart, Slicer
-Funksiyalar: VLOOKUP, SUMIFS, IF, IFERROR
-Statistika: AVERAGE, MEDIAN, STDEV, CORREL
## Data təmizləmə
### Tarixlerin temizlenmesi
-tarix formatını tənzizmləmək üçün "/" "." ilə replace vasitəsilə əvəz edirik 236 replecament oldu.
-bir sonraki replacement ise "-" isrelerini "." ile evez etmekdir 258 deyisiklik oldu
### Unit price temizlenmesi
-ilk once datamizin yazisini replace ile duzledirik yeni "." ler "," le evez olunsun 567 deyisiklik oldu
-AZN leri replace ile silirik 178 deyisiklik oldu 
-datamiz hamisi 1 vergulle yazilmalidir lakin aralarinda 2 vergul olanlar var bunu hell etmek ucun butun datadaki vergulleri silib, 100-e boluruk ve istediyimiz neticeni aliriq
### Quantity sutununda menfi deyerlerin musbet edilmesi
-Filterden yalniz menfi ededleri secirik
-ABS funksiyasi ile menfileri musbet edib onlarin yerine copy edirik
### Line total hesablama uygunsuzluqlarinin aradan qaldirilmasi
-quantity*unit price*(1-discount percent) dusturu ile bir daha line total sutununu hesablayib duzgun cavablari aliriq
### Customer ID orphan key probleminin helli
-Vlookup funksiyasi ile customer id cedvelinde olan lakin esas musteriler cedvelinde movcud olmayan musterileri askar etdik
-Bunlarin hamisini silib datamizi temizleyirik 
### City sutununu duzeldilmesi
-Seher adlarini tek yazi formatina salmaq ucun filter, "unique" funksiyasi ve replace istifade edeceyik
### Products sheetde category sutununda yazi sehvlerinin duzeldilmesi
-Category adlarini tek yazi formatina salmaq ucun filter unique funksiyasi ve replace istifade edirik
### Bütün sətir daxil dublikatların silinməsi
-Data bolmesinden butun dublikatlari remove dublicates emri ile temizleyirik
