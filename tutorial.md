Kartendienste:
    - https://tools.retorte.ch/map/
    - http://netvicious.com/gps/
    - http://gpso.de/maps/


    Python-Packges
    - https://pypi.python.org/pypi/utm
    - https://pypi.python.org/pypi/pyproj
    - http://matplotlib.org/basemap/
        - `conda install basemap`


    Koordinatensysteme:

    # World Geodetic System 1984
    - https://de.wikipedia.org/wiki/World_Geodetic_System_1984
    - Referenzen sind Äquator und Nullmeridian
    - Angabe in Grad oder Dezimal:
        - 50° 0′ 30.75″ N / 8° 1′ 11.5″ E 
        - 50.008542° / 8.019861°
    - http://www.unoosa.org/pdf/icg/2012/template/WGS_84.pdf
    - EPSG:4326 (World)

    # Gauss-Krüger
    - https://de.wikipedia.org/wiki/Gauß-Krüger-Koordinatensystem
    - 3° Meridianstreifen, jeweils von Nord- bis Südpol parallel
      zu Mittelmeridian
    - Streifen erhält Kennziffern nach Gradzahl des Mittelmeridians
    - Zwei Koordinaten: Rechts- (x) und Hochwert (y) in Metern
    - Offset: (0, 0) == (500000m, 0)
    - Dem Rechtswert wird die Meridiankennziffer vorangestellt
    - Referenz-Ellipsoid: Bessel oder Krassowski
    - EPSG:31466 (DHDN / 3-degree gauss-kruger zone 2), Germany - west of 7.5°E, Bessel

    # UTM (Universal Transverse Mercator)
    - https://de.wikipedia.org/wiki/UTM-Koordinatensystem
    - 6° Meridianstreifen, jeweils von Nord- bis Südpol parallel
      zu Mittelmeridian
    - Streifen erhält "Zone" nach Mittelmeridian
    - Zwei Koordinaten: Rechts- (x) und Hochwert (y) in Metern
    - Offset: (0, 0) == (500000m, [Nord: 0, Süd: 10000000])
    - Referenz-Ellipsoid: WGS84 bzw. GRS80
    - EPSG:25832 (ETRS89 / UTM zone 32N), Europe - 6°E to 12°E and ETRS89 by country
    - https://de.wikipedia.org/wiki/Europäisches_Terrestrisches_Referenzsystem_1989
    - http://www.bezreg-koeln.nrw.de/brk_internet/publikationen/abteilung07/pub_geobasis_etrs89.pdf


    EPSG Codes
    - https://de.wikipedia.org/wiki/European_Petroleum_Survey_Group_Geodesy
    - http://spatialreference.org
