Spring Project Exercise
Projekt "Hello Vistula" to prosta aplikacja stworzona w oparciu o framework Spring, która pozwala użytkownikowi korzystać z dwóch stron internetowych. Celem projektu jest przedstawienie podstawowych funkcji Springa oraz zastosowanie silnika szablonów Thymeleaf. Aplikacja umożliwia wyświetlanie komunikatu powitalnego na stronie głównej oraz personalizację powitania na drugiej stronie poprzez podanie imienia.

Funkcje
Strona główna ("/")
Po otwarciu strony głównej użytkownik zobaczy następujący komunikat:

"Hello Vistula, in my first Spring controller!"

Strona powitalna ("/greeting")
Na tej stronie użytkownik może wpisać swoje imię, dodając je jako parametr w URL, np.:

http://localhost:8080/greeting?name=Jan

W odpowiedzi aplikacja wyświetli powitanie spersonalizowane dla danego imienia:

"Hello, Jan!"

Jeżeli imię nie zostanie podane, aplikacja wyświetli domyślne powitanie:

"Hello, World!"

Obrazek
Na stronie powitalnej znajduje się również obrazek przedstawiający słynny obraze raper Drake z memów, który jest pobierany z zewnętrznego źródła:

https://www.stickpng.com/img/download/5ee771dc99588c0004aa6849

Wykorzystane technologie

Spring Boot – framework użyty do budowy aplikacji po stronie serwera.
Thymeleaf – narzędzie do generowania dynamicznego HTML na podstawie danych z kontrolera.
Java – język programowania, w którym zaimplementowano logikę aplikacji.





