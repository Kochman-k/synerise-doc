# Synerise Document System

## Struktura
```
├── style.css          ← Główny arkusz stylów (edytuj tutaj)
├── template.html      ← Szablon dla nowych dokumentów
├── synerise_doc.html  ← Platform Reference Document
├── images/            ← Obrazki współdzielone
│   ├── beh-hub.png
│   ├── ai-hub.png
│   └── ...
├── Graphik-*.otf      ← Fonty (lokalne)
```

## Tworzenie nowego dokumentu
1. Skopiuj `template.html` i zmień nazwę
2. Zmień tytuł i treść
3. Plik automatycznie używa `style.css`

## Rozwijanie stylów
Edytuj `style.css` — zmiany trafiają do wszystkich dokumentów.

### Klasy dostępne w szablonie
- `h1.section` — nagłówek sekcji (28pt)
- `h2` — podtytuł (16pt)
- `h3` — nagłówek trzeciego poziomu (11pt)
- `table.light` — tabela z dotted separatorami
- `table.banded` — tabela z naprzemiennymi wierszami
- `table.default` — tabela z pełnymi liniami
- `table.signatures` — tabela podpisów
- `.metrics` — siatka metryk liczbowych
- `.hub-grid` — siatka kart hubów
- `.badge` — etykieta "Proprietary"
- `blockquote` — cytat z paskiem
- `.quote-intense` — cytat na ciemnym tle
- `.info-box` — box informacyjny
- `.cover-title`, `.cover-subtitle` — elementy okładki
- `.running-header` — nagłówek strony
- `.doc-page` — kontener strony
- `.hub-section-header` — nagłówek huba z obrazkiem
- `.hub-ui-screenshot` — screenshot UI

## GitHub Pages
Strona dostępna pod:
https://kochman-k.github.io/synerise-doc/synerise_doc.html

## Deploy
```bash
git add . && git commit -m "opis zmian" && git push
```
