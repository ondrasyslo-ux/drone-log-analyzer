# Plán projektu a milníky

Tento dokument slouží ke sledování postupu vývoje semestrálního projektu (Analyzátor telemetrie dronů). Cílem je vyvinout a otestovat plně funkční nástroj v Pythonu do **29. 1. 2027**.

## Fáze 1: Příprava (Začátek října 2026)
- [x] Výběr tématu projektu
- [x] Založení veřejného repozitáře na GitHubu
- [x] Vytvoření základní dokumentace (README.md, návrh milníků)

## Fáze 2: Sběr dat (Do konce října 2026)
- [ ] Zajištění open-source letových logů (CSV) ze systémů PX4/ArduPilot
- [ ] Zmapování struktury dat a výběr relevantních sloupců pro analýzu

## Fáze 3: Datový model (Do poloviny listopadu 2026)
- [ ] Vývoj základního skriptu v Pythonu
- [ ] Implementace načítání a čištění dat pomocí knihovny `pandas`
- [ ] Parsování dat z logů do bezpečné datové struktury

## Fáze 4: Detekční algoritmy (Do poloviny prosince 2026)
- [ ] Implementace matematické logiky pro výpočet vzdáleností a rychlostí
- [ ] Vytvoření logiky pro detekci GPS Spoofingu (fyzikálně nereálné skoky v lokaci)
- [ ] Vytvoření logiky pro detekci Jammingu (náhlé výpadky signálu satelitů)

## Fáze 5: Testování (Do poloviny ledna 2027)
- [ ] Testování nástroje na různých sadách logů (normální let vs. anomálie)
- [ ] Odstranění nalezených chyb (bugfixing)
- [ ] Celková optimalizace kódu a příprava na odevzdání

## Fáze 6: Finalizace (Do 29. 1. 2027)
- [ ] Kompletace uživatelské dokumentace (jak nástroj spustit)
- [ ] Kompletace technické dokumentace (jak kód funguje)
- [ ] Závěrečné úpravy kódu a oficiální odevzdání projektu
