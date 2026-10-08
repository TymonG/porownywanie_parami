# Porównywanie Parami (porownywanie_parami)

## O programie

Aplikacja mobilna stworzona w technologii **React Native** oraz **Expo**. Służy do wartościowania, szeregowania i podejmowania decyzji na podstawie metody porównywania opcji parami (koncepcja AHP / Analityczny Proces Hierarchiczny).

## Główne funkcje

* **Ocena parami:** Porównywanie opcji dwie po dwóch, co pozwala przekształcić subiektywne preferencje w uporządkowany ranking.
* **Wieloplatformowość:** Wsparcie dla systemów Android, iOS oraz przeglądarek WWW dzięki frameworkowi Expo.
* **Gotowość do budowania:** Skonfigurowana obsługa buildów za pomocą Expo Application Services (`eas.json`).

## Struktura projektu

```text
porownywanie_parami/
├── App.js              # Główny punkt wejścia i interfejs aplikacji[cite: 7]
├── app.json            # Konfiguracja projektu Expo[cite: 7]
├── eas.json            # Konfiguracja budowania EAS[cite: 7]
├── index.js            # Rejestracja startowa aplikacji[cite: 7]
├── components/         # Komponenty UI[cite: 7]
└── assets/             # Ikony, ekrany ładowania i zasoby graficzne[cite: 7]
