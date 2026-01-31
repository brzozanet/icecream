# 🍦 Projekt Ice Cream

### Projekt grupowy GoIT fullstack developer course

Strona internetowa dla firmy produkującej lody, zbudowana przy użyciu HTML, SASS i JavaScript. Strona wykonana jako SPA (_single-page-application_). Zawiera trzy główne działy: _About Us_, _How it's made?_ oraz _Our products_ oraz _Contact_. W pełni responsywny projekt powstał w oparciu o strategię _Mobile First_ w celu poprawy doświadczeń użytkownika na urządzeniach mobilnych, poprawę pozycjonowania w wynikach wyszukiwania, szybsze ładowanie stron, elastyczność i skalowalność oraz minimalizację zbędnych elementów. Zastosowanie preprocesora SASS spowodowało większą zwięzłość i czytelność kodu, możliwość wprowadzenia zmiennych oraz obsługi zagnieżdżania oraz modularność. Bundling aplikacji wykonany za pomoca Parcel, służącego do automatyzacji procesu budowania i dostarczania plików źródłowych (np. JavaScript, CSS, obrazy) do produkcji.

## 🌐 Demo

Zobacz stronę online: [Ice Cream Project](https://brzozanet.github.io/icecream/)

## 🛠 Użyte technologie

- **HTML5** (struktura strony)
- **CSS3** (stylowanie z wykorzystaniem metodologii BEM)
- **SASS** (preprocesor CSS dla lepszej organizacji stylów)
- **Flexbox** (elastyczny układ strony)
- **JavaScript** (interaktywność strony)
- **Node.js** (środowisko uruchomieniowe)
- **Parcel** (bundler)
- **Swiper.js** (do karuzeli)
- **PostHTML** (do includów)
- **Figma** (projekt graficzny)
- **Git & GitHub** (kontrola wersji i hosting)

## 📂 Struktura projektu

```
icecream/
├── src/
│   ├── index.html
│   ├── index.js
│   ├── images/
│   └── sass/
│       ├── main.scss
│       └── components/
├── package.json
└── README.md
```

## 📱 Dostępne strony i funkcje

- **Strona Główna** - Landing page z sekcją hero
- **O Nas** - Informacje o firmie
- **Jak To Jest Robione** - Opis procesu produkcji
- **Nasze Produkty** - Katalog produktów
- **Kontakt** - Informacje kontaktowe i formularz
- Responsywny design dla wszystkich urządzeń
- Interaktywna galeria
- Karuzela z opiniami klientów
- Formularz kontaktowy z walidacją
- Nawigacja przyjazna urządzeniom mobilnym

## 📱 Responsywność

Strona jest w pełni responsywna i dostosowana do następujących breakpointów:

- Mobile: < 768px
- Tablet: 768px - 1199px
- Desktop: ≥ 1200px

## 🔍 SEO i Wydajność

- Zoptymalizowane obrazy
- Semantyczny HTML
- Szybkie ładowanie strony
- Mobile-first approach
- Dostępność (WCAG)

## 🚀 Jak rozpocząć

### Wymagania

- Node.js (wersja 12 lub wyższa)
- npm (Node Package Manager)

### Uruchomienie wersji developerskiej

1. Sklonuj repozytorium

   ```bash
   git clone https://github.com/brzozanet/icecream.git
   ```

2. Przejdź do katalogu projektu

   ```bash
   cd icecream
   ```

3. Zainstaluj zależności
   ```bash
   npm install
   ```

Aby uruchomić serwer deweloperski:

```bash
npm run dev
```

Strona będzie dostępna pod adresem: `http://localhost:1234`

## 🌍 Wdrożenie

Projekt jest skonfigurowany do wdrożenia na GitHub Pages. Po zbudowaniu, strona będzie dostępna pod adresem:
`https://brzozanet.github.io/icecream/`

## 📝 Licencja

Projekt jest objęty licencją ISC.

<br>

![Screenshot App](https://raw.githubusercontent.com/brzozanet/icecream/main/src/images/gh-cover-goit-html-css.png)
