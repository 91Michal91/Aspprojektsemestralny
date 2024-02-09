
Projekt "Reservation" to system rezerwacji stworzony z wykorzystaniem ASP.NET Core 7.0 i 
Entity Framework Core z bazą danych SQLite, wspierany przez Microsoft Identity dla zarządzania użytkownikami i 
Bootstrap do stylizacji interfejsu. Umożliwia on zarządzanie danymi dotyczącymi rezerwacji, oferując funkcje takie jak wyszukiwanie, 
sortowanie i stronicowanie rezerwacji, a także zapisywanie danych w bazie za pomocą Entity Framework. Dostęp do formularzy realizujących operacje 

CRUD (Create, Read, Update, Delete) oraz widoków z listami obiektów jest ograniczony tylko dla administratora, podczas gdy system zarządza dwoma
rolami użytkowników: administrator i zwykły użytkownik. Projekt obejmuje również moduł testów jednostkowych dla kontrolerów, asynchroniczne operacje
dla lepszej wydajności oraz dostosowany wygląd strony przy użyciu Tailwind CSS. 
Dodatkowo, wprowadzono kontroler WEBAPI do udostępniania wybranych danych, co ułatwia integrację z zewnętrznymi systemami.
