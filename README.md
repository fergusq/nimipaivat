# Vuosien 1995 ja 2000 nimipäiväkalenterit

Tästä reposta löytyy Helsingin yliopiston toimittama suomalainen ja
suomenruotsalainen nimipäiväkalenteri vuosilta 1995 ja 2000 sekä saamelainen
nimipäiväkalenteri vuodelta 2000. Kalenterit löytyvät sekä txt- että
json-muotoisina.

## Tiedostot

Kansioista `1995` ja `2000` löytyvät seuraavat tiedostot (saamenkielinen
kalenteri vain vuodelta 2000):

	txt/namedays-fi.txt     Suomenkielinen nimipäiväkalenteri txt-muotoisena
	txt/namedays-sv.txt     Ruotsinkielinen nimipäiväkalenteri txt-muotoisena
	txt/namedays-sa.txt     Saamenkielinen nimipäiväkalenteri txt-muotoisena
	json/namedays-fi.json   Suomenkielinen nimipäiväkalenteri json-muotoisena
	json/namedays-sv.json   Ruotsinkielinen nimipäiväkalenteri json-muotoisena
	json/namedays-sa.json   Saamenkielinen nimipäiväkalenteri json-muotoisena
	tee_json.röd            Ohjelma txt-muodon muuntamiseksi json-muotoon

Vuoden 1995 txt-formaatissa kuukauden ensimmäisellä rivillä lukee kuukauden
päivien määrä ja kuukauden nimi. Sen jälkeen seuraa jokainen kuukauden päivä
omalla rivillään. Päivän rivillä on päivän numero ja nimet.

Vuoden 2000 txt-formaatissa jokaisella rivillä on nimi ja päivämäärä.

Kansioissa olevilla skripteillä voi muuttaa txt-muotoista dataa json-muotoiseksi.

## Tekijänoikeus

Helsingin yliopisto omistaa ns. luettelosuojan ([Tekijänoikeuslaki 49 §])
toimittamiinsa nimipäiväluetteloihin ([KKO:2000:56]). Luettelosuoja on voimassa
15 vuotta. Koska nimipäiväkalenterit ovat vuosilta 1995 ja 2000, niiden
luettelosuoja on siis rauennut, eikä yliopistolla tai muilla tahoilla ole enää
niihin oikeutta. Tämän vuoksi kalentereita saa kopioida ja jakaa vapaasti.

Rödaskriptit on lisenssoitu MIT-lisenssillä.

## In English

This repository contains the Finnish and Swedish name day calendars published by
the University of Helsinki in 1995 and 2000. The calendars are in TXT and JSON
formats.

The copyright to the calendars is no longer valid, as 15 years have been passed
since they were published. The Röda files are licensed under the MIT license.

[Tekijänoikeuslaki 49 §]: https://www.finlex.fi/fi/laki/ajantasa/1961/19610404#L5P49
[KKO:2000:56]: https://www.finlex.fi/fi/oikeus/kko/kko/2000/20000056
