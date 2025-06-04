# 🎯 Aufgabe 1: Einstieg in JavaScript

Willkommen bei JavaScript! In dieser Aufgabe lernen Sie:

✅ Was JavaScript ist  
✅ Wie man JavaScript in eine HTML-Seite einbindet  
✅ Wie man mit einem Klick auf einen Button eine Aktion auslöst

---

## 🧠 Theorie

**Was ist JavaScript?**  
JavaScript ist eine Programmiersprache, mit der Webseiten interaktiv gemacht werden – z. B. durch Buttons, Animationen oder API-Aufrufe.

**Wie wird JavaScript eingebunden?**  
In Ihrer HTML-Datei finden Sie am Ende folgenden Code:

```html
<script src="script.js"></script>
```

Damit wird die Datei `script.js` eingebunden – Sie schreiben den Code also dort hinein.

---

## 🛠️ Ihre Aufgabe

Erstellen Sie in der Datei `script.js` folgenden Code:

1. Wählen Sie den Button mit der ID `introButton` aus.
2. Fügen Sie einen **Event Listener** hinzu, der beim Klick `"JavaScript funktioniert!"` in der Konsole anzeigt.

---

### 💡 Beispielcode

```javascript
document.getElementById('introButton').addEventListener('click', function() {
    console.log('JavaScript funktioniert!');
});
```

---

## 🧪 Kontrolle

- Öffnen Sie die Seite im Browser.
- Öffnen Sie die Entwicklertools (F12 oder Rechtsklick → "Untersuchen" → Tab „Konsole“).
- Klicken Sie auf den Button mit der Aufschrift „Klick mich!“.
- Wenn in der Konsole **„JavaScript funktioniert!“** erscheint, haben Sie alles richtig gemacht. ✅
