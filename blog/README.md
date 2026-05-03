# Bonairian Blog Pakket

Dit pakket bevat 18 hoogwaardige Nederlandse SEO-blogs voor bonairian.com,
geoptimaliseerd voor Google en LLM-zoekmachines (ChatGPT, Perplexity, Claude).

## Inhoud

- **18 blog HTML-bestanden** in `/blog/`
- **index.html** — overzichtspagina van de blog
- **sitemap-blog.xml** — XML sitemap (voeg toe aan Search Console)
- **README.md** — dit bestand

## Hoe te installeren in GitHub repo

1. Maak in je repo een map `blog/`
2. Plaats alle HTML-bestanden uit dit pakket in `blog/`
3. Plaats `sitemap-blog.xml` in de repo-root
4. Verwijs vanaf je hoofdsite naar `/blog/index.html`
5. Commit en deploy via Vercel
6. Submit `https://bonairian.com/sitemap-blog.xml` in Google Search Console

## SEO-features per blog

- Volledige schema.org markup (Article + BreadcrumbList + FAQPage)
- Open Graph + Twitter Card tags
- Canonical URL en hreflang nl-NL
- Geoptimaliseerde meta description (150-160 chars)
- Interne links tussen gerelateerde posts
- Mobielvriendelijk responsive CSS
- ~1200-1800 woorden per artikel (Google sweet spot)

## Onderwerpen gedekt

Duiken, snorkelen, windsurfen, Klein Bonaire, Washington Slagbaai, flamingo's,
stranden, 1000 Steps, Salt Pier, mangroves, Donkey Sanctuary, restaurants,
huurauto, beste reistijd, Kralendijk, Rincon, cruise tips en Lac Bay.

## Aanpassen

- **Datum:** Pas `PUBLISH_DATE` aan in de generator als je herpubliceert
- **Logo/OG image:** Vervang `LOGO_URL` en `DEFAULT_OG_IMAGE` paths
- **Auteur:** Pas `AUTHOR` aan voor persoonlijke branding
- **CSS:** Volledig in HTML-bestand, eenvoudig aan te passen

Veel succes met de ranking!
