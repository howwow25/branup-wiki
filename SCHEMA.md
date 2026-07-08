# Wiki Schema

## Domain
브랜업(주) — 화장품 수출 전문 중소기업. 업무 지식, 정부지원사업, 수출/계약, 재무, 기술문서, 의사결정 기록.

## Conventions
- File names: lowercase, hyphens, no spaces (e.g., `export-contract-process.md`)
- Every wiki page starts with YAML frontmatter (see below)
- Use `[[wikilinks]]` to link between pages (minimum 2 outbound links per page)
- When updating a page, always bump the `updated` date
- Every new page must be added to `index.md` under the correct section
- Every action must be appended to `log.md`
- **Provenance markers:** On pages synthesizing 3+ sources, append `^[raw/articles/source-file.md]`
  at the end of paragraphs whose claims come from a specific source.

## Frontmatter
  ```yaml
  ---
  title: Page Title
  created: YYYY-MM-DD
  updated: YYYY-MM-DD
  type: entity | concept | comparison | query | summary
  tags: [from taxonomy below]
  sources: [raw/articles/source-name.md]
  confidence: high | medium | low
  contested: true
  contradictions: [other-page-slug]
  ---
  ```

### raw/ Frontmatter
  ```yaml
  ---
  source_url: https://example.com/article
  ingested: YYYY-MM-DD
  sha256: <hex digest of the raw content below the frontmatter>
  ---
  ```

## Tag Taxonomy
- **Business:** contract, export, partner, customer, finance, insurance
- **Government:** support-program, export-voucher, subsidy, monitoring
- **Product:** cosmetics, formulation, certification, packaging, regulation
- **People:** team, role, contact
- **Process:** workflow, approval, reporting, meeting
- **Tech:** developer, infra, project, system, code
- **Meta:** comparison, timeline, decision, guideline

## Page Thresholds
- **Create a page** when an entity/concept appears in 2+ sources OR is central to one source
- **Add to existing page** when a source mentions something already covered
- **DON'T create a page** for passing mentions, minor details
- **Split a page** when it exceeds ~200 lines
- **Archive a page** when content is fully superseded

## Entity Pages
One page per notable entity. Include:
- Overview / what it is
- Key facts and dates
- Relationships to other entities ([[wikilinks]])
- Source references

## Concept Pages
One page per concept or topic. Include:
- Definition / explanation
- Current state of knowledge
- Open questions or debates
- Related concepts ([[wikilinks]])

## Comparison Pages
Side-by-side analyses. Include:
- What is being compared and why
- Dimensions of comparison (table format preferred)
- Verdict or synthesis
- Sources

## Update Policy
When new information conflicts with existing content:
1. Check the dates — newer sources generally supersede older ones
2. If genuinely contradictory, note both positions with dates and sources
3. Mark the contradiction in frontmatter: `contradictions: [page-name]`
4. Flag for user review in the lint report
