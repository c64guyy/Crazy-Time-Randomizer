# Crazy Time Randomizer

Tool web per generare numeri casuali "Crazy Time" style. Sviluppato da c64guyy (Marco Vinci).


## Caratteristiche
- Genera sequenze casuali ispirate a Crazy Time (ruota, moltiplicatori).
- Interfaccia responsive HTML/CSS/JS.
- Personalizzabile (range, velocità animazione).
- No dipendenze esterne, puro vanilla JS.

## Tecnologie
- Frontend: HTML5, CSS3, JavaScript (ES6+)
- Editor: VS Code su Ubuntu [memory:6]
- Browser: Chrome/Firefox/Edge

## Installazione e Uso
1. Clona la repo:  
git clone https://github.com/c64guyy/Crazy-Time-Randomizer.git
cd Crazy-Time-Randomizer

2. Apri `index.html` nel browser:  
- Doppio click o `live-server` (VS Code extension).
3. Clicca "Randomize" per generare!

Demo online: [https://c64guyy.github.io/Crazy-Time-Randomizer](https://c64guyy.github.io/Crazy-Time-Randomizer/) *(deploya su GitHub Pages!)*

## File Principali
- `index.html`: Interfaccia principale.
- `style.css`: Stili animati.
- `script.js`: Logica random (Math.random(), animazioni).

## Personalizzazione
Modifica in `script.js`:  
```js
const min = 1, max = 100;  // Cambia range
const result = Math.floor(Math.random() * (max - min + 1)) + min;
