# Drone Telemetry Analyzer

Softwarový nástroj v Pythonu pro automatizované zpracování CSV letových logů ze systémů PX4 a ArduPilot. Slouží k identifikaci anomálií indikujících kybernetické útoky na drony.

## Hlavní funkce
* **Detekce GPS Spoofingu:** Identifikace fyzikálně nereálných skoků v lokaci a rychlosti.
* **Detekce Jammingu:** Sledování náhlých výpadků signálu satelitů.

## Použité technologie
* **Jazyk:** Python 3
* **Zpracování dat:** `pandas` pro načítání, čištění a parsování logů.
* **Výpočty:** `numpy` pro matematické operace a výpočet vzdáleností.

## Struktura projektu
*(Zde později doplníš, jak máš rozdělené složky, např. `data/`, `src/`, `tests/`)*
