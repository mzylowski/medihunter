#### mz
 Trójmiasto (id=`200`)

Specjalizacje (`show-params -f specialization -r 200`)
```
 Medicover Express - przeziębienie, grypa (id=16234)
 Medicover Express - przeziębienie, grypa - porada telefoniczna (id=55522)
 Alergolog dorośli (id=176)
 Alergolog dorośli - porada telefoniczna (id=44062)
 Alergolog dorośli odczulanie (id=178)
 Badanie dna oka - dorośli (id=11682)
 Chirurg dorośli (id=2)
 Chirurg stomatolog - leczenie (id=28760)
 Chirurgia - zdjęcie szwów (id=27952)
 Chirurgia - zmiana opatrunku (id=5346)
 Choroby zakaźne dorośli (id=1190)
 Cytologia (id=6254)
 Dermatolog dorośli (id=3)
 Dermatolog dorośli - porada telefoniczna (id=43852)
 Diabetolog (id=99)
 Diabetolog - porada telefoniczna (id=29178)
 Diabetolog - porada telefoniczna zdalna (id=49318)
 Dietetyk dorośli (id=182)
 Endodonta - leczenie (id=28764)
 Endokrynolog dorośli (id=5)
 Endokrynolog dorośli - porada telefoniczna (id=27962)
 Fizjoterapia stomatologiczna - leczenie (id=48080)
 Gastroenterolog dorośli (id=42)
 Gastroenterolog dorośli - porada telefoniczna (id=44054)
 Ginekolog - porada telefoniczna (id=32818)
 Ginekolog - porada telefoniczna zdalna (id=49330)
 Ginekolog - prowadzenie ciąży (id=4800)
 Ginekolog - prowadzenie ciąży - porada telefoniczna (id=44266)
 Ginekolog - prowadzenie ciąży - porada telefoniczna zdalna (id=49332)
 Ginekolog dorośli (id=4798)
 Ginekolog Endokrynolog dorośli (id=32)
 Ginekolog Endokrynolog dorośli - porada telefoniczna (id=44270)
 Ginekologia - infekcja intymna u położnej (id=46068)
 Ginekologia - pobranie wymazu (id=10244)
 Ginekologia - potwierdzenie ciąży u położnej-porada telefoniczna (id=57924)
 Ginekologia - przygotowanie do ciąży u położnej (id=72380)
 Hematolog (id=53)
 Hematolog dorośli - porada telefoniczna (id=44272)
 Hepatolog (id=54)
 Higienistka stomatologiczna (id=112)
 Immunolog (id=52706)
 Implantolog - leczenie (id=29394)
 Internista (id=9)
 Internista - porada telefoniczna (id=19046)
 Internista dyżurny (id=7338)
 Invisalign - leczenie (id=39836)
 Kardiolog dorośli (id=10)
 Kardiolog dorośli - porada telefoniczna (id=43652)
 Konsultacja stylisty (id=72984)
 Laryngolog dorośli (id=192)
 Laryngolog dorośli - porada telefoniczna (id=44066)
 Logopeda dorośli (id=96)
 Medicover Express - szczepienia dorośli (id=16236)
 Medycyna podróży - dorośli (id=9976)
 Medycyna podróży - dorośli - porada telefoniczna (id=44278)
 Medycyna Rodzinna - dorośli (id=1586)
 Medycyna rodzinna - dorośli - porada telefoniczna (id=27964)
 Nefrolog dorośli (id=33)
 Nefrolog dorośli - porada telefoniczna (id=44070)
 Neurochirurg (id=80)
 Neurolog dorośli (id=16)
 Neurolog dorośli - porada telefoniczna (id=44074)
 Okulista dorośli (id=198)
 Okulista dorośli - porada telefoniczna (id=44078)
 Okulistyka - badanie wzroku (id=19054)
 Okulistyka - dobór soczewek kontaktowych (id=22694)
 Okulistyka - pakiet dobór okularów i soczewek kontaktowych (id=58724)
 Onkolog dorośli (id=79)
 Onkolog dorośli - porada telefoniczna (id=44284)
 Optometrysta - porada telefoniczna (id=50498)
 Ortodonta - leczenie (id=28766)
 Ortopeda dorośli (id=163)
 Ortopeda dorośli - porada telefoniczna (id=44058)
 Periodontolog - leczenie (id=28768)
 Pielęgniarka internistyczna - porada telefoniczna (id=46872)
 Położna - porada telefoniczna (id=5832)
 Poradnia bólu pleców (id=16844)
 Poradnia Leczenia Boreliozy (id=20056)
 Poradnia Układu Ruchu - dorośli (id=27158)
 Proktolog dorośli (id=56)
 Protetyk - leczenie (id=28770)
 Protetyk słuchu - dobór aparatu słuchowego (id=38636)
 Przeziębienie, grypa - pielęgniarka specjalistyczna (id=63156)
 Pulmonolog dorośli (id=41)
 Pulmonolog dorośli - porada telefoniczna (id=44082)
 Punkt Pobrań - ciężarne (id=52110)
 Punkt Pobrań - dorośli (id=52106)
 Reumatolog dorośli (id=26)
 Reumatolog dorośli - porada telefoniczna (id=44086)
 Stomatolog - leczenie (id=23504)
 Stomatolog - przegląd (id=22890)
 Stomatolog dziecięcy - leczenie (id=28772)
 Urolog dorośli (id=30)
 Urolog dorośli - porada telefoniczna (id=44290)
 USG ciąży 4D (id=8474)
 Wizyta Pierwszorazowa z planem leczenia (id=55112)
```

Konkretny lekarz:

Wylisotwanie alergologów w Trojmieście: `show-params -f doctor -r 200 -s 176`



# medihunter

Narzędzia służy do automatycznego wyszukiwania wizyt u lekarzy. Szczególnie przydaje się gdy wizyty są trudno dostępne ;)

**Działa z pythonem w wersji 3.6+**

<p align="center">
    <img src="https://apqlzm.github.io/theme/images/icons/search-every-minute.svg">
</p>

## Wstęp

Dostępne są dwie wersje skryptu

* **medihunter_pushover.py** - ma funkcje powiadomień pushover, możliwość wyszukiwania kilku klinik i kilku specjalistów jednocześnie. Kod wymaga refaktoru i w związku z tym nie będzie rozwijany. Z czasem planuje go usunąć.
* **medihunter.py** - tu dodawane są nowe funkcjonalności. Na chwilę obecną (2021-07-11) można ustawić powiadomienia pushover, w telegramie i przez xmpp.

## Instalacja

Aktywujemy virtualenva (opcjonalnie choć zalecane)

```bash
source /path/to/my/virtualenv/bin/activate
```
lub w Windows cmd ze środowiskiem wirtualnym utworzonym biblioteką venv

```
SourceToVirtEnv\Scripts\activate.bat
```

Przechodzimy do katalogu ze źródłem i odpalamy

```bash
pip install --editable .
```

Od teraz mamy dostępną w virtualenvie komendę: `medihunter`

Jeśli nie chcemy być za każdym razem pytani o login i hasło i/lub nie chcemy podawać ich jawnie w terminalu poprzez `--user login --password hasło` to możemy zapisać je w pliku `.env`:
```
MEDICOVER_USER=login
MEDICOVER_PASS=hasło
```

Najprościej skopiować przykładowy plik `.env.example` z głównego katalogu jako `.env` i uzupełnić w nim dane.

## Dostępne subkomendy

### show-params

Gdy wyszukujemy wizyty musimy podać miasto, placówkę medyczną, specjalizację (jaki to ma być lekarz), identyfikator lekarza (możliwość wybrania konkretnego lekarza), datę wizyty (wizyta zacznie się nie wcześniej niż ta data). Każdy z tych parametrów (z wyjątkiem daty) ma przypisany nr id. Żeby go poznać używamy do tego komendy *show-params*.

id miast

```bash
medihunter show-params -f region
```

id specjalizacji

```bash
medihunter show-params -f specialization -r 204
```

### find-appointment

Poszukajmy endokrynologa

```bash
medihunter find-appointment -s 27962
```

Oczywiście znalezienie wizyty do endokrynologa nie jest takie proste, więc ustawmy żeby wyszukiwarka sprawdzała czy jest coś dostępne co 5 minut

```bash
medihunter find-appointment -s 27962 -i 5
```

a może chcemy poszukać konkretnych endokrynolgów o ID: 12345 i 0987? **tylko w medicover_pushover.py**

```bash
medihunter find-appointment -s 27962 -o 12345 -o 0987
```

a może po prostu szukamy dowolnego internisty w przychodniach blisko nas w Atrium i na Prostej? **tylko w medicover_pushover.py**

```bash
medihunter find-appointment -s 9 -c 174 -c 49088
```

a co jeśli chcemy znaleźć wizytę u dowolnego ortopedy w Trójmieście w przeciągu następnych dwóch tygodni a nie za miesiąc? **bez daty rozpoczęcia nie działa**

```bash
medihunter find-appointment -s 163 -d 2021-12-19 -f 2022-12-31 -r 200 
```

Lub można dodać bezpośrednio do Crontaba jak poniżej **wpis w cronie działa tylko z medicover_pushover.py**

- będzie uruchamiany między 6tą a 23cią co 5 minut
- -s - szuka Ortopedy dla dorosłych
- -c 174 -c 6896 tylko w centrum Warszawa Atrium i Warszawa Inflancka
Będzie korzystał z podanych parametrów użytkownika Medicoveru i Pushover do wysyłania powiadomień
- crontab zapisze logi w /var/log/medihunter.log

```bash
*/5 6-23 * * * /usr/bin/python3.7 /home/user/medihunter.py find-appointment -s 163 -c 174 -c 6896 --user MEDICOVER_USER --password MEDICOVER_PASS --pushover_msgtitle 'Ortopeda Centrum' --pushover_token PUSHOVER_TOKEN --pushover_user PUSHOVER_USER >> /var/log/medihunter.log 2>&1
```

### my-plan

Ściąga i zapisuje dostępne usługi wraz z informacjami na temat tego czy są dostępne w ramach wykupionego pakietu, a jeśli nie to czy mamy na nie jakieś zniżki. Niektóre usługi mają limity, to też powinno być tu widoczne. Plik wynikowy ma format  tsv (Tab-separated_values). Przykład użycia:

```bash
medihunter my-plan --user mylogin --password mypassword
```

## Wyświetlanie pomocy

Ogólna pomoc

```bash
medihunter --help
```

Poszczególne subkomendy

```bash
medihunter find-appointment --help
medihunter show-params --help
```

## Powiadomienia Pushover

dotyczy **medicover_pushover.py**

Poprzez podanie parametrów do powiadomień Poshover https://pushover.net/ możliwe jest przekazywanie powiadomień na wizytę bezpośrednio do aplikacji. Należy podać minimalnie parametry --pushover_token oraz --pushover_user

## Domyślne ustawienia

### show-params

domyślnie -f jest ustawiony na *specialization*

### find-appointment

TODO: _Poniższe opcje aktualne tylko dla medihunter_pushover.py_

opcja|domyślna wartość
-----|----------------
-r, --region|Warszawa
-b, --bookingtype|2, Typ wizyty 2 = Konsultacja (domyślnie), 1 = Badanie diagnostyczne
-s, --specialization|brak Specjalizacja, podać w przypadku gdy Typ wizyty to Konsultacja (bookingtype = 2 domyślnie)
-e, --service|brak, Typ/identyfikator usługi, podać w przypadku gdy Typ wizyty to usługa (bookingtype = 1), działa analogicznie do specjalizacji
-c, --clinic|wszystkie jakie są w regionie/mieście, można użyć parametru wielokrotnie w celu szukania wizyt w konkretnych klinikach
-o, --doctor|wszyscy lekarze, można użyć parametru wielokrotnie w celu sprawdzenie kilku lekarzy
-d, --start-date|data bieżąca (format: YYYY-mm-dd)
-f, --end-date|brak (format: YYYY-mm-dd), dostępna tylko w medihunter.py
-a, --start-time|"0:00" (format: hh:mm), dostępna tylko w medihunter.py
-g, --end-time|"23:59" (format: hh:mm), dostępna tylko w medihunter.py
-j, --days-ahead| 1 = pokazuje wizyty dla pierwszego znalezionego dnia, dostępna tylko w medihunter.py
-i, --interval|brak
--disable-phone-search|brak, Pozwala pominąć wizyty telefoniczne w wyszukiwaniu, dostępna tylko w medihunter.py
--pushover_token|brak, Pushover Application Token
--pushover_user|brak, Pushover user Token
--pushover_device|brak, None nazwa device w Pushover domyślnie pusta=wszystkie
--pushover_msgtitle|brak - prefix dodawany przed tytułem powiadomienia
-t, --notification-title|brak, dostępna tylko w medihunter.py, wspierana tylko przez Pushover i Telegram

## Pushbullet w medihunter.py

Żeby działały powiadomienia pushbullet trzeba zrobić eksport (wartości ustawiamy swoje):

```shell
# bash
export NOTIFIERS_PUSHBULLET_TOKEN=avykwnqc8ohyk73mo1bsuggsm3r4qf
```

lub

```shell
# fish
set -x NOTIFIERS_PUSHBULLET_TOKEN avykwnqc8ohyk73mo1bsuggsm3r4qf
```

Teraz możemy wyszukać wizyty np. tak:

```shell
medihunter find-appointment -n pushbullet -r 204 -s 4798 --user 00000 --password psw1234 -i 1 -d 2019-05-15
```

## Pushover w medihunter.py

Żeby działały powiadomienia pushover trzeba zrobić eksport (wartości ustawiamy swoje):

```shell
# bash
export NOTIFIERS_PUSHOVER_TOKEN=avykwnqc8ohyk73mo1bsuggsm3r4qf
export NOTIFIERS_PUSHOVER_USER=s4g1zoewbzseogp4knrapx23k9yi95
```

lub

```shell
# fish
set -x NOTIFIERS_PUSHOVER_TOKEN avykwnqc8ohyk73mo1bsuggsm3r4qf
set -x NOTIFIERS_PUSHOVER_USER s4g1zoewbzseogp4knrapx23k9yi95
```

Teraz możemy wyszukać wizyty np. tak:

```shell
medihunter find-appointment -n pushover -r 204 -s 4798 --user 00000 --password psw1234 -i 1 -d 2019-05-15
```

## Telegram w medihunter.py

Musimy utworzyć bota do powiadomień i kanał na który będą przesyłane powiadomienia. Szczegóły jak to zrobić można znaleźć pod adresem https://core.telegram.org/bots

Jak już mamy to gotowe to wystarczy zrobić eksport dwóch zmiennych (wartości ustawiamy swoje):

```shell
# bash
export NOTIFIERS_TELEGRAM_CHAT_ID=avykwnqc8ohyk73mo1bsuggsm3r4qf
export NOTIFIERS_TELEGRAM_TOKEN=740885363:AdFRNFTIFTc4hC1flAuXE-dyik_Udm6Ma3o
```

lub

```shell
# fish
set -x NOTIFIERS_TELEGRAM_CHAT_ID avykwnqc8ohyk73mo1bsuggsm3r4qf
set -x NOTIFIERS_TELEGRAM_TOKEN 740885363:AdFRNFTIFTc4hC1flAuXE-dyik_Udm6Ma3o
```

lub w Windows z venv
```shell
set NOTIFIERS_TELEGRAM_CHAT_ID=avykwnqc8ohyk73mo1bsuggsm3r4qf
set NOTIFIERS_TELEGRAM_TOKEN=740885363:AdFRNFTIFTc4hC1flAuXE-dyik_Udm6Ma3o
```

Teraz możemy wyszukać wizyty i otrzymać notyfikacje w Telegramie:

```shell
medihunter find-appointment -r 204 -s 4798 --user 00000 --password psw1234 -i 1 -d 2019-05-22 -n telegram
```

## XMPP w medihunter.py

Musimy posiadać 2 zarejestrowane konta XMPP:
- pierwsze do wysyłania wiadomości, w przypadku odnalezienia wizyt zgodnych z zadanymi kryteriami wyszukiwania,
- drugie do odbierania wiadomości z powiadomieniami, na którym będziemy zalogowani w dowolnym kliencie obsługującym XMPP (np. na komputerze/urządzeniu mobilnym).

Eksportujemy nazwy obu kont XMPP i hasło logowania do pierwszego z kont (wartości ustawiamy swoje):

```shell
# bash
export NOTIFIERS_XMPP_JID='nadawca_powiadomien@example.com'
export NOTIFIERS_XMPP_PASSWORD='haslo_nadawcy_powiadomien'
export NOTIFIERS_XMPP_RECEIVER='odbiorca_powiadomien@example.com'
```

lub

```shell
# fish
set -x NOTIFIERS_XMPP_JID 'nadawca_powiadomien@example.com'
set -x NOTIFIERS_XMPP_PASSWORD 'haslo_nadawcy_powiadomien'
set -x NOTIFIERS_XMPP_RECEIVER 'odbiorca_powiadomien@example.com'
```

Teraz możemy wyszukać wizyty i otrzymać notyfikacje poprzez XMPP:

```shell
medihunter find-appointment -r 204 -s 4798 --user 00000 --password psw1234 -i 1 -d 2019-05-22 -n xmpp
```

## Docker
Aby uruchomić aplikację w kontenerze należy w pierwszej kolejności zbudować obraz

```shell
docker build -t medihunter .
```

Następnie uruchamiamy kontener używając komendę run
```shell
docker run -it medihunter find-appointment --user 00000 --password psw1234 -r 204 -s 4798
```

Możliwe jest także użycie zmiennych środowiskowych lub pliku .env
```shell
docker run -it  -e MEDICOVER_USER=00000 -e MEDICOVER_PASS=psw1234 medihunter find-appointment -r 204 -s 4798d

docker run -it --env-file=.env medihunter find-appointment -r 204 -s 4798
```