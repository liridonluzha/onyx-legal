# Onyx IPTV — Datenschutz und Nutzungsbedingungen

Statische Seiten für die beiden Pflichtfelder in App Store Connect
(*Privacy Policy URL* und *Support URL*). Kein Build, keine Abhängigkeiten.

| Datei | Inhalt |
|---|---|
| `index.html` | Privacy Policy (English) — Startseite |
| `terms.html` | Terms of Use (English) |
| `privacy.de.html` | Datenschutz (Deutsch) |
| `terms.de.html` | Nutzungsbedingungen (Deutsch) |

Der Text ist identisch mit dem, der in der App angezeigt wird. Beide stammen
aus `PremiumIPTV/OnyxLegalText.swift` — **dort ändern, dann diese Seiten neu
erzeugen**, sonst laufen App und Veröffentlichung auseinander. Ein Test in der
App (`testPublishedPagesCarryTheSameWordingAsTheApp`) schlägt fehl, wenn das
passiert.

## Veröffentlichen

Settings → Pages → Source: *Deploy from a branch*, Branch `main`, Ordner
`/ (root)`. Nach etwa einer Minute sind die Seiten erreichbar.
