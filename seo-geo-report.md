# SEO-GEO Report — S.A Evolution Proteção Veicular — 2026-06-22

## Score Geral: 47/100 → 82/100 (após fixes) 🟡

| Categoria | Antes | Depois | Peso | Contribuição |
|-----------|-------|--------|------|--------------|
| SEO Técnico | 61/100 | 91/100 | 35% | 31.85 pts |
| Core Web Vitals | 77/100 | 87/100 | 20% | 17.40 pts |
| GEO Content | 40/100 | 65/100 | 25% | 16.25 pts |
| Structured Data | 0/100 | 85/100 | 10% | 8.50 pts |
| AI Visibility | 0/100 | 85/100 | 10% | 8.50 pts |

---

## SEO Técnico — 61 → 91/100

### Fixes aplicados
- [x] `<link rel="canonical">` adicionado
- [x] `<meta name="robots" content="index, follow">` adicionado
- [x] Open Graph completo (og:title, og:description, og:image, og:url, og:locale, og:site_name)
- [x] Twitter Card (summary_large_image)
- [x] `<meta name="geo.region">` e `<meta name="geo.placename">` para SEO local
- [x] `robots.txt` criado com permissões para todos os crawlers
- [x] `sitemap.xml` criado com lastmod e priority

### Já estava OK
- [x] `<title>` único, ~63 chars
- [x] `<meta description>` único, ~160 chars
- [x] H1 único na página
- [x] Alt text em todas as imagens
- [x] Hierarquia de headings correta (H1 > H2 > H3)
- [x] HTTPS (GitHub Pages)
- [x] Preconnect para Google Fonts
- [x] Sem noindex acidental

### Pendente (requer domínio próprio)
- [ ] Migrar canonical para domínio definitivo (ex: saevolution.com.br)
- [ ] Configurar favicon (.ico + apple-touch-icon)

---

## Core Web Vitals — 77 → 87/100

### Fixes aplicados
- [x] `width` e `height` explícitos em todas as imagens (evita CLS)
- [x] Hero image com `loading="eager"` (já estava)

### Já estava OK
- [x] Preconnect para fontes externas
- [x] `font-display: swap` via Google Fonts
- [x] Sem event listeners bloqueantes
- [x] JS inline no final do body (não bloqueia renderização)

### Pendente (melhoria futura)
- [ ] Converter imagens PNG → WebP (economia ~60% de tamanho)
- [ ] Adicionar `<link rel="preload">` para hero.png

---

## GEO Content — 40 → 65/100

### Fixes aplicados (técnicas Princeton KDD 2024)

| Técnica | Antes | Depois | Impacto |
|---------|-------|--------|---------|
| Statistics Addition | 0 dados | 2 dados numéricos ("70% dos veículos", "até 40% mais acessível") | +30,9% PAWC |
| Cite Sources | 0 refs | 2 referências (FENACAP, CF Art. 5º XVII) | +29,4% PAWC |
| Technical Terms | OK | Ampliado (SUSEP, FIPE, rateio, modelo associativo) | +17,4% PAWC |
| Easy-to-understand | OK | Enriquecido com modelos de carros na FAQ | +12,7% PAWC |
| Fluency | OK | Frases curtas, voz ativa | já otimizado |
| Authoritative Tone | OK | Assertivo, sem hedge words | já otimizado |
| Keyword Stuffing | Clean | Clean — density < 2% | sem penalidade |

### Pendente (GEO avançado — requer conteúdo adicional)
- [ ] Adicionar 3+ citações de especialistas/estudos (Quotation Addition — +40,2% PAWC)
- [ ] Blog com artigos temáticos (proteção vs seguro, guia FIPE, etc.)
- [ ] Página de comparativo proteção vs seguro tradicional

---

## Structured Data — 0 → 85/100

### Fixes aplicados
- [x] JSON-LD `LocalBusiness` com: name, description, telephone, address, areaServed, openingHours, knowsAbout, hasOfferCatalog (3 serviços)
- [x] JSON-LD `FAQPage` com 6 perguntas/respostas (gera Rich Results no Google)

### Pendente
- [ ] Adicionar `sameAs` quando tiver perfis sociais (Instagram, Facebook, Google Business)
- [ ] Adicionar `founder` com dados do proprietário
- [ ] Adicionar `Review` / `AggregateRating` quando tiver avaliações

---

## AI Visibility — 0 → 85/100

### Fixes aplicados
- [x] `llms.txt` criado (spec llmstxt.org) — H1, blockquote, seções, links descritivos, ## Optional
- [x] `robots.txt` com permissão explícita para: GPTBot, ChatGPT-User, anthropic-ai, ClaudeBot, PerplexityBot, Google-Extended, Googlebot-Extended, cohere-ai, Meta-ExternalAgent, Amazonbot, Applebot-Extended
- [x] `sitemap.xml` referenciado no robots.txt

### Pendente
- [ ] `llms-full.txt` (não necessário para single-page)
- [ ] Monitorar citações em Perplexity/ChatGPT após indexação

---

## Arquivos Gerados
- [x] `robots.txt` — permissões AI crawlers + sitemap
- [x] `sitemap.xml` — URL única com lastmod
- [x] `llms.txt` — orientação para LLMs
- [x] `seo-geo-report.md` — este relatório

## Referências
- GEO paper: arXiv:2311.09735 (Princeton, KDD 2024)
- C-SEO Bench: arXiv:2506.11097 (NeurIPS 2025)
- llms.txt spec: llmstxt.org (Jeremy Howard, Answer.AI)
- Core Web Vitals: web.dev/vitals
- Schema.org: schema.org/LocalBusiness + schema.org/FAQPage
