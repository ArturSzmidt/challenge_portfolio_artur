# Task 1

## Subtask 1

5 punktów

## Subtask 3

Cześć, jestem Artur. Biorę udział w portfolio challenge, ponieważ chcę zdobyć doświadczenie i umiejętności potrzebne do rozwijania swojej kariery w tej dziedzinie. Uważam, że praca testera manualnego jest ważna dla zapewnienia jakości oprogramowania i chcę mieć swój udział w tym procesie. Biorąc udział w portfolio challenge, mam okazję rozwinąć swoje umiejętności i wiedzę oraz uczyć się od innych ekspertów w dziedzinie testowania. (_wygenerowane przy użyciu GPT-3_ :see\_no\_evil: )

## Subtask 4

#### Na czym polega ta aplikacja? Do czego służy?

> Aplikacja "Scouts Panel" służy do kompleksowego zarządzania zarządzania sportowcami(grającymi w piłkę nożną).

#### Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił\_a?

> Aplikacja pozwala na utworzenie profilu sportowca. Do karty sportowca można dodać informację: Email, Imię, Nazwisko, Telefon, Waga, Wzrost, data urodzenia, dominująca noga, klub, poziom rozgrywek, główna pozycja, pozycja alternatywna, Województwo(można wybrać), osiągnięcia, jezyk jakim posługuję, "łączy nas piłka", 90 minut, profil facebook, link do youtube.
> 
> Następnie dodanego gracza bądź innego można wyszukać używając panelu do szukania po czym sprawdzić jego informację. Jeżeli to zrobimy mamy dostęp do panelu "Mecze" i panelu "Raporty". 
> 
> W panelu "Mecze" mamy dostęp do informacji(i ich edycji):  Drużyna zawodnika, Zdobyte gole, Stracone gole, Drużyna przeciwnika, data, czas gry, recenzja, autor(autor wpisu, raportu). Następnie w panelu "Akcję" mamy do wyboru: edycję, dodaj raport i rozpocznij mecz.
> 
> Rozpocznij mecz jest symulacją odbytego meczu. Po wciśnięciu klawisza mamy dostęp do prostej symulacji "Meczu". Nad symulacją mamy klawiszę które sugerują że można wcisnąć Play bądź zapauzować symulację. Następnie mamy bliżej nieokreślone guziki które wydają się nie mieć zaimplementowanej funkcjonalności. Jeżeli Wciśniemy guzik sugerujący "start" a następnie "cofnij" możemy wysłać "raport" ostatnim guzikiem. Tak sugeruje komunikat informuje nas "Wysłano poprawnie raport".
> 
> W panelu "Raporty" mamy możliwość dodania raportu ręcznie wciskając guzik "DODAJ RAPORT". Możemy dodać: Drużyna zawodnika, Zdobyte gole, Stracone gole, Drużyne przeciwnika, Datę, Ostatnia Modyfikacja(wypełnia się automatycznie), Autor.  
> Na końcu rubryki mamy ikonę edycji. Gdy w nią klikniemy ukazuję się nam poniższy raport.
> 
> Screenshot:
> 
> ![](https://user-images.githubusercontent.com/80460700/212973485-ca1bd078-2512-41ef-aa31-e0f2127a9d7e.png)
> 
> Powyższy raport można edytować.
> 
> Panel "Gracz" Pozwala nam na przeglądanie listy graczy, pobieranie informacji w formacie CSV, filtrowanie listy na bazie kryteriów(Imię, Nazwisko, Wiek(zakres od - do), Pozycja, Klub, Ocena(zakres od - do)).
> 
> Aplikacja pozwala też na zalogowanie i wylogowanie się.  

#### Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

> Interfejs aplikacji mi się nie podoba.

#### Czy aplikacja jest intuicyjna?

> Aplikacja absolutnie nie jest intuicyjna.

#### Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem?

> Tak, Panel symulacji meczu wydaje się całkowicie bezużyteczny. Na stronie głównej jest komponent "Linki Pomocnicze" informujący "DODAJ GRACZA". Jest to jeden link pomocniczy nie dający możliwości dodania innych skrótów, jest to też jedyne miejsce w którym można dodać gracza.  
> W panelu "Gracze" nie ma możliwości dodania gracza co wydaje się nieintuicyjne.   
> Pola tekstowe w formularzach nie posiadają walidacji, więc można wpisać liczby i inne znaki w imieniu i nazwisku.  
> Podobnie jest z pozycją, można wymyślić własną(powinna być predefiniowana możliwość wyboru), dodając znaki.  
> W polu numerów telefonów też można wpisywać cokolwiek się zapragnie.  
> Link do facebooka i panel dodawania linku youtube nie posiadają walidacji czy są faktycznie linkami, powinny posiadać algorytmy sprawdzające czy są linkami do tego portalu i weryfikować odnośniki( na przykładzie youtube: [https://www.youtube.com/channel/***tutajNazwaUżytkownika\*\*\*](https://www.youtube.com/channel/***tutajNazwaU%C5%BCytkownika***) ).  
> Nie działa wygenerowany link do "meczu" w raporcie (który jest widoczny na powyższym screenshocie).

# Task 2

## Subtask 3

> Test case'y są pisane, aby upewnić się, że opracowywany oprogramowanie lub system działa prawidłowo i spełnia wymagania i oczekiwania końcowego użytkownika. Służą one jako sposób na weryfikację, że oprogramowanie lub system działa zgodnie z zamierzeniem i mogą wykrywać błędy lub problemy, które trzeba rozwiązać przed końcową wersją. Tworząc test case'y, możemy również upewnić się, że oprogramowanie lub system jest niezawodny, wydajny i przyjazny dla użytkownika. Dodatkowo test case'y mogą być używane do oceny wydajności, bezpieczeństwa i zgodności systemu i mogą być używane jako odniesienie do przyszłej konserwacji i aktualizacji.
