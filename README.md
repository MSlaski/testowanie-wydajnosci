# Testowanie Wydajności
Repozytorium z materiałami wykorzystywanymi na szkoleniu Testowanie Wydajności.
# Przygotowanie do szkolenia
* Pobierz i zainstaluj oprogramowanie Java SE 8 ze strony https://www.java.com/pl/download/
* Pobierz aplikację JMeter ze strony https://jmeter.apache.org/download_jmeter.cgi. Rozpakuj archiwum do aktualnego katalogu. Po rozpakowaniu zprawdź katalog ma strukturę jak poniżej
```
|   README.md
|   run-performance-test.bat
|   run-stability-test.bat
\---apache-jmeter-5.6.2
|   \---bin
|   \---docs
|   \---extras
|   \---lib
|   \---licenses
|   \---printable_docs
\---scripts
        ContactsWS.jmx
        user.properties
        users.csv
```
* W aktualnym katalogu otwórz wiersz poleceń (cmd)
* Wykonaj polecenie ```SET IP=```
* Wykonaj polecenie ```run-stability-test.bat```
* Po zakończeniu działania skryptu w katalogu results powinien pojawić się katalog a w nim plik 'index.html'
