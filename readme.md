# KI-Kompetenzen – Workshop & Mitmachplattform

Dies ist das offizielle Repository zum offenen Workshop-Format **„KI-Kompetenzen in der religionsbezogenen Bildung“**.
Der Workshop findet als Testlauf am [27.05.2025 um 17 Uhr im relilab statt (einfach kostenfrei teilnehmen) Infos hier](https://relilab.org/ki-kompetenzen-in-der-religionsbezogenen-bildung/) und [am 2. Juni 2025 um 16:00 Uhr hier auf der RPT25 in Luzern 🇨🇭](https://rpt25.ch/ki-als-werkzeug-vom-anwenden-zum-gestalten/)
Die Plattform dient zur gemeinschaftlichen Erarbeitung, Einreichung und Diskussion von Lernaufgaben, Reflexionsimpulsen und praktischen Beispielen rund um den Einsatz von KI in Bildungsprozessen – insbesondere im Kontext von Schule, Hochschule und kirchlicher Bildungsarbeit.

---

## 🔗 Live-Version (GitHub Pages)

Formular zur Einreichung von Lernaufgaben:
➡️ [https://edufeed-org.github.io/ki-kompetenzen/index.html](https://edufeed-org.github.io/ki-kompetenzen/index.html)

---

## ✍️ Mitmachen

* Du kannst direkt über das [Formular](https://edufeed-org.github.io/ki-kompetenzen/index.html) neue Aufgabenformate einreichen.
* Beiträge werden automatisch per Webhook an eine zentrale Nostr-Datenbank übermittelt.
* Die Inhalte lassen sich über Hashtags (z. B. `#relilab`, `#reflektieren`, `#konstruktion`) kategorisieren.

---

## 📁 Struktur

```bash
/docs
├── index.html         # Eingabeformular (Markdown-Vorschau, Tags, JSON-POST)
├── CHANGELOG.md       # Versionsübersicht
├── beispiele/         # Optional: Beispielaufgaben & JSON-Dateien
└── assets/            # Icons, Grafiken, Styles (optional)
```

---

## 🛠 Technologien

* **GitHub Pages** zur Bereitstellung
* **n8n** für Workflow-Automatisierung (Webhook-Verarbeitung)
* **Nostr** als Netzwerk für die kollaborative Sammlung und Archivierung
* **Markdown**-basiertes Input-System mit Vorschaufunktion (via [marked.js](https://marked.js.org))

---

## 📌 Zielgruppe

* Religionslehrkräfte
* Hochschuldidaktiker\:innen
* Fortbildner\:innen & Community-Coaches
* Studierende in Lehramtsstudiengängen

---

## 🧭 Kontakt & Community

Mehr zum Projekt:

* 🔗 [https://relilab.org/](https://relilab.org/)
* 💬 Mitdiskutieren auf Nostr via `#relilab`
* 🧪 Im Austausch bleiben zu KI und religionsbezogenener Bildung in Element/Matrix 

---

## 🧾 Lizenz

Dieses Projekt steht unter einer [Creative Commons BY 4.0 Lizenz](https://creativecommons.org/licenses/by/4.0/).
