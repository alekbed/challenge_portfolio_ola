# challenge_portfolio_ola

<h2>TASK 1</h2>

<h3>Subtask 1</h3>
3 punkty 😲

<h3>Subtask 3</h3>
Zdecydowałam się na udział w wyzwaniu, aby przekonać się, jak zadania testera wyglądają w praktyce. W przyszłości chciałabym pracować na tym stanowisku.

<h3>Subtask 4</h3>

Aplikacja skierowana jest do skautów piłkarskich. Służy do zarządzania danymi o zawodnikach. Ma dwie wersje językowe: polski i angielski.
Do używania aplikacji wymagane jest zalogowanie. Po zalogowaniu użytkownik zostaje przekierowany do strony głównej aplikacji. W panelu głównym użytkownik widzi u góry kilka statystyk, tj:
- liczba graczy
- liczba meczy
- liczba wygenerowanych raportów
- oraz liczba akcji wykonanych w aplikacji.

Poniżej statystyk od lewej strony znajduje się kafel z odnośnikiem do kontaktu z zespołem developerskim, obok kafel z odnośnikiem do formularza dodawania nowego gracza oraz kafel z listą ostatnio wykonanych akcji.

Użytkownik może dodawać nowych graczy oraz przeglądać i edytować istniejących. Nie ma możliwości usuwania graczy.
Profil gracza przechowuje różne informacje o graczu:
- imię, nazwisko, data urodzenia i dane kontaktowe
- cechy fizyczne jak wzrost i waga, dominująca noga
- nazwa klubu, pozycja główna i alternatywna, poziom rozgrywek, osiągnięcia zawodnika
- linki do profili na portalach sportowych i społecznościowych

Listę zawodników można wyeksportować do pliku csv lub wydrukować. Listę można też przefiltrować po kilku cechach.

Dla każdego zawodnika można dodać mecze, w których brał udział. W podstawowym formularzu meczu można dodać różne dane na temat rozgrywki, np. datę, typ meczu oraz na temat gry zawodnika w meczu, np. czas i recenzję gry. Do meczu można dodać akcje zawodnika w danym meczu, takie jak np. faule, strzały na bramkę. Są one wyświetlane w liście akcji danego meczu.
Dla każdego meczu można wygenerować raport z wprowadzonymi wcześniej danymi i statystykami i uzupełnić go o dane opisowe występu zawodnika.

Aplikacja ma według mnie przejrzysty interfejs.

Nieintuicyjnie działa plansza do dodawania akcji: 
- wyświetlenie kafli akcji możliwe jest tylko przy uruchomionym liczniku czasu, następnie należy manualnie zapauzować licznik. Lepszym rozwiązaniem byłoby automatyczne zatrzymanie czasu po ukazaniu się kafli/możliwość edycji czasu.
- liczba części meczu, powinny 2 połowy
- nie działa przycisk do usuwania zdarzeń na planszy
