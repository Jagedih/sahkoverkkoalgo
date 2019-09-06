# Määrittelydokumentti
Sähköverkot ovat yhtenäisiä verkkoja normaalissa käyttötilanteessa, verkkohäiriön aikana sähköverkkoon voi muodostua 
saarekkeita eli toisistaan eriytyneitä sähköverkon osasia. Laboratoriotyön tarkoituksena on tehdä ohjelma, joka tutkii 
sähköverkon yhtenäiset osat syvyyshaulla. Tämän jälkeen ohjelma etsii lyhimmän reitin isoimmasta verkosta pienempään/pienempiin
verkkoihin käyttäen Dijkstraa ja Floyd-Warshalii. Tarkoituksena on myös tutkia näiden kahden algoritmin eroa. 

Ohjelmaan syötetään sähköasemien (solmujen) tietoja. Näissä tiedoissa on sähköasemalta lähtevien
voimajohtojen tilatiedot (johdon katkaisijan tila ja johdon päässä oleva sähköaseman nimi). Voimajohdon katkaisijan tilasta 
ohjelma tarkastaa onko johto ns. kylmänä vai ei. Ohjelma muodostaa annetuista tiedoista vierusmatriisin, jota käytetään
ongelman ratkaisemisessa

Ohjelmointikielenä on Java
Valitsin aiheen koska olen työskennellyt sähköverkkojen parissa ja aihe sopii hyvin kurssille.
Sähköverkon datan luon itse.