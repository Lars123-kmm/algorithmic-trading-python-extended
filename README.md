# Algorithmic Trading with Python – Extended

Dieses Repository dient der systematischen Umsetzung und Erweiterung der Inhalte aus  
„Python for Finance and Algorithmic Trading (2nd edition)“ von Lucas Inglese.  
Im Mittelpunkt steht die Entwicklung, Analyse und das Testen algorithmischer Handelsstrategien mit Python.

Die Arbeit erfolgt primär in einem Jupyter Notebook und kann schrittweise zu einem modularen Trading-Framework ausgebaut werden.

---

## Zielsetzung

- Reproduktion und Erweiterung zentraler Konzepte aus dem Buch
- Aufbau eines sauberen, nachvollziehbaren Research-Workflows in Python
- Entwicklung, Parametrisierung und Bewertung verschiedener Handelsstrategien
- Vorbereitung von Strategien für Backtesting und potenziell späteres Live-Trading (z. B. mit MetaTrader 5)
- Strukturierte Dokumentation der einzelnen Experimente und Ergebnisse

---

## Inhalt

Aktuell umfasst das Repository vor allem:

- `Algorithmic Trading with Python – Extended.ipynb`  
  Zentrales Notebook mit:
  - Datenbeschaffung und -aufbereitung
  - Explorative Datenanalyse (EDA) von Finanzzeitreihen
  - Implementierung und Test einfacher Handelsregeln
  - Berechnung ausgewählter Risiko- und Performancekennzahlen
  - Grundlage für weitere Strategiemodule und Backtests

Optional bzw. perspektivisch vorgesehen:

- `data/` – lokale Markt- und Testdaten (CSV, Parquet o. Ä.)
- `strategies/` – Python-Module mit einzelnen Strategien oder Modellen
- `backtesting/` – Komponenten für wiederverwendbare Backtests
- `utils/` – allgemeine Hilfsfunktionen (Datenimport, Plots, Kennzahlen)

---

## Voraussetzungen

Benötigt wird eine funktionierende Python-Umgebung (empfohlen: Python ≥ 3.10).

Typisch verwendete Pakete (Basis):

```bash
pip install numpy pandas matplotlib yfinance scipy
