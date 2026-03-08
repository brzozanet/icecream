# 🍦 Artisanal Ice Cream Manufacturer

![Screenshot App](https://raw.githubusercontent.com/brzozanet/icecream/main/src/images/gh-cover-goit-html-css.png)

Responsywna strona internetowa marki lodów, zbudowana z użyciem HTML, SASS i JavaScript. Projekt opiera się o podejście _Mobile First_ i został zorganizowany modułowo (sekcje strony jako partiale, osobne pliki SCSS i JS dla komponentów/interakcji). Bundling oraz serwer developerski realizowane są przez Parcel.

## 🌐 Demo

Zobacz stronę online: [Ice Cream Project](https://brzozanet.github.io/icecream/)

## 🛠 Użyte technologie

- **HTML5**
- **SASS (SCSS)**
- **JavaScript (ES Modules)**
- **Parcel 2**
- **PostHTML Include**
- **Swiper.js**
- **GitHub Pages**

## 📂 Struktura projektu

```text
icecream/
├── src/
│   ├── index.html
│   ├── index.js
│   ├── js/
│   │   ├── mobile-menu.js
│   │   ├── modal-buynow.js
│   │   ├── modal-franschise.js
│   │   └── modal-location.js
│   ├── partials/
│   ├── sass/
│   │   ├── main.scss
│   │   ├── partials/
│   │   ├── modules/
│   │   └── utils/
│   ├── images/
│   └── icons/
├── package.json
└── README.md
```

## ✨ Najważniejsze funkcje

- Sekcje: hero, produkty, o nas, zalety, galeria, opinie, kontakt, stopka
- Menu mobilne
- Modale: `Buy now`, `Our Locations`, `Franchise`
- Responsywny layout dla mobile/tablet/desktop
- Komponent galerii i slider opinii (Swiper)

## 📱 Responsywność

- Mobile: `< 768px`
- Tablet: `768px - 1199px`
- Desktop: `>= 1200px`

## 🚀 Uruchomienie lokalne

### Wymagania

- Node.js (zalecana aktualna wersja LTS)
- npm

### Instalacja i start

1. Sklonuj repozytorium:

```bash
git clone https://github.com/brzozanet/icecream.git
```

2. Przejdź do katalogu projektu:

```bash
cd icecream
```

3. Zainstaluj zależności:

```bash
npm install
```

4. Uruchom tryb developerski:

```bash
npm run dev
```

Aplikacja będzie dostępna pod adresem: `http://localhost:1234`.

## 🏗 Build produkcyjny

```bash
npm run build
```

Build jest przygotowany pod publikację na GitHub Pages z `public-url` ustawionym na `/icecream/`.

## 📝 Licencja

Projekt jest objęty licencją ISC.
