# 🎮 Bond Calculator – Codexboru Edition (8‑Bit Style)

## 📌 Navigation
- 😶‍🌫️: [Codexboru](www.Github.com/codexboru)  
- 🕳: [Bond_calculator](codexboru.github.io/bond/index.html)  

Beide Buttons sind im **Retro‑8‑Bit‑Pixel‑Style** gestaltet und fest oben positioniert.

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

## 🎨 8‑Bit Style CSS

```css
/* 8-Bit Retro Arcade Style */
body {
  font-family: 'Press Start 2P', monospace;
  background-color: #111;
  color: #0f0;
  margin: 0;
  padding: 0;
}

button {
  font-family: 'Press Start 2P', monospace;
  background-color: #222;
  color: #0f0;
  border: 3px solid #0f0;
  padding: 10px 20px;
  cursor: pointer;
  box-shadow: 4px 4px #0f0;
}

button:hover {
  background-color: #0f0;
  color: #111;
}

.nav-left, .nav-right {
  position: fixed;
  top: 10px;
}

.nav-left {
  left: 10px;
}

.nav-right {
  right: 10px;
}
