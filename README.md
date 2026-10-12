# antoniotrento.github.io

Host vecchio (GitHub user Pages, dal 2017). Il sito ufficiale è **https://antoniotrento.net/**.

Questo repo non è più un sito: è un ponte SEO. Ogni URL pubblica fa meta-refresh + `rel=canonical` verso il corrispettivo su `antoniotrento.net` (il blog verso `blog.antoniotrento.net`). GitHub Pages non fa HTTP 301; canonical + refresh 0 è il massimo che questo host può fare.

**Non** linkare questo host da `antoniotrento.net`. Il succo deve uscire da qui, non tornare indietro.

Mappa (12 ott 2026):

| Qui | Destinazione |
|---|---|
| `/` | `https://antoniotrento.net/` |
| `/blog.html` | `https://blog.antoniotrento.net/it/` |
| `/biografia.html`, `/about.html` | `https://antoniotrento.net/biografia/` |
| `/portfolio.html`, post 2016–17 `/fullit/` ecc. | `https://antoniotrento.net/portfolio/` |
| `/contatti.html` | `https://antoniotrento.net/contatti/` |
| `/servizi.html`, `/archive.html`, `/tags.html`, `/grazie.html` | `https://antoniotrento.net/` |

GSC: proprietà `https://antoniotrento.github.io/` se non c’è già. Non chiedere l’indicizzazione di queste URL come contenuto. Lascia recrawlare i redirect. Non aggiungere questo host nella nav del sito nuovo.
