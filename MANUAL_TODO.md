# MANUAL_TODO — Offene Punkte (nicht automatisiert lösbar)

Stand: 11. April 2026

---

## 🔴 Kritisch — Sofort

### 1. Google Search Console einrichten
- Unter [search.google.com/search-console](https://search.google.com/search-console) anmelden
- Domain `arns-immobilien.de` verifizieren (DNS-TXT-Record oder HTML-Datei)
- Sitemap einreichen: `https://arns-immobilien.de/sitemap.xml`
- Haupt-URL manuell zur Indexierung anfordern
- **Warum:** Die Seite ist aktuell nicht bei Google indexiert (0 Treffer bei `site:arns-immobilien.de`)

### 2. Google Business Profile anlegen
- Unter [business.google.com](https://business.google.com) Profil erstellen
- Adresse: Eisenstr. 37, 50825 Köln
- Kategorie: "Immobilienunternehmen" oder "Immobilieninvestor"
- Verifizierung per Postkarte (5–14 Tage)
- Beschreibung, Fotos, Öffnungszeiten, Website-URL ergänzen
- **Warum:** Ohne Profil keine Sichtbarkeit in Google Maps / Local Pack

---

## 🟡 Mittel — Diesen Monat

### 3. Google-Bewertungen einholen
- Bisherige Geschäftspartner (Makler, Verkäufer, Notare) um Bewertung bitten
- Ziel: mindestens 3–5 Bewertungen im Google Business Profile
- **Warum:** Bewertungen sind der stärkste lokale Ranking-Faktor

### 4. WCAG-Kontraste prüfen
- Mit [WAVE Tool](https://wave.webaim.org/) oder axe DevTools die Seite prüfen
- Mindestens 4,5:1 Kontrastverhältnis für normalen Text
- Mindestens 3:1 für großen Text (>18px)
- Ggf. Farbwerte in CSS-Variablen anpassen

### 5. Social-Media-Profile anlegen / verknüpfen
- LinkedIn-Profil für Michael Arns erstellen oder aktualisieren
- Optional: XING, Instagram (Objekt-Fotos)
- Profile auf der Website verlinken
- **Warum:** Stärkt E-E-A-T-Signale (Expertise, Authoritativeness, Trustworthiness)

### 6. Keyword-spezifische Landingpages (mittelfristig)
- `/koeln` — "Mehrfamilienhaus verkaufen Köln"
- `/wuppertal` — "Mehrfamilienhaus verkaufen Wuppertal"
- `/ablauf` — Ankaufsprozess im Detail
- **Warum:** Gezielte Keyword-Abdeckung und interne Verlinkung

---

## 🟢 Nice-to-have — Q3 2026+

### 7. Blog / Content-Marketing evaluieren
- Themen: "Mehrfamilienhaus verkaufen: Was Eigentümer wissen müssen"
- "Immobilienmarkt Köln 2026: Aktuelle Entwicklungen"
- Stärkt organische Sichtbarkeit langfristig

### 8. CMS / Static Site Generator evaluieren
- Bei wachsendem Content (Blog, Objekt-Listings) Hugo, Astro oder 11ty prüfen
- Aktuell: Statische HTML-Dateien sind performant, aber schwer skalierbar

### 9. WhatsApp-Button als Zweit-CTA
- Neben "Objekt anbieten" einen WhatsApp-Link anbieten
- Senkt die Hemmschwelle für spontane Kontaktaufnahmen
