# Multiplayer-Snake Programowanie-Rozproszone
Projekt na zaliczenie przedmiotu 'Programowanie Rozproszone' opracowany w 2-osobowym zespole.

W projekcie korzystamy z języka C, w którym napisany jest server oraz Pythona, który jest odpowiedzialny za stronę klienta.
Projekt jest swego rodzaju klonem gry przeglądarkowej 'Achtung, Die Kurve!', w której każdy gracz wciela się w węża, którego celem jest jak najdłuższe utrzmanie
się przy życiu i eliminację pozostałych graczy poprzez zablokowanie im drogi swoim ogonem.
W projekcie używane są sockety do komunikacji sieciowej oraz semafory do zapewnienia współbieżności.

# Uruchomienie serwera (Linux):

Będąc w folderze server należy wpisać w konsolę polecenie ./compile.sh - e LICZBA_GRACZY IP
np: ./compile.sh - e 3 127.0.0.1

# Uruchomienie klienta (Dowolny system):

Będąc w folderze client należy wpisać w konsolę polecenie python3 main.py IP
np: python main.py 127.0.0.1

# Rozgrywka

Ruch odbywa się za pomocą strzałek(Lewa/Prawa). Na mapie pojawiają się bonusy szybkości,nieśmiertelności i większego rozmiaru.
Rozgrywka kończy się w momencie gdy nie ma już żywych graczy i każdy z nich otrzymuje dedykowaną tablicę wyników.
