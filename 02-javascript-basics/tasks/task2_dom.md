# 🧩 Aufgabe 2: DOM-Manipulation

In dieser Aufgabe lernen Sie, wie Sie die Webseite mit JavaScript **verändern** können.

---

## 🛠️ Aufgabe

Wenn der Button mit der ID `domButton` geklickt wird, soll im `div` mit der ID `weatherData` der Text  
„Wetterdaten werden geladen…“ erscheinen.

---

## 🧪 Beispiel

```javascript
document.getElementById('domButton').addEventListener('click', function() {
    document.getElementById('weatherData').innerHTML = '<p>Wetterdaten werden geladen...</p>';
});
```

