---
name: Bug template
about: Bug report
title: ''
labels: ''
assignees: ''
type: Bug

---

## Opis błędu
Obraz stereoskopowy dla gracza 2 traci synchronizację z pozycją głowy
po upływie ~2 minut od uruchomienia sesji.

## Kroki do reprodukcji
1. Uruchom sesję z dwoma graczami
2. Odczekaj ~2 minuty
3. Gracz 2 porusza głową – obraz nie nadąża za ruchem

## Oczekiwane zachowanie
Obraz aktualizuje się płynnie przez cały czas trwania sesji.

## Aktualne zachowanie
Po ~2 minutach head tracking gracza 2 przestaje działać poprawnie.
