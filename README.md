# Lucjan Sobieszczański - Interaktywna Strona ⚡🐾

Zabawna, interaktywna strona internetowa z biegającym i podskakującym Pikachu/Pichu podążającym za kursorem myszki lub dotykiem na ekranie.

---

## 🌟 Funkcje

- **Interaktywny towarzysz (Pichu / Pikachu):**
  - Podąża za kursorem myszy lub dotykiem (obsługa ekranów dotykowych).
  - Płynna fizyka ruchu (efekt sprężyny z animacją kołysania / waddle).
  - Obracanie się w kierunku ruchu oraz pochylanie przy przyspieszaniu.
- **Efekty dźwiękowe:**
  - 8-bitowe urocze dźwięki wygenerowane dynamicznie za pomocą **Web Audio API** (brak zewnętrznych plików audio).
- **Akcje i animacje:**
  - **Kliknięcie / dotknięcie:** radosny podskok z saltkiem 360°, dymki z kwestiami ("Pika-pika!", "Wheee!") oraz iskierki (`⚡`, `✨`, `⭐`).
  - **Sprint:** kłęby kurzu przy szybkim biegu oraz kropelki potu (`💦`) przy gwałtownych ruchach.
  - **Tryb uśpienia:** po 3.5 sekundach bezruchu postać zasypia ("Zzz... 💤") i budzi się z wykrzyknikiem, gdy kursor znów się poruszy.
- **Zero zewnętrznych zależności:** czysty HTML, CSS i nowoczesny Vanilla JS.

---

## 📂 Struktura projektu

```text
lucek-strona/
├── Lucjan.html    # Główna strona ze stylami i logiką animacji
├── Pichu.webp     # Grafika postaci
└── README.md      # Dokumentacja projektu
```

---

## 🚀 Jak uruchomić

Projekt nie wymaga instalacji żadnych pakietów ani serwerów:

1. Pobierz lub sklonuj repozytorium:
   ```bash
   git clone git@github.com:sobi3ch/lucek-strona.git
   cd lucek-strona
   ```
2. Otwórz plik `Lucjan.html` w dowolnej nowoczesnej przeglądarce internetowej:
   - Kliknij dwukrotnie na `Lucjan.html`, lub
   - W terminalu:
     ```bash
     xdg-open Lucjan.html   # Linux
     open Lucjan.html       # macOS
     start Lucjan.html      # Windows
     ```

---

## 🛠️ Technologie

- **HTML5 & CSS3** (Flexbox, CSS Animations, Clamp, Dynamic Viewport)
- **Vanilla JavaScript** (Spring physics, RequestAnimationFrame, Touch & Pointer Events)
- **Web Audio API** (generowanie dźwięków syntezatorem oscylatorowym)
