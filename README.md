# SQL_journey
My personal SQL journal and knowledge refresher. This repository serves as a permanent log of all the SQL commands, concepts, and tricky queries I've learned, helping me revisit key concepts quickly.


# 📓 SQL Journey: The Definitive Learning Log

## 🚀 Wprowadzenie

Ten katalog jest moim osobistym **Dziennikiem SQL (SQL Journal)** oraz zbiorem szybkich przypominaczy (**Knowledge Refresher**). Służy jako stały rejestr wszystkich komend, koncepcji i trudniejszych zapytań, które poznałem.

Głównym celem jest:
1.  **Utrwalenie Wiedzy:** Przechowywanie praktycznych przykładów na szybkie odtworzenie składni.
2.  **Śledzenie Postępu:** Dokumentowanie przejścia od podstawowych zapytań `SELECT` do zaawansowanych funkcji okienkowych.
3.  **Wielodostępność:** Używam tego jako głównego punktu odniesienia, niezależnie od tego, z jakim dialektem SQL aktualnie pracuję (np. PostgreSQL, SQLite, MySQL).

## ⚙️ Struktura Repozytorium

Zapytania i skrypty są pogrupowane tematycznie, aby ułatwić szybkie odnajdywanie konkretnych zagadnień.

| Folder | Zawartość | Cel |
| :--- | :--- | :--- |
| `01_SETUP/` | Skrypty DDL. | Tworzenie baz danych, tabel i definiowanie relacji. |
| `02_BASICS/` | Podstawowe zapytania. | `SELECT`, `FROM`, `WHERE`, `ORDER BY`, filtrowanie i sortowanie danych. |
| `03_DATA_MANIPULATION/` | Skrypty DML. | Wstawianie, aktualizowanie i usuwanie danych (`INSERT`, `UPDATE`, `DELETE`). |
| `04_JOINS_AND_RELATIONS/` | Łączenie danych. | Przykłady relacji: `INNER`, `LEFT`, `RIGHT`, `FULL` join. |
| `05_AGGREGATION_AND_GROUPING/` | Funkcje agregujące. | Użycie `COUNT`, `SUM`, `AVG`, `GROUP BY`, `HAVING`. |
| `06_ADVANCED/` | Zaawansowane tematy. | CTEs, funkcje okienkowe, transakcje. |
| `DATA/` | Pliki źródłowe. | Pliki `.csv` lub `.json` używane do importu i testowania zapytań. |
| `NOTES/` | Notatki tekstowe. | Różnice dialektów, ściągawki ze składni. |

## 🎯 Obecny Cel i Zadanie Startowe

### Zadanie Startowe: **Baza Filmów**

Zadaniem wprowadzającym było stworzenie prostej tabeli do śledzenia ulubionych filmów. Odpowiednie skrypty znajdują się w:
* `01_SETUP/create_films_table.sql`
* `03_DATA_MANIPULATION/insert_films.sql`
* `02_BASICS/list_all_films.sql`

### 🚧 Plan na Kolejny Tydzień

* [ ] Ukończenie wszystkich ćwiczeń w folderze `02_BASICS/`.
* [ ] Zrozumienie różnicy między `WHERE` a `HAVING`.
* [ ] Dodanie przykładów `LEFT JOIN` do folderu `04_JOINS_AND_RELATIONS/`.
* [ ] Dodanie notatki o typach danych w pliku `NOTES/`.
