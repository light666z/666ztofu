# 04 — Site Structure & Information Architecture

## Structural goals

1. A first-time Korean visitor understands the site in one screen
2. Categories stay shallow and crawlable
3. Reviews, guides, and trust pages reinforce each other through internal links
4. URLs are stable from day one (avoid renames after indexing)

---

## Core pages (v1)

| Page | URL | Role |
|------|-----|------|
| Home | `/` | Brand + what we do + start paths |
| About | `/about/` | Mission, editorial stance, who it’s for |
| How we review | `/methodology/` | Scoring system transparency |
| All reviews | `/reviews/` | Review index |
| Guides index | `/guides/` | Fundamentals hub index |
| Providers index | `/providers/` | Studio/provider index |
| Compare index | `/compare/` | Comparison index |
| Responsible play | `/responsible/` | Trust pillar landing |
| Contact | `/contact/` | Feedback / corrections |
| Editorial policy | `/policy/editorial/` | Corrections, conflicts, standards |
| Privacy | `/privacy/` | Standard privacy page |
| Disclaimer | `/disclaimer/` | Informational/entertainment disclaimer |

---

## Recommended URL patterns

```text
/reviews/{game-slug}/
/guides/{guide-slug}/
/providers/{provider-slug}/
/compare/{compare-slug}/
/responsible/{article-slug}/
/lab-notes/{note-slug}/
```

### Slug conventions
- Prefer English-leaning slugs for stability (`sweet-bonanza`, `what-is-rtp`)
- Korean titles remain on-page H1
- Keep slugs short, hyphenated, lowercase
- Never include years unless the page is intentionally dated

---

## Homepage information architecture

Hero budget (first viewport):
1. Brand: **slotreviewlab**
2. One headline (KR)
3. One supporting sentence
4. One CTA group (예: `리뷰 기준 보기` / `초보 가이드 시작`)
5. One dominant visual plane (lab/review atmosphere — not a collage of casino chips)

Below the fold (not in first viewport):
- Start here paths (초보 / 리뷰 / 안전)
- Latest reviews
- Pillar entry cards (links, not decorative clutter)
- Responsible note strip

---

## Navigation (desktop)

**Primary**
- 리뷰
- 가이드
- 프로바이더
- 비교
- 안전/책임
- 리뷰 기준

**Utility**
- 소개
- 검색

**Mobile**
- Same items in a single menu; keep “리뷰 기준” visible because it is a trust differentiator

---

## Internal linking rules

1. Every review links to:
   - `/methodology/`
   - at least one relevant guide (e.g., volatility)
   - provider page when available
2. Every guide links to 2–3 example reviews
3. Every comparison links to the individual review pages it mentions
4. Responsible pages are linked from homepage footer and methodology page

---

## Content templates (page types)

### Review page outline
1. Quick verdict
2. Score card (5 dimensions)
3. Who it suits / who it doesn’t
4. Mechanics breakdown
5. Bonus features
6. Volatility & RTP notes (with source confidence)
7. Pros / cons
8. Final recommendation
9. FAQ
10. Related reviews / guides

### Guide page outline
1. Definition
2. Why it matters
3. How to use the concept when choosing games
4. Common misunderstandings
5. Examples from reviewed games
6. FAQ
7. Next reading path

---

## Taxonomy implementation notes

- **Categories** = main IA buckets (see `03`)
- **Tags** = flexible descriptors (`초보`, `고변동성`, `클러스터페이`, provider names)
- Limit visible tags on a post to 3–5 to avoid noise

---

## Launch IA checklist

- [ ] Categories frozen
- [ ] Methodology page written before review #1
- [ ] Disclaimer + responsible page live before public promotion
- [ ] Homepage start paths point to real published posts
- [ ] 404 and search exist
- [ ] Sitemap + robots configured
