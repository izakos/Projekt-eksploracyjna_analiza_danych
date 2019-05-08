# Projekt - eksploracyjna analiza danych

Projekt został zrealizowany na zaliczenie przedmiotu Eksploracja danych - warsztaty na Wydziale Matematyki i Informatyki na Uniwersytecie im. Adama Mickiewicza w Poznaniu. 

W swoim projekcie starałyśmy się wykonać eksploracyjną analizę danych za pomocą różnorodnych narzędzi, takich jak Python, R czy Tableau.

Na początek polecamy zainstalować python 3.7 (najlepiej w wersji anakonda - jupyter notebook), a następnie potrzebne biblioteki np. za pomocą polecenia:

`pip install -r requirements.txt`


Analizowany przez nas zbiór nazywa się Weather. Dane pochodzą z pakietu mosaicData środowiska R. Można je pobrać przykładowo ze strony https://vincentarelbundock.github.io/Rdatasets/datasets.html?fbclid=IwAR0rG5b1v-6G-4nHddhLAFSA3rsLtZqOdW_mi74NYMoq20hurAUX0npYNJc.

Oryginalnie zostały one zebrane z danych pogodowych 5 miast świata - Beijing (pl. Pekin), Mumbai (pl. Bombaj), San Diego, Auckland, Chicago a ich źródłem jest archiwum strony internetowej https://www.wunderground.com/history/.

Liczba kolumn wynosi 25, natomiast wierszy jest 3655.

Obserwacje w kolumnach przed dokonaną analizą oznaczają odpowiednio:

**city**                                      - nazwa miasta

date                                      - data

year                                      - rok numeryczny

month                                     - numeryczny miesiąc

day                                       - numeryczny dzień

high_temp, avg_temp, low_temp             - wysoka, średnia i niska temperatura w ciągu dnia w stopniach F

high_dewpt, avg_dewpt, low_dewpt          - wysoki, średni i niski punkt rosy w ciągu dnia w stopniach F

high_humidity, avg_humidity, low_humidity - wysoka, średnia i niska wilgotność względna

high_hg, avg_hg, low_hg                   - wysokie, średnie i niskie ciśnienie na poziomie morza w calach rtęci

high_vis, avg_vis, low_vis                - wysoka, średnia i niska widoczność w ciągu dnia w milach

high_wind, avg_wind, low_wind             - wysoka, średnia i niska prędkość wiatru na dzień w mph

precip                                    - opady na dzień - dolina postaci; T oznacza „ilość śladową”

events                                    - ciąg znaków określający zdarzenia pogodowe w danym dniu (deszcz, mgła, śnieg itp.)
