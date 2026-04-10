# 🧾 Time2Split

Smart bill splitting app for iOS.

## 🌐 Documentation Website

Live site: [https://rodriqe.github.io/Splitbill/](https://rodriqe.github.io/Splitbill/)

| File | Description | URL |
|------|-------------|-----|
| `index.html` | Landing page | [https://rodriqe.github.io/Splitbill/](https://rodriqe.github.io/Splitbill/) |
| `privacy.html` | Privacy Policy (App Store) | [https://rodriqe.github.io/Splitbill/privacy.html](https://rodriqe.github.io/Splitbill/privacy.html) |
| `terms.html` | Terms of Use / EULA (App Store) | [https://rodriqe.github.io/Splitbill/terms.html](https://rodriqe.github.io/Splitbill/terms.html) |
| `support.html` | Support (App Store Connect) | [https://rodriqe.github.io/Splitbill/support.html](https://rodriqe.github.io/Splitbill/support.html) |

## ✨ Features

- **OCR Receipt Scanning** — Automatically extract items and prices from receipt photos using Apple Vision
- **30 Currencies** — Multi-currency support with locale-aware formatting
- **Smart Item Assignment** — Assign items to individual participants or split evenly
- **Proportional Tips** — Adjustable tip percentage distributed proportionally
- **Debt Settlement** — Greedy algorithm calculates minimum transactions to settle all debts
- **Participant Groups** — Save and reuse frequent groups
- **Bilingual** — Full English and Spanish localization
- **Privacy First** — All data stored locally, no tracking, no ads, no servers

## 🏗️ Architecture

```
Splitbill/
├── Models/          # SwiftData models (Bill, BillItem, Participant, etc.)
├── Services/        # Business logic (BillSplitService, CurrencyService, OCRService)
├── Views/           # SwiftUI views (Home, BillDetail, Summary, Settings, etc.)
├── Persistence/     # ModelContainer setup
├── en.lproj/        # English localization
├── es.lproj/        # Spanish localization
└── Assets.xcassets/ # App icons and colors
docs/                # GitHub Pages documentation site
```

## 🔒 Privacy

All data is stored locally on-device using SwiftData. No analytics, no tracking, no third-party services. OCR processing uses Apple's Vision framework entirely on-device. See the full [Privacy Policy](https://rodriqe.github.io/Splitbill/privacy.html).

## 🚀 GitHub Pages

This site is published automatically via GitHub Pages from the `/docs` directory on the `main` branch.

### Setup

1. Repository → Settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `main` → `/docs`

## 📋 Checklist GitHub Pages

- [x] Directorio `/docs` creado
- [x] `index.html` creado
- [x] `privacy.html` creado
- [x] `terms.html` creado
- [x] `support.html` creado
- [ ] GitHub Pages habilitado (Settings → Pages)
- [ ] Sitio verificado: [https://rodriqe.github.io/Splitbill/](https://rodriqe.github.io/Splitbill/)
- [ ] Privacy Policy URL añadida a App Store Connect
- [ ] Terms of Use (EULA) URL añadida a App Store Connect
- [ ] Support URL añadida a App Store Connect

## 🔗 Enlaces Importantes

- **Privacy Policy**: [https://rodriqe.github.io/Splitbill/privacy.html](https://rodriqe.github.io/Splitbill/privacy.html)
- **Terms of Use**: [https://rodriqe.github.io/Splitbill/terms.html](https://rodriqe.github.io/Splitbill/terms.html)
- **Support**: [https://rodriqe.github.io/Splitbill/support.html](https://rodriqe.github.io/Splitbill/support.html)
- **GitHub Repo**: https://github.com/Rodriqe/Splitbill

> **Nota:** Este sitio es estático (solo HTML/CSS). No requiere servidor ni base de datos.