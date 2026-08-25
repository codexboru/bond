## 📜 [Lizenz](LICENSE)
Dieses Projekt steht unter der MIT-Lizenz. 

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-v1.1.0-blue.svg)](https://github.com/codexboru/bond/releases)
[![View Demo](https://img.shields.io/badge/View-Demo-blue.svg)](https://codexboru.github.io/bond/index.html)
[![Made with ❤️ by Codexboru](https://img.shields.io/badge/Made%20with-❤️%20by%20Codexboru-red.svg)](https://github.com/codexboru)
[![Download Release](https://img.shields.io/github/downloads/codexboru/bond/latest/total?color=orange)](https://github.com/codexboru/bond/releases/latest)

[![Total Downloads](https://img.shields.io/github/downloads/codexboru/bond/total?color=purple)](https://github.com/codexboru/bond/releases)

# 🎮 Bond – Codexboru Edition 

## 📌 Navigation
- 😶‍🌫️: [Codexboru](https://github.com/codexboru/)  
- 🕳: [Bond_calculator](https://codexboru.github.io/bond/index.html)  
- 🕹️: [README.md](https://codexboru.github.io/bond/README.html)
- 📊: [stats](https://codexboru.github.io/bond/stats.html)
- 🐈: [M2/M3](https://codexboru.github.io/bond/money.html)
---

## 🕹️ Einleitung

Wenn die **Leitzinsen erhöht** werden, fällt der Kurs der Staatsanleihe von **100 %** nach unten.  
Trotzdem wird am Ende der Laufzeit der **Nominalwert von 100 %** ausgezahlt – unabhängig vom Kauf‑ oder Verkaufskurs.  

### Beispiel:  
**Ticker: TRB100227**  
- **TRB** = Europäische Türkische Staatsanleihe  
- **100227** = Ablaufdatum 10.02.27  
- Auszahlung: **100 % Nominalwert**, egal wie der Kurs zwischendurch schwankt.  

---

## 📉 Zins ↑ → Kurs ↓
- Alte Anleihen verlieren an Attraktivität.  
- Kapital fließt in neue Anleihen mit höherem Kupon.  
- Risiko‑Assets (Aktien etc.) fallen.  

## 📈 Zins ↓ → Kurs ↑
- Alte Anleihen mit hohem Kupon steigen im Wert.  
- Verkaufspreise steigen.  
- Risiko‑Assets (Aktien etc.) steigen ebenfalls.  

---

## 🕳 [bond_calculator](https://codexboru.github.io/bond/index.html)
- Türkische Staatsanleihe Kaufkurs und Nominal Verkaufskurs kalkulator.
- Mit Gewinn bei Nominalwert 100 nach Ablauf Datum Rechner, sowie Investierte Summe mit Kauf Datum.
- Mit dem dazugehörigen Ticker der Anleihe.

---

## 📊 [Leitzins mit dem Kaufkurs der Staatsanleihen](https://codexboru.github.io/bond/stats.html)
- Datenbank von Leitzins und Anleihe Kaufkurse.

---

## 🐈 [M2 / M3 Geldmenge](https://codexboru.github.io/bond/money.html)

M2/M3 ↑ → Zins ↑ → Bond ↓
- Wenn die zirkulierende Geldmenge in den Ländern steigt, dann wird die Zentralbank die Zinsen anheben um die Umlaufgeschwindigkeit zu reduzieren.
-📉 Dabei gibts dann bei Staatsanleihen fallende Kurse.
- Wenn die Zirkulierende Geldmenge in den Ländern sinkt, dann wird die Zentralbank die Zinsen senken.
  
M2/M3 ↓ → Zins ↓ → Bond ↑
- 📈 Dabei gibts dann bei Staatsanleihen steigende Kurse für Ankauf / Verkauf.
  Bond, Aktien High risk Assets.
  
---

## 📂 Data Download / Upload

Die Anwendung unterstützt den Export und Import von JSON‑Dateien als Datenbank‑Referenzpunkte:

- **money.json**  
  [➡ Direktlink zur Datei](https://github.com/codexboru/bond/blob/main/data/money.json)  
  Enthält die M2/M3‑Aggregatwerte, Status und Zinserwartungen.  
  → Download: erzeugt eine JSON‑Datei aus den aktuellen Tabellenwerten.  
  → Upload: lädt eine bestehende `money.json` und injiziert die Daten in die Tabelle.

- **stats.json**  
  [➡ Direktlink zur Datei](https://github.com/codexboru/bond/blob/main/data/stats.json)  
  Enthält Leitzinsen und Bond‑Kurse der wichtigsten Länder.  
  → Download: exportiert die Tabelle als `stats.json`.  
  → Upload: liest eine bestehende Datei ein und ergänzt die Tabelle ohne Duplikate.

### 🔑 Referenzpunkte
- **Download** = Sicherung der aktuellen Datenbankstände  
- **Upload** = Wiederherstellung oder Austausch von Datenquellen  
- **Duplikationsprüfung** = verhindert doppelte Einträge beim erneuten Laden
