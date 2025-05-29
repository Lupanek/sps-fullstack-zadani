# Další témata Fullstack aplikací



---



### 1. Rezervační systém na sportoviště
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Uživatelé mohou rezervovat sportoviště v různých časech.

- **Tabulka** – `sports` – seznam sportovišť
- **Tabulka** – `reservations` – rezervace


- **CRUDL (editovatelné)**: sports, reservations

### 2. Správa jídelníčku ve školní jídelně
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence jídel a jejich kategorií, možnost aktualizace jídelníčku.

- **Tabulka 1** - `meals`
- **Tabulka 2** - `categories`


- **CRUDL (editovatelné)**: meals, categories

### 3. Evidence návštěvníků muzea
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam návštěvníků a jejich návštěv jednotlivých expozic.

- **Tabulka 1** - `visitors`
- **Tabulka 2** - `exhibits`



- **CRUDL (editovatelné)**: visitors, exhibits
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 4. Správa domácích mazlíčků v útulku
Útulek spravuje zvířata a jejich majitele.

- **Tabulka 1** - `pets`
- **Tabulka 2** - `owners`


- **CRUDL (editovatelné)**: pets, owners

### 5. Správa kurzů v jazykové škole
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam kurzů, lektorů a přihlášených studentů.

- **Tabulka 1** - `courses`
- **Tabulka 2** - `teachers`



- **CRUDL (editovatelné)**: courses, teachers
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 6. Správa aut v autopůjčovně
Půjčovna eviduje auta, zákazníky a výpůjčky.

- **Tabulka 1** - `cars`
- **Tabulka 2** - `customers`
- **Tabulka 3** - `rentals`


- **CRUDL (editovatelné)**: cars, customers
- **Neměnitelná tabulka (seedovaná při spuštění)**: rentals

### 7. Sklad náhradních dílů
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence dílů, dodavatelů a objednávek.

- **Tabulka 1** - `parts`
- **Tabulka 2** - `suppliers`



- **CRUDL (editovatelné)**: parts, suppliers
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 8. Systém hodnocení restaurací
Uživatelé hodnotí restaurace a přidávají komentáře.

- **Tabulka 1** - `restaurants`
- **Tabulka 2** - `reviews`


- **CRUDL (editovatelné)**: restaurants, reviews

### 9. Správa inventáře kanceláře
Sledování zásob, kategorií a dodavatelů.

- **Tabulka 1** - `items`
- **Tabulka 2** - `categories`
- **Tabulka 3** - `suppliers`


- **CRUDL (editovatelné)**: items, categories
- **Neměnitelná tabulka (seedovaná při spuštění)**: suppliers

### 10. Evidence úkolů v týmu
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Správa projektových úkolů, přiřazení k členům týmu.

- **Tabulka 1** - `tasks`
- **Tabulka 2** - `team_members`



- **CRUDL (editovatelné)**: tasks, team_members
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 11. Správa parkovacích míst v garáži
Rezervace a správa parkovacích míst.

- **Tabulka 1** - `parking_spots`
- **Tabulka 2** - `reservations`


- **CRUDL (editovatelné)**: parking_spots, reservations

### 12. Katalog filmů a hodnocení
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence filmů a uživatelských hodnocení.

- **Tabulka 1** - `movies`



- **CRUDL (editovatelné)**: movies

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 13. Správa fitness centra
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam členů, cvičebních plánů a rezervací lekcí.

- **Tabulka 1** - `members`
- **Tabulka 2** - `workout_plans`



- **CRUDL (editovatelné)**: members, workout_plans
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 14. Evidence návštěv v zoo
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam návštěvníků a zvířat, která viděli.

- **Tabulka 1** - `visitors`
- **Tabulka 2** - `animals`



- **CRUDL (editovatelné)**: visitors, animals
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 15. Správa knih v antikvariátu
Evidování knih, autorů a žánrů.

- **Tabulka 1** - `books`
- **Tabulka 2** - `authors`
- **Tabulka 3** - `genres`


- **CRUDL (editovatelné)**: books, authors
- **Neměnitelná tabulka (seedovaná při spuštění)**: genres

### 16. Systém správy konferencí
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence konferencí, řečníků a účastníků.

- **Tabulka 1** - `conferences`
- **Tabulka 2** - `speakers`



- **CRUDL (editovatelné)**: conferences, speakers
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 17. Správa objednávek v e-shopu
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam produktů, zákazníků a objednávek.

- **Tabulka 1** - `products`
- **Tabulka 2** - `customers`



- **CRUDL (editovatelné)**: products, customers
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 18. Evidence darů pro charitu
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam dárců a darovaných věcí.

- **Tabulka 1** - `donors`
- **Tabulka 2** - `donations`


- **CRUDL (editovatelné)**: donors, donations

### 19. Správa recepce hotelu
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence pokojů, hostů a rezervací.

- **Tabulka 1** - `rooms`
- **Tabulka 2** - `guests`



- **CRUDL (editovatelné)**: rooms, guests
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 20. Správa zaměstnanců firmy
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam zaměstnanců, oddělení a projektů.

- **Tabulka 1** - `employees`
- **Tabulka 2** - `departments`
- **Tabulka 3** - `projects`


- **CRUDL (editovatelné)**: employees, departments
- **Neměnitelná tabulka (seedovaná při spuštění)**: projects

### 21. Správa školních tříd
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence tříd, žáků a třídních učitelů.

- **Tabulka 1** - `classes`
- **Tabulka 2** - `students`



- **CRUDL (editovatelné)**: classes, students
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 22. Správa výpůjček v knihovně
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam čtenářů, knih a výpůjček.

- **Tabulka 1** - `readers`
- **Tabulka 2** - `books`



- **CRUDL (editovatelné)**: readers, books
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 23. Správa soutěžících v soutěži
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence soutěžících, kategorií a výsledků.

- **Tabulka 1** - `contestants`
- **Tabulka 2** - `categories`



- **CRUDL (editovatelné)**: contestants, categories
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 24. Správa objednávek v restauraci
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam jídel, stolů a objednávek.

- **Tabulka 1** - `dishes`
- **Tabulka 2** - `tables`



- **CRUDL (editovatelné)**: dishes, tables
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 25. Správa návštěv v nemocnici
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam pacientů, lékařů a návštěv.

- **Tabulka 1** - `patients`
- **Tabulka 2** - `doctors`



- **CRUDL (editovatelné)**: patients, doctors
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 26. Správa vozového parku firmy
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence vozidel, řidičů a jízd.

- **Tabulka 1** - `vehicles`
- **Tabulka 2** - `drivers`



- **CRUDL (editovatelné)**: vehicles, drivers
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 27. Správa inventáře ve skladu knih
Evidování knih, skladových míst a zásob.

- **Tabulka 1** - `books`
- **Tabulka 2** - `locations`



- **CRUDL (editovatelné)**: books, locations
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 28. Správa projektů a úkolů
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence projektů, úkolů a členů týmu.

- **Tabulka 1** - `projects`
- **Tabulka 2** - `tasks`
- **Tabulka 3** - `team_members`



- **CRUDL (editovatelné)**: projects, tasks

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 29. Správa objednávek květin
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Záznam květin, zákazníků a objednávek.

- **Tabulka 1** - `flowers`
- **Tabulka 2** - `customers`



- **CRUDL (editovatelné)**: flowers, customers
- **Neměnitelná tabulka (seedovaná při spuštění)**: 

- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.

### 30. Správa kurzů a studentů
Při inicializaci systému se připraví výchozí data do neměnitelných tabulek. Uživatelé budou moci spravovat pouze editovatelné položky přes CRUD rozhraní.

Evidence kurzů, studentů a jejich zápisů.

- **Tabulka 1** - `courses`
- **Tabulka 2** - `students`


---



- **CRUDL (editovatelné)**: courses, students
- **Neměnitelná tabulka (seedovaná při spuštění)**: 
- **Poznámka**: V systému může být vztah typu M:N reprezentovaný pomocí pomocné tabulky.
