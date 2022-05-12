# WEB1-15puzzle
4 ETA7600 Web-ohjelmointi.ET21KM

30. Tee 15-peli eli tee sivulle 4x4 ruudukko, joiden sisällä on luvut 1-15 ja yksi ruutu jää tyhjäksi. 
31. Kun käyttäjä klikkaa ruutua, joka on tyhjän ruudun yläpuolella, alapuolella, vasemmalla puolella tai oikealla puolella, vaihtuu luku tyhjään ruutuun ja
32.  klikattu ruutu jää tyhjäksi. Tässä vaiheessa voit tehdä käsin numeroinnin ruudukkoon ja tähän yhteen pisteeseen riittää heikomminkin toimiva ratkaisu.

31. Arvo edelliseen tehtävään luvut 1-15 ruudukkoon käyttäen Math.Randomia:
// Returns a random integer from 0 to 9:
Math.floor(Math.random() * 10);
Voit jättää vaikka viimeisen ruudun tyhjäksi. Tämän voi siis tehdä vaikkei itse peli onnistunutkaan.

32. Muokkaa edellistä: Ruudut, joissa on luvut 1-4 ja 9-12 ovat taustaväriltään punaisia ja teksti on valkoista. 
33. Loput ovat valkoisella taustalla ja mustalla tekstin värillä. Näin täytyy olla koko pelin ajan.

Jos et onnistunut tekemään 30 ja 31 tehtäviä:
Tee 4x4 ruudukko table elementin sisälle ja numeroi ensimmäiset 15 ruutua numeroilla 1-15 ja jätä viimeinen tyhjäksi. 
Tee funktio, joka käy html-puun luomisen jälkeen kaikki solut läpi ja muuttaa niiden taustavärit em. ehtojen mukaan.

33. Jos käyttäjä yrittää klikata väärää ruutua, pitää käyttäjälle ilmoittaa väärästä klikkauksesta ja 
34. estää väärä toiminto. Pelin loppumisesta pitää antaa käyttäjälle ilmoitus ja uuden pelin pitää alkaa sen jälkeen.

Bonus: Tarkista taulukosta inversiot, jotta peli on ratkaistavissa.
Eli jatka tehtävää 31:n osalta tämän ohjeen mukaan https://www.geeksforgeeks.org/check-instance-15-puzzle-solvable/
