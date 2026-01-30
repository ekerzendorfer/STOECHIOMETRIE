# Stöchiometrie-Meister 🧪

Ein interaktives Web-Tool für den Chemieunterricht (Sekundarstufe 1 und 2), entwickelt für das Seminar **"KI im Chemieunterricht"** (Österreich).

Dieses Tool demonstriert, wie KI-generierte Inhalte (NotebookLM & Gemini) nahtlos in eine funktionale Lehr-Lernumgebung integriert werden können.

## 🌟 Features

- **Interaktive Brücke:** Visualisierung des Rechenweges von der Masse ($m$) zur Stoffmenge ($n$) und zur Teilchenzahl ($N$).
- **Didaktische Differenzierung:** - **SEK 1:** Fokus auf Analogien ("Der Schluck Wasser") und intuitives Verständnis.
  - **SEK 2:** Fokus auf Laboranwendungen, Gasgesetze und Matura-Vorbereitung.
- **KI-Resilienz-Modul:** Integrierte "Fehlersuche" (Prinzip: *Max hat Mist gemacht*), um kritisches Denken zu fördern.
- **Scaffolding:** Ein schrittweiser Lösungsleitfaden nach dem *Cognitive Apprenticeship* Modell.
- **Matura-Challenge:** Expertenfragen zum realen Gasverhalten (van-der-Waals).

## 🚀 Installation (GitHub Pages)

1. Erstelle ein neues GitHub-Repository.
2. Lade die Datei `index.html` hoch.
3. Gehe zu **Settings > Pages**.
4. Wähle den `main` Branch und klicke auf **Save**.
5. Deine App ist nach wenigen Augenblicken unter `https://[dein-benutzername].github.io/[repo-name]` online.

## 🛠️ Erweiterung der Stoffliste

Die Stoffdatenbank befindet sich im `<script>`-Bereich der `index.html` unter der Konstante `chemicals`. Um neue Stoffe hinzuzufügen, kann einfach ein neuer Eintrag nach folgendem Muster ergänzt werden:

```javascript
"FORMEL": { 
    m: MOLMASSE, 
    name: "NAME", 
    s1: "ANALOGIE FÜR SEK 1", 
    s2: "ANWENDUNG FÜR SEK 2" 
}
