# 06 — Site IA (Phase 1 WordPress) — locked

Sources: locked `01`–`05` artifacts + owner IA decisions  
Status: **locked** — owner approved. Do not revise without an explicit new prompt.  
Constraint: simple blog IA only — no app-like structure.

---

## URL tree (English path slugs; Korean UI labels)

```text
/
├── about/                         # 소개 (publication-focused) — footer only
├── methodology/                   # 리뷰 기준 / 방법론 (static) — footer
├── privacy/                       # 개인정보처리방침 — footer
├── disclaimer/                    # 고지 + advertising/editorial separation — footer
├── reviews/                       # 슬롯 리뷰 (category archive)
├── guides/                        # 슬롯 가이드 (category archive)
├── discover/                      # 슬롯 발견 (category archive)
└── {post-slug}/                   # posts via /%postname%/ (not nested under category in URL)
```

**Tags** (theme, provider, bonus-buy, etc.): available on posts, **not** in top nav, **not** required as pretty landing hubs in Phase 1.

---

## Top nav (Phase 1) — locked

UI labels in Korean; paths in English:

| Order | UI label | Path | EN note |
|------:|----------|------|---------|
| 1 | 슬롯 리뷰 | `/reviews/` | Slot Reviews |
| 2 | 슬롯 가이드 | `/guides/` | Slot Guides |
| 3 | 슬롯 발견 | `/discover/` | Slot Discovery |

**Not in top nav:** 소개 (`/about/`) — footer only.  
**Also footer-linked utilities:** 리뷰 기준 (`/methodology/`), 고지 (`/disclaimer/`), 개인정보 (`/privacy/`).

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

### Required at launch — locked

| Page | Slug | Why |
|------|------|-----|
| 소개 | `about` | Publication-focused About |
| 리뷰 기준 | `methodology` | Methodology as static page, not a category |
| 고지 / 면책 | `disclaimer` | Editorial independence + display-ad separation; non-guarantee stance |
| 개인정보처리방침 | `privacy` | Standard for a public site with ads/analytics potential |

### Explicitly excluded from Phase 1 launch

| Page / area | Why |
|-------------|-----|
| Contact (`/contact/`) | Excluded from Phase 1 by owner decision |
| Shop / products / checkout | Not in positioning or monetization model |
| In-article affiliate “where to play” hubs | Phase 2 parking; brand safety |
| Provider hub index as nav section | Phase 2 parking (`02`) |
| Dedicated theme browse nav | Tags only in Phase 1 |
| Legality / access deep guide | Undecided / Phase 2 (`04`) |
| Lab notes / blog-about-process category | Removed from launch categories |
| Newsletter / membership portals | Not approved |

---

## Post URL pattern — locked

**Permalink:** `/%postname%/`

**Rationale:** Stable, short, English-kebab slugs; avoids date-based churn; works with category archives at `/reviews/`, `/guides/`, `/discover/` without nesting every post under a category path.

**Slug habit:** English kebab-case post slugs (e.g. `sweet-bonanza-review`, `how-to-choose-slots`) even when the on-page H1 is Korean.

**Avoid for Phase 1:** `/%year%/%month%/%postname%/`.

---

## Homepage (boring blog home)

1. Brand + one-line mission (experience-first discovery)
2. Latest posts
3. Entry links to the three categories
4. Optional short link to 리뷰 기준
5. No operator CTA modules in the content area

---

## Phase 2 parking lot (not in launch nav) — kept

| Item | Notes |
|------|-------|
| Provider hubs / provider nav | Parked in `02` |
| Dedicated theme navigation | Use tags first |
| Legality / access content scope | Undecided in `04` |
| Operator / affiliate modules | Commercial placement parked |
| Contact | Excluded in Phase 1; only if later requested |
| Newsletter / community / shop | Not in Phase 1 |
| Author personal bio pages | About stays publication-focused |
| Nested category trees | Flat three categories only |

---

## Owner decisions recorded

1. Top nav = **3 categories only**; 소개 via footer, not top nav.
2. Required pages = `/about/` · `/methodology/` · `/disclaimer/` · `/privacy/`.
3. `/contact/` excluded from Phase 1.
4. Keep `/disclaimer/` slug.
5. Permalink = `/%postname%/`.
6. Phase 2 parking lot kept as written.

---

## Approval

**Approved and locked** by owner. No next-phase work until an explicit new prompt.
