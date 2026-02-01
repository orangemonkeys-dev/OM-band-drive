# OM Band Drive – Projektübersicht
Dieses Repository dient als zentraler Speicherort für alle Inhalte der Band **Orange Monkeys**.
Es enthält Leadsheets, Design‑Elemente, Songlisten sowie die operative Website.
Zusätzlich existiert ein Entwicklungsbereich, in dem neue Ideen, Layouts und Funktionen getestet werden können.

--- 

# Orange Monkeys – Projektstruktur

Dieses Repository enthält die zentrale Ordnerstruktur der Band **Orange Monkeys**.

## 📁 Verzeichnisbaum

# Orange Monkeys – Projektstruktur

| Pfad                | Beschreibung |
|---------------------|--------------|
| `/Leadsheets/`      | Offizielle Leadsheets, PDFs, Arrangements |
| `/MonkeysDesign/`   | Logos, Grafiken, visuelle Assets |
| `/Songlist.json`    | Operative Songliste (Produktivversion) |
| `/index.html`       | Operative Website (Produktivversion) |
| `/dev/`             | Entwicklungs- & Testbereich |
| `/dev/Songlist.json`| Testversion der Songliste |
| `/dev/index.html`   | Testversion der Website |
| `/dev/experiments/` | Prototypen, Tests, neue Ideen |
| `/dev/design-drafts/` | Entwürfe, neue Designs, Varianten |
| `/README.md`        | Projektbeschreibung |


---

## 🔀 Branch‑Konzept

Das Repository nutzt zwei Haupt‑Branches:

### **main**
- Enthält die **operative**, stabile Version  
- Wird für Website‑Deployments und offizielle Dateien genutzt  
- Änderungen werden nur über Pull Requests eingespielt  

### **dev**
- Entwicklungszweig für neue Features, Layouts und Songlisten  
- Änderungen werden hier getestet, bevor sie in `main` übernommen werden  

---

## 🧠 Workflow

1. Änderungen oder neue Features werden im Branch `dev` entwickelt.  
2. Optional: Feature‑Branches wie `feature-new-songlist` oder `design-update`.  
3. Nach Fertigstellung → Pull Request von `dev` nach `main`.  
4. Nach dem Merge ist die operative Version aktualisiert.

---

## 🎸 Inhalte des Repositories

### **Leadsheets**
- Enthält Noten, PDFs und Arrangements für Proben und Auftritte.

### **MonkeysDesign**
- Logos, Grafiken, Layouts und visuelle Elemente der Band.

### **Songlist.json**
- Zentrale Songliste, die von Tools oder der Website genutzt wird.  
- In `main` → operative Version  
- In `dev` → Testversion für neue Songs oder Sortierungen

### **index.html**
- Operative Website der Band  
- Änderungen werden zuerst in `dev` getestet

---

## 🛠️ Entwicklungsbereich (`dev/`)

Der Ordner `dev/` dient als Sandbox für neue Ideen:

- **Songlist.json** – neue Songs, Sortierungen, Metadaten  
- **index.html** – neue Layouts, Funktionen, UI‑Tests  
- **experiments/** – Prototypen, Skripte, Tests  
- **design-drafts/** – neue Logos, Farbvarianten, Layout‑Entwürfe  

---

## 📄 Lizenz & Nutzung

Dieses Repository ist öffentlich sichtbar, aber die Inhalte sind Eigentum der Band **Orange Monkeys**.  
Bitte nur mit Zustimmung der Band verwenden oder weitergeben.

---

## 🤝 Mitwirken

Bandmitglieder können:

- neue Leadsheets hochladen  
- Songlisten aktualisieren  
- Design‑Elemente ergänzen  
- Website‑Änderungen vorschlagen  

Alle Änderungen sollten über Pull Requests erfolgen.

---

## 📬 Kontakt

Für Fragen oder Vorschläge:  
**orangemonkeys-dev** (GitHub Account)  
oder direkt an die Band.
