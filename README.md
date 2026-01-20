# Praha vs. Brno: Srovnání vybraných ukazatelů kvality života

Projekt je vizualizací srovnání dat týkající se tří oblastí života v Praze a Brně, kterými jsou **ceny nemovitostí** s ohledem na příjmy v daném kraji, **životní prostředí** a zdravotní ukazatele v podobě **úmrtnosti a diagnostiky nádorových onemocnění**. Cílem bylo zjistit, zda jsou dvě největší města v ČR v těchto ukazatelích srovnatelná nebo zda existují nějaké významné rozdíly. 




## Datové zdroje

Data byla získána především z [Portálu otevřených dat ČR](https://data.gov.cz/datové-sady). Dalším zdrojem dat byla [Data o Brně](https://data.brno.cz) a [Otevřená data hlavního města Prahy](https://opendata.praha.eu). 


## Datový model

Do modelu bylo zahnuto osm hlavních tabulek a dále několik pomocných: kalendářová tabulka, číselník krajů, číselník věkových skupin a údaje o krajích (počet obyvatel a rozloha). 
![model1](https://github.com/laedazel/powerbi_praha_brno/blob/main/model_all.png)

## Vizualizace v Power BI

První část projektu se zaměřuje na **analýzu cen nemovitostí**. Ceny nemovitostí zůstávají v Praze v průběhu let 2019-2023 stabilně vyšší než v Praze, což platí pro domy i byty. **Index dostupnosti bydlení** však ukazuje, že bydlení je vzhledem k regionální výši mzdy v Praze i Brně přibližně stejně dostupné, což platí při přepočtu na 70 m<sup>2</sup> pro byty i domy, s malým rozdílem pro domy, které jsou v relativním přepočtu o něco levnější v Brně. 

![bydleni](https://github.com/laedazel/powerbi_praha_brno/blob/main/powerbi_bydleni.png)

Druhá část vizualizuje **indikátory emisí a hluku**. Relativně větší plocha Prahy je ve srovnání s Brnem zatížena vysokou hlučností. V Praze je také vyšší zatížení prachovými emisemi, což indikuje vyšší počet překročení emisních limitů na stanicích měřících emise. Ostatní emise jsou při přepočtu na rozlohu kraje vyšší v Jihomoravském kraji, a to zejména Oxid uhelnatý. V průběhu let dochází k poklesu všech druhů emisí.  

![zivotni_prostredi](https://github.com/laedazel/powerbi_praha_brno/blob/main/powerbi_zivotni_prostredi.png)

Poslední část se zaměřuje na srovnání úmrtnosti a stádium nádorového onemocnění v době diagnózy. Pro účely regionálního srovnání byla vytvořena nová míra, která ukazuje **počet úmrtí v Praze a Jihomoravském kraji na nádory** při přepočtu na 100 000 obyvatel.  Úmrtí na nádory v průběhu let klesají s občasnými výkyvy, přičemž v Praze je pokles výraznější. Další ukazatel je **průměrné stádium nemoci v době diagnózy**, tedy zda je nádor odhalen v časné fázi onemocnění. Od roku 1977 je patrné, že dochází k dřívější diagnostice, ke zhoršení došlo v roce 2020 pravděpodobně v souvislosti s pandemií Covid 19. Zatímco do roku 2004 byl nádor v Praze v průměru odhalen dříve než v Jihomoravském kraji, po roce 2004 se trend až do konce sledovaného období v roce 2022 obrací. 

![zdravi](https://github.com/laedazel/powerbi_praha_brno/blob/main/powerbi_zdravi.png)

## Závěr

Analýza a vizualizace zvolených indikátorů ukazuje **poměrně srovnatelné životní podmínky v Praze a Brně**. Ceny nemovitostí jsou sice vyšší v Praze, ale vzhledem k výši mezd je zde bydlení srovnatelně dostupné. Praha je také relativně hlučnější a prašnější, ostatní emise při přepočtu na celý kraj a jeho rozlohu jsou však horší v oblasti Brna. V Brně je nádor odhalen v průměru v nižším stádiu, ale v Praze je přesto nižší úmrtnost na nádorová onemocnění ve srovnání s Jihomoravským krajem. 
