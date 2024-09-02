# e14-2018_styczen
# ZADANIE EGZAMINACYJNE</p>

## Zaprojektuj zapytania SQL do bazy szkola, wykonaj zrzuty ekranu przedstawiające efekty działania zapytań, przygotuj grafiki przeznaczone do umieszczenia na stronie internetowej oraz witrynę internetową. Wykorzystaj środowisko XAMPP, edytor zaznaczający składnię HTML oraz edytor grafiki rastrowej.

### Baza Danych
Archiwum ZIP o nazwie `zad2.zip` jest zabezpieczone hasłem `szko!a_2`
Jego zawartość to plik `szkola.sql` zawierający przygotowane do importu tabele bazy danych `szkola`. Baza danych `szkola` składa się z trzech tabel: uczen, klasa, wychowawca. Wszystkie tabele posiadają klucz podstawowy o nazwie `id`. 
Opis tabel jest następujący:
- Tabela uczen -przechowuje: informacje o wybranych uczniach klas 1a, 1b, 2a i 2b szkoły ponadgimnazjalnej, -pola: imie i nazwisko typu tekstowego oraz id i id_klasy typu liczbowego, -pole id_klasy jest kluczem obcym powiązanym z kluczem podstawowym tabeli klasa.
- Tabela wychowawca -przechowuje: informacje o wychowawcach klas 1a, 1b, 2a i 2b, -pola: imie i nazwisko typu tekstowego oraz id i id_klasy typu liczbowego, -pole id_klasy jest kluczem obcym powiązanym z kluczem podstawowym tabeli klasa. 
- Tabela klasa -przechowuje: informacje o klasach 1a, 1b, 2a i 2b, -pola: nazwa typu tekstowego oraz id i il_uczniow typu liczbowego.

### Zapytania do bazy danych
Za pomocą narzędzia XAMPP Control Panel uruchom usługi Apache oraz MySQL, przejdź do narzędzia phpMyAdmin. Wykonaj następujące czynności:

- Utwórz bazę danych o nazwie **szkola**,

- Do bazy szkola zaimportuj tabele z pliku **zkola.sql** z wcześniej rozpakowanego archiwum,

- W podfolderze baza utwórz plik **zapytania.txt**,

- Zapisz i wykonaj zapytania SQL działające na bazie szkola. Zapytania zapisz w pliku **kwerendy.txt**, w podfolderze baza.
***Wykonaj zrzuty ekranu przedstawiające wyniki działania kwerend. Zrzuty zapisz w formacie PNG, w podfolderze baza jako: `kwerenda1.png,kwerenda2.png, nowy_uzytkownik.png i uprawnienia.png`. Zrzuty powinny obejmować cały ekran monitora z widocznym paskiem zadań.

**Zapytanie 1:** zapisujące w tabeli wychowawca rekord danych: id=5,imie=Maciej, nazwisko=Stasiak, id_klasy=5,

**Zapytanie 2:** wybierające jedynie imiona i nazwiska uczniów, których wychowawczyni nazywa się Michalska,

**Zapytanie 3:** tworzące użytkownika * *K_Pietkiewicz* * na localhost z hasłem * *kp_123* *

**Zapytanie 4:** nadające prawa dla użytkownika * *K_Pietkiewicz* * wybierania i dodawania danych dla tabeli uczen,

***Wyeksportuj bazę danych do pliku o nazwie <i>szkola_nowa.sql</i>,plik eksportu umieść w podfolderze <i>baza</i>.***




### Witryna internetowa

Stwórz prostą witrynę składającą się z jednej strony internetowej o nazwie * *index.html* *. Plik zapisz w podfolderze www. Wygląd witryny jest zgodny z Obrazem 1


### Przygotowanie grafik:
Wykorzystując zrzuty ekranowe kwerend przygotuj grafiki dla witryny internetowej:
- zrzuty ekranowe wykadruj tak, aby były widoczne tylko efekty działania zapytań, nie powinny być widoczne inne elementy okna przeglądarki oraz panelu phpMyAdmin,</li>
- przeskaluj obrazy tak, aby ich szerokość wynosiła 400 px, a wysokość 200 px,
- obrazy zapisz w formacie JPG, w podfolderze * *www* *, jako * *kwerenda1.jpg, kwerenda2.jpg, nowy_uzytkownik.jpg i uprawnienia.jpg* *

**UWAGA:** * *pliki z podfolderu baza pozostaw niezmienione, nie nadpisuj ich.* *

### Cechy witryny: 
- zastosowano właściwy standard kodowania polskich znaków,
- tytuł strony: „Szkoła ponadgimnazjalna”,
- strona podzielona za pomocą znaczników sekcji na baner, panele lewy i prawy oraz stopkę, tak aby po uruchomieniu strony w przeglądarce wygląd był zgodny z obrazem 1,
- zawartość banera: nagłówek pierwszego stopnia o treści: „Projekt strony internetowej szkoły ponadgimnazjalnej”,
- zawartość panelu lewego: -nagłówek trzeciego stopnia o treści: „Do pobrania”, -poniżej w postaci listy punktowanej dwa odnośniki: 1. „zapytania SQL”, 2.„baza danych”,-kliknięcie odnośnika o treści: „zapytania SQL”, powoduje pobranie/wyświetlenie pliku zapytania.txt z podfolderu baza, -kliknięcie odnośnika o treści: „baza danych”, powoduje pobranie/wyświetlenie pliku szkola_nowa.sql z podfolderu baza, -poniżej linia pozioma przez całą szerokość panelu lewego, -poniżej napis w nagłówku trzeciego stopnia: „Wyznaczanie najwyższej średniej”, -poniżej lista punktowana z nazwiskami: Polak, Nowak, Rysik, obok każdego nazwiska pole edycyjne typu tekstowego przeznaczone na wpisanie średniej ocen ucznia, -poniżej przycisk z etykietą „wyznacz”, -poniżej napis w nagłówku trzeciego stopnia „Najwyższa średnia:”, 
- zawartość panelu prawego: -tabela o rozmiarach 5 wierszy i 2 kolumny, -szerokość prawej kolumny tabeli: 405 px, -komórki wiersza nagłówkowego zawierają kolejno wpisy: „Treść zapytania” i „Zrzut ekranu”, -w komórkach tabeli w kolejnych wierszach: treści zapytań z pliku zapytania.txt i obok odpowiadające im zrzuty ekranu w formacie JPG zgodnie z obrazem 1, -obrazy powinny posiadać tekst alternatywny zawierający nazwę pliku,
-  zawartość stopki: -nagłówek czwartego stopnia o treści: „stronę wykonał: ………….”, w miejsce kropek wpisany Twój numer PESEL.



### Styl CSS witryny internetowej

<p>Styl elementów witryny zdefiniuj przy pomocy języka CSS, w osobnym pliku o nazwie <i>styl.css</i>, plik ten zapisz w podfolderze <i>www</i> oraz prawidłowo dołącz do pliku z kodem strony.</p>

<p>Wymagania odnośnie stylu CSS:</p>

<ul>

<li>kolor czcionki odnośników: #ffd87e,</li>

<li>kolor tła banera, stopki oraz panelu lewego: #af8c4b,</li>

<li>kolor tła panelu prawego: #ffd87e,</li>

<li>wyrównanie tekstu banera i stopki: do środka,</li>

<li>wyrównanie tekstu panelu lewego: do prawej,</li>

<li>krój czcionki dla całej strony: Tahoma,</li>

<li>szerokość panelu lewego: 30%,</li>

<li>szerokość panelu prawego: 70%,</li>

<li>wysokość paneli lewego i prawego: 500 px,</li>

<li>wysokość banera: 60 px,</li>

<li>wysokość stopki: 25 px,</li>

<li>kolor poziomej linii w lewym panelu: #ffd87e,</li>

<li>punktor list w panelu lewym: okrąg,</li>

<li>wszystkie komórki tabeli obramowane ramką czarną kropkowaną szerokości 1 px,</li>

<li>włączone paski przewijania dla panelu prawego,</li>

</ul>





<h5>Skrypt wyznaczający najwyższą średnią ocen </h5>



<ul>

<li>wykonywany po stronie klienta,</li>

<li>powinien wykonywać działania na liczbach rzeczywistych,</li>

<li>po kliknięciu przycisku „wyznacz” skrypt pobiera dane z trzech pól

edycyjnych typu tekstowego,</li>

<li>jeżeli przynajmniej jedno z pól jest puste lub do któregoś pola wpisano ciąg znaków, który nie jest poprawną liczbą rzeczywistą skrypt powinien wyświetlić w osobnym oknie komunikat „wpisz poprawne dane”,</li>

<li>w przeciwnym przypadku skrypt powinien przekonwertować ciągi znaków na liczby rzeczywiste,</li>

<li>następnie skrypt powinien wyznaczyć najwyższą spośród trzech średnich ocen,</li>

<li>na koniec skrypt powinien wyświetlić wyznaczoną najwyższą średnią poniżej napisu „Najwyższa średnia” w lewym panelu.</li>

</ul>

<p><b>UWAGA:</b> <i> 

W repozytorium powinny znajdować się podfoldery: **baza** oraz **www**. W podfolderze **baza** powinny znajdować się pliki: `szkola_nowa.sql`, `zapytania.txt`, `kwerenda1.png`, `kwerenda2.png`, `nowy_uzytkownik.png` i `uprawnienia.png`. W podfolderze **www** powinny znajdować się pliki: `kwerenda1.jpg`, `kwerenda2.jpg`, `nowy_uzytkownik.jpg` i `uprawnienia.jpg` oraz `index.html`, `styl.css`, ewentualnie inne przygotowane pliki.</i></p><i>

<p><b>Ocenie będzie podlegać 5 rezultatów:</b></p>

<ul>

<li>operacje na bazie danych,</li>

<li>witryna internetowa,</li>

<li>styl CSS witryny internetowej,</li>

<li>skrypt.</li>

</ul>


