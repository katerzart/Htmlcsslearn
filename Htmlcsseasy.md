# 🌍 HTML & CSS – Der einfachste Guide für Anfänger

HTML baut das Gerüst einer Webseite, CSS macht sie schön!

Stell dir eine Webseite vor wie ein Haus:
- 🏠 **HTML** = Mauern und Fenster (Struktur)
- 🎨 **CSS** = Farben und Möbel (Design)

Jetzt lernst du, wie du deine eigene Webseite baust! 🚀

---

## 📌 1. Was ist HTML? (Die Bausteine einer Webseite)

HTML (HyperText Markup Language) ist eine Sprache, mit der du Webseiten erstellst. Jede HTML-Seite besteht aus verschiedenen Bausteinen, die mit sogenannten **Tags** geschrieben werden.

---

## 🏗 2. Die Grundstruktur einer HTML-Seite

Jede Webseite beginnt mit dieser Basis-Struktur:

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Meine erste Webseite</title>
</head>
<body>
    <h1>Willkommen auf meiner Webseite!</h1>
    <p>Das ist mein erster Absatz.</p>
</body>
</html>
```

### Erklärung:
- `<!DOCTYPE html>` → Sagt dem Browser: “Das ist eine HTML-Seite!”
- `<html lang="de">` → Start des HTML-Codes (Sprache: Deutsch)
- `<head>` → Unsichtbare Infos (z. B. Titel der Seite)
- `<title>` → Titel der Webseite (erscheint im Browser-Tab)
- `<body>` → Hier kommt alles rein, was der Besucher sieht!

---

## 🏷 3. Die wichtigsten HTML-Tags (Bausteine einer Webseite)

| Tag            | Bedeutung                | Beispiel                          |
|----------------|--------------------------|-----------------------------------|
| `<h1>` - `<h6>`| Überschriften            | `<h1>Große Überschrift</h1>`      |
| `<p>`          | Absatz (Text)            | `<p>Hallo Welt!</p>`              |
| `<a href="URL">`| Link                    | `<a href="https://google.com">Google</a>` |
| `<img src="bild.jpg">` | Bild einfügen     | `<img src="katze.jpg">`           |
| `<ul>` / `<ol>`| Listen                   | `<ul><li>Apfel</li><li>Banane</li></ul>` |
| `<button>`     | Knopf                    | `<button>Klick mich</button>`     |

---

## 🎨 4. Was ist CSS? (Das Design deiner Webseite)

CSS (Cascading Style Sheets) gibt deiner Webseite Farben, Schriftarten und Layouts.

Ein einfacher CSS-Code sieht so aus:

```css
body {
    background-color: lightblue;
}
h1 {
    color: red;
    font-size: 30px;
}
```

### Erklärung:
- `background-color` → Hintergrundfarbe
- `color` → Textfarbe
- `font-size` → Schriftgröße

---

## 🎨 5. Wie fügt man CSS hinzu? (3 Methoden)

### 1️⃣ Direkt im HTML-Tag (nicht empfohlen!)
```html
<p style="color: blue;">Blauer Text</p>
```

### 2️⃣ Im `<style>`-Tag (für kleine Designs okay)
```html
<head>
    <style>
        p { color: blue; }
    </style>
</head>
```

### 3️⃣ In einer extra Datei (beste Methode!)
**HTML (index.html)**
```html
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

**CSS (style.css)**
```css
p {
    color: blue;
}
```

✅ **Vorteil:** Dein CSS ist sauber getrennt vom HTML!

---

## 🎯 6. Die wichtigsten CSS-Befehle

| CSS-Befehl       | Bedeutung                | Beispiel                          |
|------------------|--------------------------|-----------------------------------|
| `color`          | Textfarbe                | `color: red;`                     |
| `background-color` | Hintergrundfarbe        | `background-color: yellow;`       |
| `font-size`      | Schriftgröße             | `font-size: 20px;`                |
| `text-align`     | Text ausrichten          | `text-align: center;`             |
| `border`         | Rand um ein Element      | `border: 2px solid black;`        |
| `margin`         | Abstand nach außen       | `margin: 10px;`                   |
| `padding`        | Abstand nach innen       | `padding: 10px;`                  |

💡 **Tipp:** `margin` sorgt für Abstand außen, `padding` für Abstand innen!

---

## 🎉 7. HTML & CSS in Aktion – Dein erstes Mini-Projekt!

Jetzt kombinieren wir HTML & CSS und erstellen eine kleine Webseite!

**HTML (index.html)**
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Meine Webseite</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Hallo Welt!</h1>
    <p>Ich lerne gerade HTML & CSS. 🚀</p>
    <button>Klick mich!</button>
</body>
</html>
```

**CSS (style.css)**
```css
body {
    background-color: lightgray;
    font-family: Arial, sans-serif;
}

h1 {
    color: blue;
    text-align: center;
}

p {
    color: green;
    font-size: 18px;
}

button {
    background-color: orange;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}
```

### 🔹 Was passiert hier?
- ✅ Der Hintergrund wird grau
- ✅ Die Überschrift ist blau & mittig
- ✅ Der Text ist grün und größer
- ✅ Der Button ist orange und anklickbar

🚀 **Speichere die Dateien & öffne `index.html` in deinem Browser – Fertig ist deine erste Webseite!**

---

## 📚 8. Extra-Tipps für Anfänger

- ✅ **HTML ist für den Inhalt, CSS für das Design**
- ✅ **Schreibe sauberen Code!** → Nutze Einrückungen & Leerzeilen
- ✅ **Teste deine Webseite** → Öffne deine `.html` Datei einfach im Browser
- ✅ **Nutze Online-Editoren** wie [CodePen.io](https://codepen.io/)

---

## 📝 9. Mini-Test – Kannst du diese Fragen beantworten?

1️⃣ Welches HTML-Tag macht eine Überschrift?  
2️⃣ Wie färbst du den Hintergrund einer Seite blau?  
3️⃣ Welches HTML-Tag benutzt man für einen Knopf?  
4️⃣ Wie bindet man eine externe CSS-Datei ein?  

**Tipp:** Schreib die Antworten als HTML & CSS Code auf!

---

🎉 **Glückwunsch! Du bist bereit für den Test!**

Mit diesem Guide hast du alles gelernt, um HTML & CSS zu verstehen! Viel Erfolg! 🍀🚀
