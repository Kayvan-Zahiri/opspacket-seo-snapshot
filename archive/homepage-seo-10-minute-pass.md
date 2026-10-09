# 10-minute homepage SEO pass (public HTML)

A practical first pass you can run yourself in about ten minutes. No CMS login. View-source, DevTools → Elements, or “Inspect” on the live homepage.

**Maker:** OpsPacket (EXP-PMF-02 Site Health). This is a teach checklist, not a ranking campaign. **No ranking, traffic, or revenue guarantees.**

---

## What to check

| Check | What “good” looks like |
| --- | --- |
| **Title** | Present; not “Home” / “Untitled”; roughly ~50–60 characters; unique |
| **Meta description** | Present; roughly under ~155 characters; describes the offer |
| **H1** | Exactly one clear H1 that matches what the page sells |
| **Image alts** | Content images have non-empty `alt` text |
| **Canonical** | Points at the preferred public URL (usually the HTTPS homepage) |
| **noindex / robots** | Not blocked by meta robots `noindex` or `robots.txt` if you want Google to see it |
| **Status** | Public URL returns **200** (not soft-404, not redirect loops) |

---

## P0 / P1 / P2 framing

Sort every finding before you “optimize” copy or buy tools.

### P0 — fix before anything else
- Missing or garbage title
- Soft-404 / non-200 on the public homepage
- Accidental `noindex` (or robots block) on a page you want indexed
- Zero H1, or an H1 that does not match the offer

### P1 — next
- Missing / weak meta description
- Title too long/short or duplicated across pages
- Wrong or missing canonical
- Empty alts on main content images

### P2 — later
- Duplicate H1s
- Weak internal links from homepage to important pages
- Mixed-content / HTTPS polish

Skip vanity scores (DA, “SEO grade,” keyword stuffing) until P0/P1 are clean.

---

## 10-minute workflow

1. Open the public homepage in a private window. Confirm **HTTPS** and a real **200**.
2. View-source: find `<title>`, `<meta name="description">`, `<link rel="canonical">`, meta robots.
3. Count **H1** tags in the body (Elements search for `h1`).
4. Spot-check a few content images for `alt`.
5. Write leftovers as **P0 / P1 / P2** — three short lists, not a 40-page audit.

Printable checkbox version: [self-serve punch-list](self-serve-punch-list.md).

---

## Want it done for you?

- **Free** homepage P0/P1/P2 punch-list (authorized public URL): https://opspacket.com/#free-sample  
- Optional paid **$49 Site Health Snapshot** (≤15 same-site URLs, status CSV, capped top-5 prioritized fixes): https://kayvanandre.gumroad.com/l/seo-snapshot  

Landing: https://opspacket.com/ · Repo / sample: https://github.com/Kayvan-Zahiri/opspacket-seo-snapshot  

Public HTML only. Authorized URLs only. Not affiliated with Google or WordPress.
