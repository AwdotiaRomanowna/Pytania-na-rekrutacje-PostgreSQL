# Pytania na rekrutację PostgreSQL
====================================================
## <a name='toc'>Spis treści</a>

####[[⬆]](#toc) <a name='general'>Pytania ogólne:</a>
* Czego nowego dowiedziałeś się ostatnio o postgresie?
* Jakich narzędzi używasz?
* Która cecha postgresa wydaje ci się jego największym atutem?
* Które blogi uwaszasz za najbardziej wartościowe?
* Od której strony nie zajmowałeś się jeszcze postgresem?
* Co uważasz za "dobrą praktykę" w pisaniu SQL-i?
* Co uważasz za "dobrą praktykę" w projektowaniu bazy?
* Jak podchodzisz do wersjonowania bazy?

####[[⬆]](#toc) <a name='administracja'>Administracja:</a>
* Jak zaplanowałbyś politykę backupu dla 20TB bazy OLTP?
* Kiedy należy użyć VACUUM FULL?
* Które parametry zmieniasz przy nowej instalacji klastra?

####[[⬆]](#toc) <a name='administracja'>Tuning zapytań:</a>


####[[⬆]](#toc) <a name='tuning'>Tuning serwera:</a>
* Jedno z zapytań trwa około 20 minut zajmując bardzo dużo czasu procesora. co zrobisz?
* Co to jest work_mem i jak go ustawisz?
* Jak ustawisz shared_buffers dla bazy z 6TB pamięci RAM?
* Czy operacja index scan wiąże się z dostępem do tabeli, na której założony jest indeks?
* Jakie według ciebie konstrukcje SQL powodują największe obciążenie dla bazy?
* Rozszyfruj skrót HOT i powiedz za pomocą jakiego parametru się go tuninguje
* Jakie znasz mechanizmy wspomagające checkpoint?



####[[⬆]](#toc) <a name='tuning'>Zaawansowane</a>
* Czym może skutkować zbyt wysokie ustawienie shared buffers?
* Czym może skutkować zbyt niskie ustawienie shared buffers?
* Jakie znasz "fizyczne" JOIN-y?
* Czego nie chciałbyś zobaczyć w EXPLAIN-ie zapytania operującego na dużych wolumenach danych?
* Jak można, alternatywnie do SELECT count(*), zweryfikować liczbę wierszy w tabeli? 