1. Filesystem sync - Połącz dwa pliki z response  w jeden result. Do ścieżek do odczytu plików użyj modułu path.

2. Filesystem async - Połącz dwa pliki z response  w jeden result. Do ścieżek do odczytu plików użyj modułu path. Użyj funkcji asynchronicznych do odczytu i zapisu plików, tj readFile i writeFile.

3. HTTP server - Stwórz prosty serwer HTTP, który zostanie uruchomiony na portcie 3000 i będzie serwował 3 strony z nagłówkami H1 z tekstami jak na załączonym obrazku. 
- Strona główna  - status 200
- Strona contact - status 226
- Strona błędu w przypadku kiedy ktoś wpisze zły adres  - status 404
Strony powinny być rozróżniane na podstawie wpisanego URL. Serwer powinien zostać wykonany przy pomocy natywnego modułu HTTP W przypadku próby dostania się pod adres, który nie istnieje  - to zdarzenie powinno zostać zalogowane do pliku server.log. Każda kolejna próba otworzenia nieistniejącej strony powinna dodawać wpis w pliku server.log Wpis powinien wyglądać następująco: [dzień-miesiąc-rok godzina-minuta] - Bad request to URL [adres na który ktoś próbował się dostać] - Requested from [adres IP klienta]

4. Create the same server as it is in previous Exercises from node using Express JS. Additionally servers should start serve HTML files from pages directory. For example when user visits /contact page - server should serve contact.html file.

