# 06 — Site IA (Phase 1 WordPress) — draft awaiting approval

Sources: locked `01`–`05` artifacts  
Status: **draft** — stop for owner approval of **top nav** and **required pages**  
Constraint: simple blog IA only — no app-like structure. Ask before inventing undecided pages.

---

## URL tree (English path slugs; Korean UI labels)

```text
/
├── about/                         # 소개 (publication-focused)
├── methodology/                   # 리뷰 기준 / 방법론 (static)
├── privacy/                       # 개인정보처리방침
├── disclaimer/                    # 고지 + advertising/editorial separation note
├── reviews/                       # 슬롯 리뷰 (category archive)
│   └── {post-slug}/               # individual review posts*
├── guides/                        # 슬롯 가이드 (category archive)
│   └── {post-slug}/
├── discover/                      # 슬롯 발견 (category archive)
│   └── {post-slug}/
└── (uncategorized avoided)        # do not use for launch content
```

\*If WordPress permalinks are sitewide `/%postname%/`, posts live at root (`/sweet-bonanza-review/`) while category archives stay at `/reviews/`, `/guides/`, `/discover/`. That is the recommended default (see permalink section).

**Tags** (theme, provider, bonus-buy, etc.): available on posts, **not** in top nav, **not** required as pretty landing hubs in Phase 1.

---

## Top nav (Phase 1) — proposed short set

UI labels in Korean; paths in English:

| Order | UI label | Path | Notes |
|------:|----------|------|-------|
| 1 | 슬롯 리뷰 | `/reviews/` | Locked category |
| 2 | 슬롯 가이드 | `/guides/` | Locked category |
| 3 | 슬롯 발견 | `/discover/` | Locked category |

**Utility (not in the short top nav — link from footer / about):**  
소개 (`/about/`), 리뷰 기준 (`/methodology/`)

**Open ask:** Keep top nav to the **3 categories only** (recommended, matches locked `02`), or add **소개** as a 4th item?

---

## Footer essentials

| Link / element | Path or content |
|----------------|-----------------|
| 소개 | `/about/` |
| 리뷰 기준 | `/methodology/` |
| 고지 / 면책 | `/disclaimer/` |
| 개인정보처리방침 | `/privacy/` |
| Sitewide ad note | Short line on `/disclaimer/` and/or footer text: display ads for existing sites are separate from editorial (locked `04`) |
| Byline credit (optional microcopy) | `슬롯리뷰랩 편집부` |
| © year + SlotReviewLab | Plain text |

No shop, no social-app megamenu, no “play now” footer CTA block in Phase 1 editorial IA.

---

## Required static pages at launch vs excluded

### Required at launch (proposed)

| Page | Slug | Why |
|------|------|-----|
| 소개 | `about` | Locked: publication-focused About |
| 리뷰 기준 | `methodology` | Locked: methodology as static page, not a category |
| 고지 / 면책 | `disclaimer` | Editorial independence + display-ad separation; non-guarantee stance |
| 개인정보처리방침 | `privacy` | Standard for a public site with ads/analytics potential |

### Explicitly excluded from Phase 1 launch

| Page / area | Why |
|-------------|-----|
| Shop / products / checkout | Not in positioning or monetization model |
| In-article affiliate “where to play” hubs | Phase 2 parking; brand safety |
| Provider hub index as nav section | Phase 2 parking (`02`) |
| Dedicated theme browse nav | Tags only in Phase 1 |
| Legality / access deep guide | Undecided / Phase 2 (`04`) |
| Lab notes / blog-about-process category | Removed from launch categories |
| Newsletter / membership portals | Not approved — **ask before adding** |
| Contact | Mentioned only as a possible page type earlier — **not decided**. Propose **exclude from launch** unless you need a correction/tip form; ask below |

---

## Post URL pattern recommendation

**Recommend:** WordPress permalink  
`/%postname%/`

**Rationale:** Stable, short, English-kebab slugs; avoids date-based churn; works with category archives at `/reviews/`, `/guides/`, `/discover/` without nesting every post under a category path.

**Slug habit:** English kebab-case post slugs (e.g. `sweet-bonanza-review`, `how-to-choose-slots`) even when the on-page H1 is Korean — matches SEO map preference for stable paths.

**Avoid for Phase 1:** `/%year%/%month%/%postname%/` (longer, weaker evergreen URLs for reviews).

---

## Homepage (boring blog home)

Not a product app shell — a simple WP home:

1. Brand + one-line mission (experience-first discovery)
2. Latest posts
3. Entry links to the three categories
4. Optional short link to 리뷰 기준
5. No operator CTA modules in the content area

---

## Phase 2 parking lot (not in launch nav)

| Item | Notes |
|------|-------|
| Provider hubs / provider nav | Parked in `02` |
| Dedicated theme navigation | Use tags first |
| Legality / access content scope | Undecided in `04` |
| Operator / affiliate modules | Commercial placement parked |
| Contact (if later needed) | Corrections, tips, press — only if you request |
| Newsletter / community / shop | Not in Phase 1 |
| Author personal bio pages | About stays publication-focused |
| Nested category trees | Flat three categories only |

---

## Clarification questions (approve nav + required pages)

1. **Top nav:** Approve **3 items only** (리뷰 / 가이드 / 발견), or add **소개**?
2. **Required pages:** Approve **about + methodology + disclaimer + privacy** as the launch static set?
3. **Contact:** Exclude from Phase 1 (recommended), or include a simple `/contact/` page?
4. **Disclaimer slug:** Keep `/disclaimer/`, or prefer `/disclosure/` / Korean-path exception (not recommended if we standardize on English paths)?
5. **Permalink:** Approve `/%postname%/`?

---

## Approval gate

Approve or edit **top nav** and **required pages** before locking. No next-phase work until then.
