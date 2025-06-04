# 🌐 Aufgabe 3: Arbeiten mit einer Wetter-API

Sie programmieren nun eine echte Schnittstelle ins Internet!

---

## 🛠️ Aufgabe

1. Beim Klick auf den Button `apiButton` soll eine Anfrage an die OpenWeatherMap API geschickt werden.
2. Die Temperatur und der Ort sollen im `apiOutput` angezeigt werden.
3. Fehler (z. B. kein Internet oder falscher API-Schlüssel) sollen in der Konsole angezeigt werden.

---

## 🧪 Beispiel

```javascript
const apiKey = 'HIER_IHR_SCHLÜSSEL';
const url = `https://api.openweathermap.org/data/2.5/weather?q=Zürich&appid=${apiKey}&units=metric`;

document.getElementById('apiButton').addEventListener('click', async function() {
    try {
        const response = await fetch(url);
        const data = await response.json();
        document.getElementById('apiOutput').innerHTML = 
            `<p>Temperatur in ${data.name}: ${data.main.temp}°C</p>`;
    } catch (error) {
        console.error('Fehler beim Abrufen der Wetterdaten:', error);
    }
});
```
