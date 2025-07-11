# Témata Fullstack aplikací
## Doporučený TechStack
- **Frontend**: HTML, CSS, JavaScript
  - Chceš si okořenit život? *React/Vue, TailwindCSS...*
- **Backend**: Node.js, Express, Sqlite3
- **Ostatní**: Git, Postman, VSCode
  - Chceš psát hezký kód? *Biome*

## Povinná struktura

Na GitHubu nechci vidět žádné `node_modules`, `.vscode`, `package-lock.json`, ...

```js
nazev-projektu
│   README.md
│   .gitignore
│   package.json
│
└───public
│   │   index.html
│   │   další html soubory
│   │
│   └───assets
│       │   místo pro obrázky, styles.css...
│   
└───api
│   │   nějaký js soubor s routováním
│   
└───database
│   │   db.js       // Database connection logic
│   │   schema.sql  // Schema definition
│   │   seed.js     // Script for seeding the database
│   │   seed.sql    // Seed data (INSERT statements)
│   
│   server.js
```

- `README.md` - popis projektu, jak ho spustit, co dělá, ...
- `.gitignore` - ignorujeme všechny složky, které nechceme commitovat
- `package.json` - dependencies, scripts, ...
- `public` - statické soubory, které chceme poslat klientovi
  - `index.html` - hlavní stránka
  - `další html soubory` - další stránky
  - `assets` - obrázky, styles.css, ...
- `api` - složka pro backend
  - `nějaký js soubor s routováním` - soubor, který obsahuje všechny routy
- `database` - složka pro databázi
  - `db.js` - soubor, který obsahuje logiku pro připojení k databázi
  - `schema.sql` - soubor, který obsahuje definici schématu databáze
  - `seed.js` - soubor, který obsahuje logiku pro naplnění databáze daty
  - `seed.sql` - soubor, který obsahuje samotná data pro naplnění databáze
- `server.js` - hlavní spouštěcí soubor, který obsahuje všechny routy a nastavení serveru

## Témata
Každé z témat je víceméně nějaký uživatelský formulář který dovoluje dělat CRUDL operace na 2-3 tabulkách. Tabulky jsou vždy propojeny cizím klíčem, je potřeba správně určit datové typy polí a přidat primární klíče. Při spuštění aplikace se databáze inicializuje a naplní nějakými ukázkovými daty. 
CRUDL znamená, že má uživatel možnost vykonat operace
- Create
- Read
- Update
- Delete
- List (Read All)

### 1. Zasedací pořádek
Učitelé potřebují systém, kde mohou:
- spravovat (CRUDL) své předměty
- spravovat (CRUDL) kteří žáci sedí na kterých místech.
Počítejte, že učitel učí pouze v jedné třídě, která má pevně daný počet míst (bude nakrmeno při seedingu)

- **Tabulka 1** - `subjects` - seznam předmětů
  - `name` - název předmětu
  - `code` - zkratka předmětu
- **Tabulka 2** - `places` - seznam míst v třídě
  - `name` - název místa
  - `row` - řádek
  - `column` - sloupec
- **Tabulka 3** - `seating_plans` - seznam zasedání žáků na místech
  - `firstname` - jméno žáka
  - `lastname` - příjmení žáka

### 2. Knihovna
Knihovna potřebuje systém, kde mohou:
- spravovat (CRUDL) knihy, zařazovat je do žánrů
- spravovat (CRUDL) autory
Počítejte, že žánry jsou pevně dané a nebudou se měnit.

- **Tabulka 1** - `books` - seznam knih
  - `title` - název knihy
- **Tabulka 2** - `authors` - seznam autorů
  - `firstname` - jméno autora
  - `lastname` - příjmení autora
  - `nationality` - národnost autora
- **Tabulka 3** - `genres` - seznam žánrů
  - `name` - název žánru

