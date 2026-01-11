# BabyStars Landing Page

Statická jednostránková prezentace pro soukromou dětskou skupinu BabyStars v Brně-Bosonohách.

## Struktura
- `index.html` – hlavní stránka (obsahuje SEO meta a strukturu sekcí)
- `styles.css` – responzivní styly, mobile-first
- `main.js` – drobné interakce (FAQ akordeon, smooth scroll)

## Rychlé spuštění
Otevřete `index.html` v prohlížeči nebo spusťte jednoduchý lokální server, například:

```bash
python -m http.server 8000
```

## Nasazení
### Netlify Drop
1. Přejděte na [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Přetáhněte složku `landing/` nebo zip se soubory.

### GitHub Pages
1. Nahrajte obsah složky `landing/` do repozitáře (do hlavní větve nebo `gh-pages`).
2. V GitHub nastavení projektu zapněte **Pages** a jako zdroj vyberte větev/kořen repozitáře.
3. Publikovaná URL se objeví v sekci Pages.

### Vercel
1. Vytvořte nový projekt na [https://vercel.com/new](https://vercel.com/new).
2. Vyberte repozitář se složkou `landing/` nebo nahrajte projekt jako ZIP.
3. V nastavení build stepů není potřeba nic měnit (jedná se o statickou stránku); Vercel použije kořenový obsah.
4. Deploy potvrďte a vyčkejte na URL.

## Tracking placeholdery
V `index.html` jsou zakomentované bloky pro Meta Pixel a GA4. Po doplnění skutečných snippetů je možné je odkomentovat.
