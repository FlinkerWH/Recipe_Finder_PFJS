# Recipe_Finder_PFJS
PFJS – Popularne frameworki Java Script, semestr VI

Projekt Recipe Finder

Piotr Pawlak 157852

Michał Urbansky 117141

https://github.com/FlinkerWH/Recipe_Finder_PFJS


REPOZYTORIUM ŹRÓDŁOWE:

https://github.com/FlinkerWH/receptury

VERCAL:

https://receptury-michal-urbanskys-projects.vercel.app/



DOKUMENTACJA:
 1. React
    
Architektura: React to biblioteka JavaScript służąca do budowy interfejsów użytkownika, oparta na komponentach, co umożliwia modularne budowanie aplikacji. React używa deklaratywnego podejścia, co sprawia, że kod jest bardziej przewidywalny i łatwiejszy do debugowania.
Zastosowanie w projekcie:

•	Komponenty: Aplikacja wykorzystuje komponenty React do tworzenia struktury strony, takie jak App, Header, SearchBar, RecipeList oraz RecipeCard.
•	Stan aplikacji: Za zarządzanie stanem aplikacji odpowiada React Hook useState, który pozwala na przechowywanie i aktualizację stanu w komponentach funkcyjnych.

 2. Material-UI
    
Architektura: Material-UI to popularna biblioteka komponentów React, która implementuje Google Material Design. Oferuje gotowe do użycia komponenty UI, które są estetycznie przyjemne i łatwe w integracji.

Zastosowanie w projekcie:

•	Komponenty UI: Aplikacja korzysta z różnych komponentów Material-UI, takich jak AppBar, Box, Toolbar, Typography, TextField, i Button do budowy interaktywnego i responsywnego interfejsu użytkownika.

 3. Emotion
    
Architektura: Emotion to biblioteka umożliwiająca stylizację w JavaScript, oferująca wydajne, skalowalne i elastyczne rozwiązania dla CSS-in-JS. Emotion integruje stylizację bezpośrednio w komponentach React.

Zastosowanie w projekcie:

•	Stylizacja: Za pomocą Emotion (wraz z @emotion/styled) projekt wykorzystuje dynamiczne style CSS bezpośrednio w komponentach React, co umożliwia łatwe stosowanie i modyfikację stylów w zależności od stanu i właściwości komponentów.

 4. Fetch API

Architektura: Fetch API to nowoczesne API dostępne w przeglądarkach do wykonywania operacji HTTP, używane do asynchronicznych zapytań sieciowych.

Zastosowanie w projekcie:

•	Komunikacja z API: SearchBar wykorzystuje Fetch API do asynchronicznego pobierania danych o przepisach kulinarnych z zewnętrznego API, co umożliwia dynamiczne wyszukiwanie i wyświetlanie przepisów kulinarnych na podstawie zapytań użytkownika.

Narzędzia pomocnicze:

•	npm (Node Package Manager): Używany do zarządzania pakietami i zależnościami projektu, co widać w plikach package.json i package-lock.json.
•	Babel: Transpiler JavaScript, który pozwala na użycie nowoczesnej składni JavaScript, zapewniając kompatybilność ze starszymi przeglądarkami.
•	Webpack: Pakowacz modułów używany w react-scripts do optymalizacji i kompilacji zasobów aplikacji.


 EWENTUALNE PROBLEMY I ICH ROZWIĄZANIA

W procesie tworzenia aplikacji wykorzystującej wspomniane frameworki i narzędzia, mogą pojawić się różnorodne problemy techniczne.

 1. Fetch API i zarządzanie stanem asynchronicznym
   
Problem: Zarządzanie asynchronicznym ładowaniem danych z zewnętrznych API, w tym obsługa błędów i stanów ładowania.
Rozwiązanie:

•	React Query: Biblioteka ta oferuje potężne narzędzia do zarządzania stanem asynchronicznym, cache'owania, synchronizacji i aktualizacji danych z API, znacząco upraszczając logikę związaną z asynchronicznymi zapytaniami.

