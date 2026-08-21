# Resume redesign spec — "Rail" layout

Hand this to Claude Code alongside `resume.tex`. `resume.tex` is a
working first pass; treat this file as the source of truth for intent
if the two disagree.

## Structure

Two columns, full-bleed (no page margin — the columns own their own
padding).

- **Sidebar**, 28.7% of page width, tinted `#F2EFE8`, runs full height
  of every page.
  - Page 1: name, accent rule, contact block, Technologies.
  - Page 2, top: Education.
- **Main column**, remaining 71.3%.
  - Summary paragraph (no heading).
  - Experience — 4 entries.
  - Projects — 3 entries.

## Palette

| role | hex |
|---|---|
| body text | `#1B1A16` |
| bullet text | `#33312B` |
| secondary lines (company · place) | `#4F4C44` |
| dates, sidebar labels | `#85806F` |
| sidebar tint | `#F2EFE8` |
| accent (section heads, name rule) | `#3B6BB0` |

## Type

Source Sans Pro throughout (or Helvetica/Arial fallback).

| element | size | weight | treatment |
|---|---|---|---|
| Name | 19pt | bold | — |
| Section head | 7.6pt | bold | uppercase, ~0.18em letterspaced, accent color |
| Entry title (role / project) | 10.2pt | bold | — |
| Entry subtitle (company · place) | 8.8pt | regular | `#4F4C44` |
| Dates | 8.2pt | regular | `#85806F`, flush right on the title line |
| Bullets | 9.2pt | regular | `#33312B`, line-height ~1.26 |
| Summary | 9.4pt | regular | `#33312B`, line-height ~1.38 |
| Sidebar skill label | 7.8pt | regular | uppercase, letterspaced, `#85806F` |
| Sidebar skill value | 8.8pt | regular | `#33312B` |

Accent rule under the name: 28pt wide, 2.2pt tall, accent color.

## Spacing

- Column top padding: 36pt. Sidebar left padding 24pt, right 18pt.
  Main column left padding 24pt, right 32pt.
- Between entries: 11pt. Between a section head and its first entry: 7pt.
- Between sections: 16pt.
- Bullet list: 11pt left indent, 2pt between items.

## Content

Verbatim from the current resume — do not rewrite any bullet.

## Known open items

1. At full content this runs about 1.6 pages. If one page is wanted,
   drop the Mage internship and the coursework line first, then trim
   the trailing benefit clauses ("...enhancing deployment efficiency
   and reliability").
2. Only one bullet carries a number (30% startup time). The XANE.AI
   bullets are the strongest material and read as description — add
   document counts, latency, or the accuracy lift from the Ragas work.
3. Two-column layouts parse badly in some ATS. Keep a single-column
   build of the same content for portal uploads.
