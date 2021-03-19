# OpenStreetMap Promotional Leaflets

![photo](https://raw.github.com/osm-ba/openstreetmap-promotional-leaflets-bih/master/leaflets.jpg)

![photo](https://raw.github.com/osm-ba/openstreetmap-promotional-leaflets-bih/master/leaflets2.jpg)

Ovaj repozitorij sadrži izvorne datoteke za OSM letak (na engleskom jeziku) koji je originalno dizajnirao Frederik Ramm frederik@remote.org i saradnici sa talk-de liste u januaru 2008. godine, a potom je letak updejtan, preveden, ponovo updejtan i ponovo preveden tokom godina. Ovu verziju napravio je Andy Allan andy@gravitystorm.co.uk

Sav sadržaj je u javnoj domeni, osim onih izvedenih iz OSM-a koji su CC BY-SA, i osim logotipa koji nisu OSM.

Letak je dizajniran za DIN A7 u finalnoj veličini (105 mm visina i 74 mm širina), sa 8 stranica savijen u cik-cak ("Leporello") i štampanjem u boji.

Letak je napravljen pomoću Inkscape-a; osmflyer1.svg i osmflyer2.svg su prednja i zadnja strana.

Neke bilješke u slučaju da želite nešto sami ponovo dizajnirati:

* `berlin-background.png` je u osnovi četverogodišnji Osmarender-ov prikaz Berlina, koji koristi standardnu tabelu stilova, sa svim uklonjenim natpisima, a rezultirajuća PNG datoteka je obrađena u Gimpu otprilike ovako:

* Prvo pretvorite u grayscale(sivo), a zatim upotrijebite `colors->curves` da biste smanjili 
kontrast, zatim pretvorite natrag u RGB, a zatim upotrijebite `colors-> colorify` da biste dobili lijepu nijansu

* Slika zemljine kugle napravljena je Marble-om, tehnika je otprilike
objašnjena ovdje: http://wiki.openstreetmap.org/wiki/Marble

* Da biste generirali png mape visoke rezolucije, upotrijebite sljedeće komande
`~/src/nik2img/nik2img.py -d 2479 1356 -z 14 -c -0.128056 51.508056 --scale-factor 3 ~/src/openstreetmap-carto/osm-carto.xml london.png`
`~/src/nik2img/nik2img.py -d 1974 2902 -z 15 -c -3.19864 55.95 --scale-factor 3 ~/src/openstreetmap-carto/osm-carto.xml edinburgh.png`
