# Laboratorium 5

## Zadanie 1 ##

Na podstawie poprzedniego laboratorium z mapami, ustawić kamerę na zatokę gdańską.
Dodać do projektu plik GeoServerUrlTileProvider z repozytorium i dodać jako źródło kafelków.

Tworzenie providera:
new GeoServerUrlTileProvider("http://vps526645.ovh.net:8145/geoserver/gwc/service/",
                        "gik",
                        "S2A_20170829T152942_T34UCF_CHL_OC3",
                        256, 256)))
						
## Zadanie 2 ##

Uruchomić nowy wątek, uśpić go na kilka sekund, przesunać kamerę po wybudzeniu

## Zadanie 3 ##

Przy uruchomieniu activity dodać jakąś wartość do SharedPreferences, jeśli jej tam jeszcze nie ma. Jeśli jest, wypisać w logach na konsolę.

