# e14-2018_styczen

<div class="exam-practice-cnt" style="display: block;">

                                        <div class="exam-practice-cnt-header">

                                            <p>ZADANIE EGZAMINACYJNE</p>

                                            <div class="exam-practice-cnt-header-download">

                                                <div class="download-archives cnt-exam-choose-semestr-download e14">

                                                    <a class="download-btn" href="file/archiwa/2018/zima/E.14-08-18.01/zad2.zip">Pobierz

                                                        archiwum</a>

                                                </div>

                                                <div class="download-solution cnt-exam-choose-semestr-download e14">

                                                    <a class="download-btn" href="file/rozwiązania/2018/Zima/E.14-08-18.01.rar">Pobierz

                                                        rozwiązanie</a>

                                                </div>

                                            </div>

                                        </div>

                                        <div class="exam-practice-cnt-text">

                                            <p>Zaprojektuj zapytania SQL do bazy szkola, wykonaj zrzuty ekranu

                                                przedstawiające efekty działania zapytań, przygotuj grafiki przeznaczone

                                                do umieszczenia na stronie internetowej oraz witrynę internetową.

                                                Wykorzystaj środowisko XAMPP, edytor zaznaczający składnię HTML oraz

                                                edytor grafiki rastrowej.</p>

                                            <p>Na stanowisku egzaminacyjnym znajduje się komputer z zainstalowanym

                                                systemem operacyjnym i oprogramowaniem, a także dokumentacja w postaci

                                                spisu zainstalowanego oprogramowania. Zaloguj się na konto

                                                <b>Egzamin</b> bez hasła. Wyniki swojej pracy zapisz w folderze. Jako

                                                nazwy folderu użyj swojego numeru PESEL. Folder umieść na pulpicie konta

                                                <b>Egzamin</b>. Wewnątrz folderu utwórz dwa podfoldery o nazwach:

                                                <i>baza</i> oraz <i>www</i>.</p>





                                            <h5>Baza Danych</h5>

                                            <p>Na pulpicie konta <b>Egzamin</b> znajduje się archiwum ZIP o nazwie

                                                <i>zad2.zip</i>. Archiwum jest zabezpieczone hasłem <b>szko!a_2</b></p>

                                            <p>Jego zawartość to plik <i>szkola.sql</i> zawierający przygotowane do

                                                importu tabele bazy danych <i>szkola</i>.</p>

                                            <p>Baza danych <i>szkola</i> składa się z trzech tabel: uczen, klasa,

                                                wychowawca. Wszystkie tabele posiadają klucz podstawowy o nazwie

                                                <i>id</i>. Opis tabel jest następujący:</p>

                                            <ul>

                                                <li>Tabela uczen</li> -przechowuje: informacje o wybranych uczniach klas

                                                1a, 1b, 2a i 2b szkoły ponadgimnazjalnej, -pola: imie i nazwisko typu

                                                tekstowego oraz id i id_klasy typu liczbowego, -pole id_klasy jest

                                                kluczem obcym powiązanym z kluczem podstawowym tabeli klasa. <li>Tabela

                                                    wychowawca</li> -przechowuje: informacje o wychowawcach klas 1a, 1b,

                                                2a i 2b, -pola: imie i nazwisko typu tekstowego oraz id i id_klasy typu

                                                liczbowego, -pole id_klasy jest kluczem obcym powiązanym z kluczem

                                                podstawowym tabeli klasa. <li>Tabela klasa</li> -przechowuje: informacje

                                                o klasach 1a, 1b, 2a i 2b, -pola: nazwa typu tekstowego oraz id i

                                                il_uczniow typu liczbowego.

                                            </ul>



                                            <h5>Zapytania do bazy danych</h5>

                                            <p>Za pomocą narzędzia XAMPP Control Panel uruchom usługi Apache oraz MySQL,

                                                przejdź do narzędzia phpMyAdmin. Wykonaj następujące czynności:</p>

                                            <ul>

                                                <li>Utwórz bazę danych o nazwie <i>szkola</i>,</li>

                                                <li>Do bazy szkola zaimportuj tabele z pliku <i>zkola.sql</i> z

                                                    wcześniej rozpakowanego archiwum,</li>

                                                <li>W podfolderze baza utwórz plik <i>zapytania.txt</i>,</li>

                                                <li>Zapisz i wykonaj zapytania SQL działające na bazie szkola. Zapytania

                                                    zapisz w pliku <i>kwerendy.txt</i>, w podfolderze baza. Wykonaj

                                                    zrzuty ekranu przedstawiające wyniki działania kwerend. Zrzuty

                                                    zapisz w formacie PNG, w podfolderze baza jako: <i>kwerenda1.png,

                                                        kwerenda2.png, nowy_uzytkownik.png i uprawnienia.png</i>. Zrzuty

                                                    powinny obejmować cały ekran monitora z widocznym paskiem zadań.

                                                </li>

                                                <li>Zapytanie 1: zapisujące w tabeli wychowawca rekord danych: id=5,

                                                    imie=Maciej, nazwisko=Stasiak, id_klasy=5,</li>

                                                <li>Zapytanie 2: wybierające jedynie imiona i nazwiska uczniów, których

                                                    wychowawczyni nazywa się Michalska,</li>

                                                <li>Zapytanie 3: tworzące użytkownika <b>K_Pietkiewicz</b> na localhost

                                                    z hasłem <b>kp_123</b></li>

                                                <li>Zapytanie 4: nadające prawa dla użytkownika <b>K_Pietkiewicz</b>

                                                    wybierania i dodawania danych dla tabeli uczen,</li>

                                                <li>Wyeksportuj bazę danych do pliku o nazwie <i>szkola_nowa.sql</i>,

                                                    plik eksportu umieść w podfolderze <i>baza</i>.</li>

                                            </ul>



                                            <h5>Witryna internetowa</h5>

                                            <p>Stwórz prostą witrynę składającą się z jednej strony internetowej o

                                                nazwie <i>index.html</i>. Plik zapisz w podfolderze www (który znajduje

                                                się w folderze nazwanym Twoim numerem PESEL). Wygląd witryny jest zgodny

                                                z Obrazem 1.</p>

                                            <div class="img-wrapper-exam"> <a href="file/img/2018/E.14-08-18.01/1.png" style="margin-left: auto; margin-right: auto;" target="_blank"><img src="file/img/2018/E.14-08-18.01/1.png">

                                                    <div class="subtitle-img">Obraz 1</div>

                                                </a> </div>





                                            <h5>Przygotowanie grafik:</h5>

                                            <p>Wykorzystując zrzuty ekranowe kwerend przygotuj grafiki dla witryny

                                                internetowej:</p>

                                            <ul>

                                                <li>zrzuty ekranowe wykadruj tak, aby były widoczne tylko efekty

                                                    działania zapytań, nie powinny być widoczne inne elementy okna

                                                    przeglądarki oraz panelu phpMyAdmin,</li>

                                                <li>przeskaluj obrazy tak, aby ich szerokość wynosiła 400 px, a wysokość

                                                    200 px,</li>

                                                <li>obrazy zapisz w formacie JPG, w podfolderze <i>www</i>, jako

                                                    <i>kwerenda1.jpg, kwerenda2.jpg, nowy_uzytkownik.jpg i

                                                        uprawnienia.jpg</i></li> <b>UWAGA:</b> <i>pliki z podfolderu

                                                    baza pozostaw niezmienione, nie nadpisuj ich.</i>

                                            </ul>



                                            <h5>Cechy witryny:</h5>



                                            <ul>

                                                <li>zastosowano właściwy standard kodowania polskich znaków,</li>

                                                <li>tytuł strony: „Szkoła ponadgimnazjalna”,</li>

                                                <li>strona podzielona za pomocą znaczników sekcji na baner, panele lewy

                                                    i prawy oraz stopkę, tak aby po uruchomieniu strony w przeglądarce

                                                    wygląd był zgodny z obrazem 1,</li>

                                                <li>zawartość banera: nagłówek pierwszego stopnia o treści: „Projekt

                                                    strony internetowej szkoły ponadgimnazjalnej”,</li>

                                                <li>zawartość panelu lewego:</li> -nagłówek trzeciego stopnia o treści:

                                                „Do pobrania”, -poniżej w postaci listy punktowanej dwa odnośniki: <ol style="margin: 0px;">

                                                    <li>„zapytania SQL”,</li>

                                                    <li>„baza danych”,</li>

                                                </ol> -kliknięcie odnośnika o treści: „zapytania SQL”, powoduje

                                                pobranie/wyświetlenie pliku zapytania.txt z podfolderu baza, -kliknięcie

                                                odnośnika o treści: „baza danych”, powoduje pobranie/wyświetlenie pliku

                                                szkola_nowa.sql z podfolderu baza, -poniżej linia pozioma przez całą

                                                szerokość panelu lewego, -poniżej napis w nagłówku trzeciego stopnia:

                                                „Wyznaczanie najwyższej średniej”, -poniżej lista punktowana z

                                                nazwiskami: Polak, Nowak, Rysik, obok każdego nazwiska pole edycyjne

                                                typu tekstowego przeznaczone na wpisanie średniej ocen ucznia, -poniżej

                                                przycisk z etykietą „wyznacz”, -poniżej napis w nagłówku trzeciego

                                                stopnia „Najwyższa średnia:”, <li>zawartość panelu prawego:</li> -tabela

                                                o rozmiarach 5 wierszy i 2 kolumny, -szerokość prawej kolumny tabeli:

                                                405 px, -komórki wiersza nagłówkowego zawierają kolejno wpisy: „Treść

                                                zapytania” i „Zrzut ekranu”, -w komórkach tabeli w kolejnych wierszach:

                                                treści zapytań z pliku zapytania.txt i obok odpowiadające im zrzuty

                                                ekranu w formacie JPG zgodnie z obrazem 1, -obrazy powinny posiadać

                                                tekst alternatywny zawierający nazwę pliku, <li>zawartość stopki:</li>

                                                -nagłówek czwartego stopnia o treści: „stronę wykonał: ………….”, w miejsce

                                                kropek wpisany Twój numer PESEL.

                                            </ul>



                                            <h5>Styl CSS witryny internetowej</h5>

                                            <p>Styl elementów witryny zdefiniuj przy pomocy języka CSS, w osobnym pliku

                                                o nazwie <i>styl.css</i>, plik ten zapisz w podfolderze <i>www</i> oraz

                                                prawidłowo dołącz do pliku z kodem strony.</p>

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

                                                <li>wszystkie komórki tabeli obramowane ramką czarną kropkowaną

                                                    szerokości 1 px,</li>

                                                <li>włączone paski przewijania dla panelu prawego,</li>

                                            </ul>





                                            <h5>Skrypt wyznaczający najwyższą średnią ocen </h5>



                                            <ul>

                                                <li>wykonywany po stronie klienta,</li>

                                                <li>powinien wykonywać działania na liczbach rzeczywistych,</li>

                                                <li>po kliknięciu przycisku „wyznacz” skrypt pobiera dane z trzech pól

                                                    edycyjnych typu tekstowego,</li>

                                                <li>jeżeli przynajmniej jedno z pól jest puste lub do któregoś pola

                                                    wpisano ciąg znaków, który nie jest poprawną liczbą rzeczywistą

                                                    skrypt powinien wyświetlić w osobnym oknie komunikat „wpisz poprawne

                                                    dane”,</li>

                                                <li>w przeciwnym przypadku skrypt powinien przekonwertować ciągi znaków

                                                    na liczby rzeczywiste,</li>

                                                <li>następnie skrypt powinien wyznaczyć najwyższą spośród trzech

                                                    średnich ocen,</li>

                                                <li>na koniec skrypt powinien wyświetlić wyznaczoną najwyższą średnią

                                                    poniżej napisu „Najwyższa średnia” w lewym panelu.</li>

                                            </ul>

                                            <p><b>UWAGA:</b> <i> po zakończeniu pracy nagraj płytę z rezultatami pracy.

                                                    W folderze z Twoim numerem PESEL powinny się znajdować podfoldery:

                                                    baza oraz www. W podfolderze baza powinny znajdować się pliki:

                                                    szkola_nowa.sql, zapytania.txt, kwerenda1.png, kwerenda2.png,

                                                    nowy_uzytkownik.png i uprawnienia.png. W podfolderze www powinny

                                                    znajdować się pliki: kwerenda1.jpg, kwerenda2.jpg,

                                                    nowy_uzytkownik.jpg i uprawnienia.jpg oraz index.html, styl.css,

                                                    ewentualnie inne przygotowane pliki.</i></p><i>

                                            </i><p><i>Utwórz plik tekstowy. Zapisz w nim nazwę przeglądarki internetowej w

                                                której weryfikowałeś poprawność działania witryny. Zapisz go na płycie

                                                jako przegladarka.txt. Po nagraniu płyty, sprawdź poprawność nagrania.

                                                Opisz płytę swoim numerem PESEL i pozostaw zapakowaną w pudełku na

                                                stanowisku.</i></p>





                                            <p><b>Czas przeznaczony na wykonanie zadania wynosi 150 minut.</b></p>

                                            <p><b>Ocenie będzie podlegać 5 rezultatów:</b></p>

                                            <ul>

                                                <li>operacje na bazie danych,</li>

                                                <li>witryna internetowa,</li>

                                                <li>styl CSS witryny internetowej,</li>

                                                <li>skrypt.</li>

                                            </ul>



                                            <div class="info-wrapper-exam">

                                                PODANE ROZWIĄZANIE JEST TYLKO PRZYKŁADEM.

                                            </div>

                                        </div>

                                    </div>
