# based

## Apache etusivu 

En tiedä menikö minulta aivan ohi kuinka näitä tehdään, mutta en löytänyt oikein vastauksia siihen. Tein sitten omilla osaamisillani muutoksia sivuihin, tämä tapa tuskin on se mitä tehtävässä on haettu. Toivottavasti palautettuani osaan ottaa opikseni muiden töistä ja opetella lukemalla heidän raportteja ja harjoitella sillä tavalla tekoa!

Tein kuitenkin seuraavalla tavalla, kuten taisi olla viimekin tehtävässä: 

        $ sudo nano /var/www/html/index.html
        
Ja syötin seuraavan koodinpätkän nano editoriin: 

![Muutoksia](https://user-images.githubusercontent.com/100162043/216838857-82df3c5c-111d-4e0d-beb7-25d4228900d3.jpg)

Ja kuten aikaisemmassakin tehtävässä, sain tehtyä muutoksen sivustolle. Kuten sanoin, tämä ei ole varmasti oikea tapa tehdä tätä tehtävää. 

![Etusivu](https://user-images.githubusercontent.com/100162043/216838907-784522fc-87c0-47f2-8695-33e2210a7818.jpg)

## Virheilmoituksia

Yritin myöhään sunnuntai-iltana vielä googletella kuinka näitä tulisi luoda, mutta väsymys otti voiton ja maanantain aamu 5 herätys työpäivään pakottaa miehen unille. Ja koska palautusaikaa on klo 14 asti maanantaina, jää maanantain huomio opiskelulle ja tämän työstölle käytännössä nolliin töiden takia. 

Joten, otin seuraavan kuvan seuraavilla komennolla: 
        
        $ sudo /usr/sbin/apache2ctl configtest
        $ sudo tail -l /var/log/apache2/error.log

![Vitusti virheitä](https://user-images.githubusercontent.com/100162043/216839699-1ae96ecc-d9c8-4280-b148-d10c6305d776.jpg)

Nopealla googlettamisella vaikutti siltä, että kaikki olisi ok.



