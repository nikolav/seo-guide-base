# 🧭 SEO BRZA KONTROLNA LISTA

## 📊 Alati za analitiku i praćenje

### ✅ Osnovni (obavezni)
- Google Search Console — https://search.google.com/search-console
- Google Analytics (GA4) — https://analytics.google.com
- Google PageSpeed Insights — https://pagespeed.web.dev
- Bing Webmaster Tools — https://www.bing.com/webmasters

### ➕ Osnovni (opciono)
- SEOquake — https://backlinko.com/tools/seo-checker
- Ubersuggest — https://neilpatel.com/ubersuggest

### 🧰 Profesionalni / komercijalni alati
- Semrush — https://www.semrush.com
- Ahrefs — https://ahrefs.com
- AccuRanker — https://www.accuranker.com
- Screaming Frog — https://www.screamingfrog.co.uk/seo-spider
- Moz Pro — https://moz.com/products/pro
- SE Ranking — https://seranking.com
- SEObility — https://www.seobility.net
- SEOptimer — https://www.seoptimer.com
- Keyword.com — https://keyword.com

## 📌 Početni setup (redom)

1. Poveži GSC + GA4  
   (pošalji sitemap, proveri indeksiranje, podesi događaje/konverzije)

2. Pokreni tehnički audit  
   (Semrush / Ahrefs)

3. Proveri Core Web Vitals  
   (LCP, INP, CLS)

4. Prati pozicije ključnih reči (nedeljno)

5. Prati saobraćaj i konverzije  
   (poveži SEO sa realnim rezultatima)

## 🚨 1. Indeksiranje i crawlabilnost (SEO blokatori)

- Stranice su indeksirane na Google-u
- Ne postoje blokade u robots.txt za javne stranice
- Nema slučajnog `noindex`
- XML sitemap je validan i poslat u GSC
- SSR / prerenderovani HTML je vidljiv
- Kanonikalni URL-ovi su ispravni
- Nema crawl grešaka ili petlji

## ⚡ 2. Performanse i Core Web Vitals

- LCP < 2.5s
- INP < 200ms
- CLS < 0.1
- Optimizovane slike
- Keširanje i CDN su podešeni
- Minimalno blokirajućeg JavaScript-a

## 📱 3. Mobilna prilagođenost

- Responsive dizajn
- Čitljiv tekst (≥16px)
- Dovoljno veliki touch elementi
- Brzo učitavanje na mobilnim uređajima
- Bez agresivnih pop-up prozora

## 🧱 4. Strategija renderovanja (JS aplikacije)

- SSR ili prerender za javne stranice
- Sadržaj vidljiv bez JavaScript-a
- Meta tagovi renderovani na serveru
- Interni linkovi crawlabilni

## 🏷️ 5. Naslovi, meta i head tagovi

- Jedinstven title po stranici
- Meta opis postoji i ima smisla
- Tačno jedan H1 po stranici
- Ispravan canonical
- Open Graph / social meta tagovi

## 🧠 6. Kvalitet sadržaja i search intent

- Sadržaj odgovara nameri korisnika
- Nema tankog (thin) sadržaja
- Jasno definisana tema stranice
- Dobra struktura (H1–H3)
- Ažuriran i pouzdan sadržaj

## 🧩 7. Headings i semantička struktura

- Jedan jasan i opisni H1
- Logičan redosled headinga
- Headings služe značenju, ne stilu

## 🖼️ 8. SEO za slike

- Alt tekst postoji i opisuje sliku
- Slike su kompresovane (WebP / AVIF)
- Definisana širina i visina
- Lazy loading za slike ispod pregiba

## 🔗 9. Interno linkovanje

- Nema „orphan“ stranica
- Opisni anchor tekstovi
- Breadcrumb navigacija
- Nema pokvarenih linkova

## 🌍 10. URL struktura i rutiranje

- Čisti i čitljivi URL-ovi
- Jedan canonical URL po stranici
- Konzistentni trailing slash-evi

## 🔐 11. Bezbednost i signali poverenja

- HTTPS je forsiran
- Nema mixed content-a
- Postavljeni sigurnosni header-i
- Stranice o firmi / kontakt / privatnost

## 🧬 12. Struktuisani podaci (Schema)

- Dodati samo relevantni schemati
- Podaci odgovaraju vidljivom sadržaju
- JSON-LD format
- Validiran schema markup
