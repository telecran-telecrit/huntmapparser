# Description
[huntmap.ru](https://huntmap.ru/) map parser on Selenium + Google Chrome, layers are arranged in geojson by districts and regions of the country.

* [results.tar.gz](https://github.com/interlark/huntmap-parser/blob/main/result.tar.xz) – saved result (10.04.24)

* [results.tree](https://github.com/interlark/huntmap-parser/blob/main/result.tree) – result directory structure (10.04.24)

# Launch
1. Install [Google Chrome](https://www.google.com/chrome/)
2. ```bash
   git clone https://github.com/interlark/huntmap-parser && cd huntmap-parser
   pip install -r requirements.txt
   python huntmap_parser.py
   ```
# Directory structure

<details>
  <summary>tree</summary>

```
result
├── Far Eastern Federal District
│   ├── Amur Region
│   │   ├── Amur Region border.geojson
│   │   ├── Boundaries of urban districts of AmO.geojson
│   │   ├── Assigned hunting grounds of AmO.geojson
│   │   ├── Zones with hunting restrictions of AmO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal boundaries of AmO.geojson
│   │   ├── Public hunting grounds of the Amur Region.geojson
│   │   ├── Protected areas of the Amur Region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Jewish Autonomous Region
│   │   ├── Border of the Jewish Autonomous Region.geojson
│   │   ├── Borders of urban districts of the Jewish Autonomous Region.geojson
│   │   ├── Assigned hunting hunting grounds of the Jewish Autonomous Region.geojson
│   │   ├── Hunting restrictions zones of the Jewish Autonomous Region.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of the Jewish Autonomous Region.geojson
│   │   ├── Public hunting grounds of the Jewish Autonomous Region.geojson
│   │   ├── Protected areas of the Jewish Autonomous Region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases Russia.geojson
│   ├── Zabaikalsky Krai
│   │   ├── Border of Zabaikalsky Krai.geojson
│   │   ├── Borders of settlements ZK.geojson
│   │   ├── Assigned hunting grounds ZK.geojson
│   │   ├── Zones with hunting restrictions ZK.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of ZK.geojson
│   │   ├── Public hunting grounds ZK.geojson
│   │   ├── Protected areas of Zabaikalsky Krai.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Kamchatka Krai
│   │   ├── Border of Kamchatka Krai.geojson
│   │   ├── Borders of urban districts of KamK.geojson
│   │   ├── Assigned hunting grounds KamK.geojson
│   │   ├── Zones with hunting restrictions KamK.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts KamK.geojson
│   │   ├── Public hunting grounds KamK.geojson
│   │   ├── Protected areas of Kamchatka Krai.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases Russia.geojson
│   ├── Magadan Region
│   │   ├── Magadan Region Border.geojson
│   │   ├── Assigned Hunting Grounds MagO.geojson
│   │   ├── Hunting Restriction Zones MagO.geojson
│   │   ├── Forestries MagO.geojson
│   │   ├── Paid Fishing Spots in Russia.geojson
│   │   ├── Municipal Districts MagO.geojson
│   │   ├── Public hunting grounds MagO.geojson
│   │   ├── Protected areas of Magadan region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Primorsky Krai
│   │   ├── Boundaries of urban districts of PrimK.geojson
│   │   ├── Boundaries of Primorsky Krai.geojson
│   │   ├── Assigned hunting grounds of PrimK.geojson
│   │   ├── Zones with hunting restrictions PrimK.geojson
│   │   ├── Forestries PrimK.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts PrimK.geojson
│   │   ├── Public hunting grounds PrimK.geojson
│   │   ├── Protected areas of Primorsky Krai.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Republic of Buryatia
│   │   ├── Border of the Republic of Buryatia.geojson
│   │   ├── Assigned hunting grounds of the Republic of Buryatia.geojson
│   │   ├── Zones with hunting restrictions of the Republic of Buryatia.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of the Republic of Buryatia.geojson
│   │   ├── Settlements RBU.geojson
│   │   ├── Public hunting grounds RBU.geojson
│   │   ├── Protected areas of the Republic of Buryatia.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Sakha Republic (Yakutia)
│   │   ├── Border of the Sakha Republic (Yakutia).geojson
│   │   ├── Assigned hunting grounds of YAN.geojson
│   │   ├── Zones with hunting restrictions YAN.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of YAN.geojson
│   │   ├── Public hunting grounds of YAN.geojson
│   │   ├── Protected areas of the Republic of Sakha (Yakutia).geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Sakhalin Oblast
│   │   ├── Sakhalin Oblast border.geojson
│   │   ├── Assigned hunting grounds of Sakha Oblast.geojson
│   │   ├── Restricted hunting zones of Sakha Oblast.geojson
│   │   ├── Fee-based fishing in Russia.geojson
│   │   ├── Municipal borders of Sakhalin Oblast.geojson
│   │   ├── Public hunting grounds of Sakhalin Oblast.geojson
│   │   ├── Protected areas of Sakhalin Oblast.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Khabarovsk Krai
│   │   ├── Border of Khabarovsk Krai.geojson
│   │   ├── Boundaries of urban districts of Khabarovsk.geojson
│   │   ├── Assigned hunting grounds of Khabarovsk.geojson
│   │   ├── Green zones of forests.geojson
│   │   ├── Zones with hunting restrictions of Khabarovsk.geojson
│   │   ├── Block network of Khabarovsk (zoom 11) .geojson
│   │   ├── Forestries of Khabarovsk.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts Khabarovsk.geojson
│   │   ├── Settlements Khabarovsk.geojson
│   │   ├── Public hunting grounds Khabarovsk.geojson
│   │   ├── Protected areas of Khabarovsk Krai.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   ├── Territories of traditional nature management.geojson
│   │   └── Tourist bases of Russia.geojson
│   └── Chukotka autonomous okrug
│   ├── Border of Chukotka Autonomous Okrug.geojson
│   ├── Assigned hunting grounds of Chukotka Autonomous Okrug.geojson
│   ├── Zones with hunting restrictions of Chukotka Autonomous Okrug.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts of Chukotka Autonomous Okrug.geojson
│   ├── Public hunting grounds of Chukotka Autonomous Okrug.geojson
│   ├── Protected areas of Chukotka Autonomous Okrug.geojson
│   ├── Hunting and fishing bases Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Volga Federal District
│   ├── Kirov Oblast
│   │   ├── Kirov Oblast border.geojson
│   │   ├── Borders of urban districts KO.geojson
│   │   ├── Assigned hunting grounds KO.geojson
│   │   ├── Zones with hunting restrictions KO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of KO.geojson
│   │   ├── Public hunting grounds of KO.geojson
│   │   ├── Protected areas of Kirov region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Nizhny Novgorod region
│   │   ├── Border of Nizhny Novgorod region.geojson
│   │   ├── Assigned hunting grounds НО.geojson
│   │   ├── Zones with hunting restrictions НО.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts НО.geojson
│   │   ├── Public hunting grounds НО.geojson
│   │   ├── Protected areas of the Nizhny Novgorod region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases Russia.geojson
│   ├── Orenburg Region
│   │   ├── Orenburg Region border.geojson
│   │   ├── Orenburg Region urban district borders.geojson
│   │   ├── Assigned hunting grounds OrO.geojson
│   │   ├── Hunting restricted areas OrO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── OrO municipal districts.geojson
│   │   ├── Public hunting grounds of OrO.geojson
│   │   ├── Protected areas of the Orenburg region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Penza region
│   │   ├── Penza region border.geojson
│   │   ├── Assigned hunting grounds of PenzO.geojson
│   │   ├── Zones with hunting restrictions PenzO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of PenzO.geojson
│   │   ├── Public hunting grounds of PenzO.geojson
│   │   ├── Protected areas of Penza Oblast.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Perm Krai
│   │   ├── Perm Krai border.geojson
│   │   ├── Assigned hunting grounds PeK.geojson
│   │   ├── Zones with hunting restrictions PeK.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts PeK.geojson
│   │   ├── Public hunting grounds PeK.geojson
│   │   ├── Protected areas of Perm Krai.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson

│   ├── Republic of Bashkortostan
│   │   ├── Border of the Republic of Bashkortostan.geojson
│   │   ├── Borders of urban districts of the Republic of Bashkortostan.geojson
│   │   ├── Borders of forestries.geojson
│   │   ├── Assigned hunting grounds of the Republic of Bashkortostan.geojson
│   │   ├── Spring hunting zones of the Republic of Bashkortostan.geojson
│   │   ├── Zones with hunting restrictions of the Republic of Bashkortostan.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of the Republic of Bashkortostan.geojson
│   │   ├── Public hunting grounds of the Republic of Bashkortostan.geojson
│   │   ├── Protected areas and natural monuments of Bashkortostan.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Republic of Mari El
│   │   ├── Border of the Republic of Mari El.geojson
│   │   ├── Boundaries of urban districts of the Republic of Mari El.geojson
│   │   ├── Assigned hunting grounds of the Republic of Mari El.geojson
│   │   ├── Green zones of forests of the Republic of Mari El.geojson
│   │   ├── Zones with hunting restrictions of the Republic of Mari El.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of the Republic of Mari El.geojson
│   │   ├── Public hunting grounds of the Republic of Mari El.geojson
│   │   ├── Protected areas of the Republic of Mari El.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Republic of Mordovia
│   │   ├── Border of the Republic of Mordovia.geojson
│   │   ├── Borders of urban districts of the Republic of Mordovia.geojson
│   │   ├── Assigned hunting grounds of the Republic of Mordovia.geojson
│   │   ├── Green zones of forests RMor.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of RMor.geojson
│   │   ├── Public hunting grounds of RMor.geojson
│   │   ├── Protected areas of the Republic of Mordovia.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Republic of Tatarstan
│   │   ├── Border of the Republic of Tatarstan.geojson
│   │   ├── Assigned hunting grounds of the Republic of Tatarstan.geojson
│   │   ├── Zones with hunting restrictions of the Republic of Tatarstan.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of the Republic of Tatarstan.geojson
│   │   ├── Public hunting grounds of the Republic of Tatarstan.geojson
│   │   ├── Protected areas of the Republic of Tatarstan.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Samara region
│   │   ├── Samara region border.geojson
│   │   ├── Borders of urban districts of SO.geojson
│   │   ├── Assigned hunting grounds of SO.geojson
│   │   ├── Zones with hunting restrictions of SO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of SO.geojson
│   │   ├── Public hunting grounds of SO.geojson
│   │   ├── Protected areas of Samara region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Saratov region
│   │   ├── Border of Saratov region.geojson
│   │   ├── Borders of settlements of SarO.geojson
│   │   ├── Assigned hunting grounds SarO.geojson
│   │   ├── Zones with hunting restrictions SarO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds SarO.geojson
│   │   ├── Protected areas of the Saratov region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Udmurt Republic
│   │   ├── Border of the Udmurt Republic.geojson
│   │   ├── Borders of urban districts UR.geojson
│   │   ├── Fixed hunting grounds UR.geojson
│   │   ├── Green forest zones UR.geojson
│   │   ├── Zones with hunting restrictions UR.geojson
│   │   ├── Paid fishing places in Russia.geojson
│   │   ├── Municipal areas UR.geojson
│   │   ├── Public hunting grounds UR.geojson
│   │   ├── Protected areas of the Udmurt Republic.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Ulyanovsk Region
│   │   ├── Ulyanovsk Region border.geojson
│   │   ├── Assigned hunting grounds UlO.geojson
│   │   ├── Zones with hunting restrictions UlO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts UlO.geojson
│   │   ├── Public hunting grounds UlO.geojson
│   │   ├── Protected areas of the Ulyanovsk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   └── Chuvash Republic
│   ├── Border of the Chuvash Republic.geojson
│   ├── Assigned hunting grounds of the Chechen Republic.geojson
│   ├── Green zones of the forests of the Chechen Republic.geojson
│   ├── Dog training and training zones.geojson
│   ├── Hunting restricted areas.geojson
│   ├── Forest park zones of the forests of the Chechen Republic.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts of the Chechen Republic.geojson
│   ├── Settlements of the Chechen Republic 2022.geojson
│   ├── Public hunting grounds of the Chechen Republic.geojson
│   ├── Protected areas of the Chuvash Republic.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   ├── Highway M-12.geojson
│   └── Tourist bases of Russia.geojson
├── Northwestern Federal District
│   ├── Arkhangelsk Region
│   │   ├── Arkhangelsk Region border.geojson
│   │   ├── Assigned hunting grounds ArkhO.geojson
│   │   ├── Hunting restrictions zones ArkhO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts ArkhO.geojson
│   │   ├── Public hunting grounds ArkhO.geojson
│   │   ├── Protected areas of the Arkhangelsk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Vologda region
│   │   ├── Vologda region border.geojson
│   │   ├── Vologda forestry borders.geojson
│   │   ├── Assigned hunting grounds Vologda.geojson
│   │   ├── Zones with hunting restrictions Vologda.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts Vologda.geojson
│   │   ├── Public hunting grounds Vologda.geojson
│   │   ├── Protected areas of the Vologda region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Kaliningrad region
│   │   ├── Border of Kaliningrad region.geojson
│   │   ├── Assigned hunting grounds of KaliO.geojson
│   │   ├── Zones with hunting restrictions of KaliO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of KaliO.geojson
│   │   ├── Public hunting grounds of KaliO.geojson
│   │   ├── Protected areas of Kaliningrad Oblast.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Leningrad Oblast
│   │   ├── Leningrad Oblast border.geojson
│   │   ├── Leningrad Oblast settlements borders.geojson
│   │   ├── Leningrad Oblast assigned hunting grounds.geojson
│   │   ├── ├── Zones with restricted hunting in Leningrad Oblast.geojson
│   │   ├── Forestries in Leningrad Oblast.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Leningrad Oblast.geojson
│   │   ├── Public hunting grounds in Leningrad Oblast.geojson
│   │   ├── Protected areas of Leningrad Oblast.geojson
│   │   ├── Hunting and fishing bases in Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Murmansk region
│   │   ├── Border of Murmansk region.geojson
│   │   ├── Borders of closed urban districts MurO.geojson
│   │   ├── Assigned hunting grounds MurO.geojson
│   │   ├── Zones with hunting restrictions MurO.geojson
│   │   ├── Forestries MurO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of MurO.geojson
│   │   ├── Public hunting grounds of MurO.geojson
│   │   ├── Protected areas of the Murmansk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   ├── Tourist bases of Russia.geojson
│   │   └── District forestries of MurO (zoom 10).geojson
│   ├── Nenets Autonomous Okrug
│   │   ├── NAO border.geojson
│   │   ├── Assigned hunting grounds of NAO.geojson
│   │   ├── Zones with hunting restrictions of NAO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds of NAO.geojson
│   │   ├── Protected areas of Nenets Autonomous Okrug.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Novgorod region
│   │   ├── Novgorod region border.geojson
│   │   ├── Assigned hunting grounds of Novo.geojson
│   │   ├── Zones with hunting restrictions Novo.geojson
│   │   ├── Forestries of Novo.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Novo.geojson
│   │   ├── Public hunting grounds of Novo.geojson
│   │   ├── Protected areas of Novgorod region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Pskov region
│   │   ├── Border of Pskov region.geojson
│   │   ├── Forestry boundaries of Pskov Oblast.geojson
│   │   ├── Assigned hunting grounds of Pskov Oblast.geojson
│   │   ├── Hunting restrictions zones of Pskov Oblast.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds of Pskov Oblast.geojson
│   │   ├── Protected areas of Pskov Oblast.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Republic of Karelia
│   │   ├── Border of the Republic of Karelia.geojson
│   │   ├── Borders of forestries of Karelia.geojson
│   │   ├── Assigned hunting grounds of the RK.geojson
│   │   ├── Zones with hunting restrictions of the RK.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds РК.geojson
│   │   ├── Protected areas of the Republic of Karelia.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   └── Komi Republic
│   ├── Urban districts of Kemerovo region.geojson
│   ├── Border of the Komi Republic.geojson
│   ├── Borders of Komi forestries.geojson
│   ├── Assigned hunting grounds of Komi.geojson
│   ├── Zones with hunting restrictions Komi.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts of Komi.geojson
│   ├── Public hunting grounds of Komi.geojson
│   ├── Protected areas of the Komi Republic.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Siberian Federal District
│   ├── Altai Krai
│   │   ├── Altai Krai border.geojson
│   │   ├── AlK urban district borders.geojson
│   │   ├── Assigned hunting grounds AlK.geojson
│   │   ├── Hunting restricted areas AlK.geojson
│   │   ├── AlK forestries.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── AlK municipal districts.geojson
│   │   ├── Public hunting grounds of AlK.geojson
│   │   ├── Protected areas of Altai Krai.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   ├── Tourist bases of Russia.geojson
│   │   └── District forestries of AlK (zoom 10).geojson
│   ├── Irkutsk region
│   │   ├── Border of Irkutsk region.geojson
│   │   ├── Borders of urban districts of IrkO.geojson
│   │   ├── Assigned hunting grounds IrkO.geojson
│   │   ├── Zones with hunting restrictions IrkO.geojson
│   │   ├── Forestries IrkO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts IrkO.geojson
│   │   ├── Public hunting grounds IrkO.geojson
│   │   ├── Protected areas of the Irkutsk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Kemerovo region
│   │   ├── Urban districts of Kemerovo region.geojson
│   │   ├── Border of Kemerovo region.geojson
│   │   ├── Assigned hunting grounds of KemO.geojson
│   │   ├── Zones with hunting restrictions of KemO.geojson
│   │   ├── Forest park zones of forests KemO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of KemO.geojson
│   │   ├── Public hunting grounds of KemO.geojson
│   │   ├── Protected areas of Kemerovo region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Krasnoyarsk Krai
│   │   ├── Urban districts of KraK.geojson
│   │   ├── Border of Krasnoyarsk Krai.geojson
│   │   ├── Assigned hunting grounds - Far North.geojson
│   │   ├── Assigned hunting grounds - North.geojson
│   │   ├── Assigned hunting grounds - Center.geojson
│   │   ├── Assigned hunting grounds - South.geojson
│   │   ├── Green zones of forests KraK.geojson
│   │   ├── Zones with hunting restrictions KraK.geojson
│   │   ├── Forestries KraK.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds KraK.geojson
│   │   ├── Protected areas of Krasnoyarsk Krai.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Novosibirsk region
│   │   ├── Border of Novosibirsk region.geojson
│   │   ├── Assigned hunting grounds of NSO.geojson
│   │   ├── Zones with hunting restrictions of NSO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of NSO.geojson
│   │   ├── Public hunting grounds NSO.geojson
│   │   ├── Protected areas of Novosibirsk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Omsk region
│   │   ├── Border of Omsk region.geojson
│   │   ├── Assigned hunting grounds of Omsk.geojson
│   │   ├── Zones with hunting restrictions of Omsk.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal borders of Omsk.geojson
│   │   ├── Public hunting grounds of Omsk.geojson
│   │   ├── Protected areas of Omsk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Altai Republic
│   │   ├── Border of the Altai Republic.geojson
│   │   ├── Assigned hunting grounds ResAl.geojson
│   │   ├── Zones with hunting restrictions ResAl.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts ResAl.geojson
│   │   ├── Public hunting grounds ResAl.geojson
│   │   ├── Protected areas of the Altai Republic.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Republic of Tuva
│   │   ├── Border of the Republic of Tuva.geojson
│   │   ├── Assigned hunting grounds Tuva.geojson
│   │   ├── Zones with hunting restrictions Tuva.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Tuva.geojson
│   │   ├── Public hunting grounds Tuva.geojson
│   │   ├── Protected areas of the Republic of Tuva.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Republic of Khakassia
│   │   ├── Border of the Republic of Khakassia.geojson
│   │   ├── Borders of settlements of the Republic of Khakassia.geojson
│   │   ├── Assigned hunting grounds of the Republic of Khakassia.geojson
│   │   ├── Fee places fishing in Russia.geojson
│   │   ├── Municipal districts of the Republic of Khakassia.geojson
│   │   ├── Public hunting grounds of the Republic of Khakassia.geojson
│   │   ├── Protected areas of the Republic of Khakassia.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   └── Tomsk region
│   ├── Administrative districts of TomO.geojson
│   ├── Border of Tomsk regions.geojson
│   ├── Assigned hunting grounds TomO.geojson
│   ├── Zones with hunting restrictions TomO.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Settlements of Tomsk Oblast.geojson
│   ├── Public hunting grounds TomO.geojson
│   ├── Protected areas of Tomsk Oblast.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   ├── Natural monuments of Tomsk regions.geojson
│   └── Tourist bases of Russia.geojson

├── Ural Federal District
│   ├── Kurgan Oblast
│   │   ├── Kurgan Oblast border.geojson
│   │   ├── Assigned hunting grounds KurganO.geojson
│   │   ├── Hunting restrictions zones KurganO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds KurganO.geojson
│   │   ├── Protected areas of Kurgan regions.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Sverdlovsk region
│   │   ├── Border of Sverdlovsk region.geojson
│   │   ├── Assigned hunting grounds of Sverdlovsk region.geojson
│   │   ├── Zones with hunting restrictions of Sverdlovsk region.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Sverdlovsk Oblast.geojson
│   │   ├── Public hunting grounds of Sverdlovsk Oblast.geojson
│   │   ├── Protected areas of Sverdlovsk Oblast.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Tyumen Oblast
│   │   ├── Border of Tyumen Oblast.geojson
│   │   ├── Assigned hunting grounds TyumO.geojson
│   │   ├── Hunting restricted areas TyumO.geojson
│   │   ├── Forest park belt TyumO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal boundaries TyumO.geojson
│   │   ├── Public hunting grounds TyumO.geojson
│   │   ├── Protected areas of Tyumen Oblast.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Khanty-Mansi Autonomous Okrug - Yugra
│   │   ├── Khanty-Mansi Autonomous Okrug-Yugra border.geojson
│   │   ├── Khanty-Mansi Autonomous Okrug-Yugra border.geojson
│   │   ├── Khanty-Mansi Autonomous Okrug urban district borders.geojson
│   │   ├── Khanty-Mansi Autonomous Okrug hunting grounds.geojson
│   │   ├── Khanty-Mansi Autonomous Okrug hunting restrictions zones.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Khanty-Mansiysk Autonomous Okrug-Yugra.geojson
│   │   ├── Public hunting grounds of Khanty-Mansiysk Autonomous Okrug.geojson
│   │   ├── Protected areas of Khanty-Mansiysk Autonomous Okrug-Yugra.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Chelyabinsk region
│   │   ├── Border of Chelyabinsk region.geojson
│   │   ├── Assigned hunting grounds of the Chelyabinsk Region.geojson
│   │   ├── Zones with hunting restrictions of the Chelyabinsk Region.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of the Chelyabinsk Region.geojson
│   │   ├── Public hunting grounds of the Chelyabinsk Region.geojson
│   │   ├── Protected areas of the Chelyabinsk Region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   └── Yamalo-Nenets Autonomous Okrug
│   ├── Border of Yamalo-Nenets Autonomous Okrug.geojson
│   ├── Assigned hunting grounds of Yamalo-Nenets Autonomous Okrug.geojson
│   ├── Zones with hunting restrictions of Yamalo-Nenets Autonomous Okrug.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts of Yamalo-Nenets Autonomous Okrug.geojson
│   ├── Public hunting grounds of Yamalo-Nenets Autonomous Okrug.geojson
│   ├── Protected areas of the Yamalo-Nenets Autonomous Okrug.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Central Federal District
│   ├── Belgorod Oblast
│   │   ├── Belgorod Oblast border.geojson
│   │   ├── Belgorod Oblast urban district borders.geojson
│   │   ├── Assigned hunting grounds of Belgorod Oblast.geojson
│   │   ├── Hunting restricted areas Belgorod.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Belgorod.geojson
│   │   ├── Public hunting grounds of Belgorod.geojson
│   │   ├── Protected areas of Belgorod region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Bryansk region
│   │   ├── Bryansk region border.geojson
│   │   ├── Bryansk city district borders.geojson
│   │   ├── Bryansk hunting grounds assigned.geojson
│   │   ├── Bryansk hunting restricted areas.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Bryansk municipal districts.geojson
│   │   ├── Bryansk public hunting grounds.geojson
│   │   ├── Protected areas of Bryansk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Vladimir region
│   │   ├── Vladimir region border.geojson
│   │   ├── Assigned hunting grounds of VO.geojson
│   │   ├── Zones with hunting restrictions VO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of the VO.geojson
│   │   ├── Public hunting grounds of the VO.geojson
│   │   ├── Protected areas of the Vladimir region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Voronezh region
│   │   ├── Border of the Voronezh region.geojson
│   │   ├── Borders urban districts VorO.geojson
│   │   ├── Assigned hunting grounds VorO.geojson
│   │   ├── Zones with hunting restrictions VorO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts VorO.geojson
│   │   ├── Public hunting grounds VorO.geojson
│   │   ├── Protected areas of the Voronezh region.geojson
│   │   ├── Hunting and fishing
│   ├── Kaluga Region
│   │   ├── Kaluga Region Border.geojson
│   │   ├── Assigned Hunting Grounds KaO.geojson
│   │   ├── Green Forest Zones KaO.geojson
│   │   ├── Restricted Hunting Zones KaO.geojson
│   │   ├── Paid Fishing Spots in Russia.geojson
│   │   ├── Municipal Districts KaO.geojson
│   │   ├── Settlements of Kao.geojson
│   │   ├── Public hunting grounds of Kao.geojson
│   │   ├── Protected areas of Kaluga region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Kostroma region
│   │   ├── Border of Kostroma region.geojson
│   │   ├── Borders of KostO cities.geojson
│   │   ├── Assigned hunting grounds KostO.geojson
│   │   ├── Zones with hunting restrictions KostO.geojson
│   │   ├── Forestries KostO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds KostO.geojson
│   │   ├── Protected areas of Kostroma region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Kursk region
│   │   ├── Administrative boundaries of KurO.geojson
│   │   ├── Kursk region border.geojson
│   │   ├── Assigned hunting grounds of KurO.geojson
│   │   ├── Zones with hunting restrictions of KurO.geojson
│   │   ├── Forest park zones of KurO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Settlements of KurO.geojson
│   │   ├── Public hunting grounds of KurO.geojson
│   │   ├── Protected areas of Kursk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Lipetsk region
│   │   ├── Border of Lipetsk region.geojson
│   │   ├── Borders of settlements of LipO.geojson
│   │   ├── Assigned hunting grounds LipO.geojson
│   │   ├── Zones with hunting restrictions LipO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts LipO.geojson
│   │   ├── Public hunting grounds LipO.geojson
│   │   ├── Protected areas of Lipetsk region.geojson
│   │   ├── Hunting and fishing bases Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Moscow region
│   │   ├── Moscow region border.geojson
│   │   ├── Moscow region border.geojson
│   │   ├── Moscow region urban district borders.geojson
│   │   ├── Hunting grounds assigned to MO.geojson
│   │   ├── Hunting restricted areas MO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Moscow region.geojson
│   │   ├── Public hunting grounds of Moscow region.geojson
│   │   ├── Protected areas of Moscow region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Oryol region
│   │   ├── Oryol region border.geojson
│   │   ├── Oryol region border.geojson
│   │   ├── Oryol city districts borders.geojson
│   │   ├── Assigned hunting grounds OrlO.geojson
│   │   ├── Zones with hunting restrictions OrlO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts OrlO.geojson
│   │   ├── Public hunting grounds OrlO.geojson
│   │   ├── Protected areas of the Oryol region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Ryazan region
│   │   ├── Border of Ryazan region.geojson
│   │   ├── Borders of urban districts of RyazO.geojson
│   │   ├── Assigned hunting grounds of RyazO.geojson
│   │   ├── Zones with hunting restrictions of RyazO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Public hunting grounds RyazO.geojson
│   │   ├── Protected areas of the Ryazan region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Smolensk region
│   │   ├── Border of the Smolensk region.geojson
│   │   ├── Borders of urban districts of SmolO.geojson
│   │   ├── Assigned hunting grounds of SmolO.geojson
│   │   ├── Zones with hunting restrictions SmolO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts SmolO.geojson
│   │   ├── Public hunting grounds SmolO.geojson
│   │   ├── Protected areas of the Smolensk region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Tambov Oblast
│   │   ├── Tambov Oblast border.geojson
│   │   ├── Tambov Oblast urban district borders.geojson
│   │   ├── Tambov Oblast hunting grounds assigned.geojson
│   │   ├── Tambov Oblast hunting restricted areas.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Tambov Oblast municipal districts.geojson
│   │   ├── Public hunting grounds TambO.geojson
│   │   ├── Protected areas of Tambov region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Tver Oblast
│   │   ├── Tver Oblast border.geojson
│   │   ├── Assigned hunting grounds TvO.geojson
│   │   ├── Zones with hunting restrictions TvO.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts TvO.geojson
│   │   ├── Public hunting grounds TvO.geojson
│   │   ├── Protected areas of Tver region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   ├── Tula region
│   │   ├── Border of Tula region.geojson
│   │   ├── Assigned hunting grounds of Tula.geojson
│   │   ├── Zones with hunting restrictions of Tula.geojson
│   │   ├── Paid fishing spots in Russia.geojson
│   │   ├── Municipal districts of Tula.geojson
│   │   ├── Public hunting grounds of Tula.geojson
│   │   ├── Protected areas of Tula region.geojson
│   │   ├── Hunting and fishing bases of Russia.geojson
│   │   └── Tourist bases of Russia.geojson
│   └── Yaroslavl region
│   ├── Border of Yaroslavl region.geojson
│   ├── Assigned hunting hunting grounds of Yaroslavl.geojson
│   ├── Restricted hunting zones of Yaroslavl.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts of Yaroslavl.geojson
│   ├── Public hunting grounds of Yaroslavl.geojson
│   ├── Protected areas of Yaroslavl region.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
└── Southern Federal District
├── Astrakhan region
│   ├── Astrakhan region border.geojson
│   ├── Assigned hunting grounds AcO.geojson
│   ├── Zones with hunting restrictions AcO.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts AcO.geojson
│   ├── Public hunting grounds AcO.geojson
│   ├── Protected areas of the Astrakhan region.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Volgograd region
│   ├── Volgograd region border.geojson
│   ├── Volgograd region urban district borders.geojson
│   ├── Assigned hunting grounds of Volgograd.geojson
│   ├── Hunting restrictions zones of Volgograd.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Public hunting grounds of Volgograd.geojson
│   ├── Protected areas of Volgograd region.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Krasnodar region
│   ├── Border of Krasnodar region.geojson
│   ├── Borders of urban districts of KraK.geojson
│   ├── Assigned hunting grounds of KraK.geojson
│   ├── Zones with hunting restrictions of KraK.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts of Krak.geojson
│   ├── Public hunting grounds of Krak.geojson
│   ├── Protected areas of Krasnodar Krai.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Republic of Adygea
│   ├── Border of the Republic of Adygea.geojson
│   ├── Borders of settlements of ResAd.geojson
│   ├── Assigned hunting grounds ResAd.geojson
│   ├── Zones with hunting restrictions RAd.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts ResAd.geojson
│   ├── Public hunting grounds ResAd.geojson
│   ├── Protected areas of the Republic of Adygea.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Republic of Kalmykia
│   ├── Border of the Republic of Kalmykia.geojson
│   ├── Assigned hunting grounds of the Republic of Kalmykia.geojson
│   ├── Zones with hunting restrictions of the Republic of Kalmykia.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts of the Republic of Kalmykia.geojson
│   ├── Public hunting grounds of the Republic of Kalmykia.geojson
│   ├── Protected areas of the Republic of Kalmykia.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
├── Republic of Crimea
│   ├── Border of the Republic of Crimea.geojson
│   ├── Borders of settlements ReKr.geojson
│   ├── Assigned hunting grounds ReKr.geojson
│   ├── Zones with hunting restrictions ReKr.geojson
│   ├── Paid fishing spots in Russia.geojson
│   ├── Municipal districts ReKr.geojson
│   ├── Public hunting grounds ReKr.geojson
│   ├── Protected areas of the Republic of Crimea.geojson
│   ├── Hunting and fishing bases of Russia.geojson
│   └── Tourist bases of Russia.geojson
└── Rostov region
├── Border of Rostov region.geojson
├── Borders of urban districts RO.geojson
├── Assigned hunting grounds RO.geojson
├── Zones with hunting restrictions RO.geojson
├── Fee-based fishing in Russia.geojson
├── Municipal districts of RO.geojson
├── Public hunting grounds of RO.geojson
├── Protected areas of Rostov region.geojson
├── Hunting and fishing bases of Russia.geojson
└── Tourist bases of Russia.geojson

82 directories, 746 files
```
</details>
