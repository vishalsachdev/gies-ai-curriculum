# Gies AI Curriculum Integration Project

**Project Type:** Research & Planning (Admin)
**Repository:** https://github.com/vishalsachdev/gies-ai-curriculum
**GitHub Pages:** https://vishalsachdev.github.io/gies-ai-curriculum/

---

## Purpose

This repository contains strategic planning documents, curriculum analysis, and leadership documentation for integrating AI into Gies College of Business undergraduate programs. Supports the Gies AI Curriculum Task Force (Fall 2025).

---

## Current Focus

> **Phase 2: Curriculum Design (Q1 2026)** - BADM 350 template ready, learning outcomes drafted

Next priority: Design remaining Fall 2026 pilot courses (BADM 211, 310, 320) using BADM 350 as template.

---

## Roadmap

### Phase 1: Research & Planning [COMPLETE]
- [x] Strategic document synthesis (AI_INTEGRATION_STRATEGY.md)
- [x] Peer benchmarking analysis (6 institutions)
- [x] Campus AI Framework integration
- [x] Syllabus extraction pipeline (131 BADM courses)

### Phase 2: Curriculum Design (Q1 2026) [IN PROGRESS]
- [x] Identify undergrad core courses (18 official)
- [x] Map BADM core to AI tracks (7 courses with syllabi)
- [x] Draft L-C-E learning outcomes (BADM focus)
- [x] Create leadership documentation
- [x] Publish GitHub Pages site
- [ ] Design Fall 2026 pilot courses
- [ ] Extend outcomes to other departments (BUS, ACCY, FIN)
- [ ] Create academic integrity guidelines

### Phase 3: Faculty Development (Q2 2026)
- [ ] Faculty development planning for Fall 2026
- [ ] Develop specific module designs for 5 high-priority courses
- [ ] Training curriculum with Google partnership

### Phase 4: Implementation (Fall 2026)
- [ ] Launch AI integrations in core courses
- [ ] Pilot assessment framework

---

## Session Log

### 2026-01-05
- **Completed:**
  - BADM 350 syllabus synthesis across 5 instructor variants (Ghoshal, Gokhale, Pant, Sachdev, Subramanyam)
  - Course renamed: "IT & AI Strategy for Competitive Advantage" -> "Technology and AI Strategy"
  - Created common template: `badm-syllabi/badm350/data/extracted_llm/badm350_common_template.json`
    - 7 L-C-E balanced learning objectives
    - 16-week schedule with 3-week AI module (weeks 13-15)
    - Assessment: 45% exams, 20% project, 20% assignments, 15% participation
  - Updated BADM_350_REDESIGN.md with synthesis findings
  - Updated CURRICULUM_EVOLUTION.md (replaced BADM 410 proposal with BADM 350 enhancement)
  - UNDERGRAD_CORE_AI_MATRIX.md: BADM 350 marked "Template Ready"
  - 3 commits pushed to GitHub
- **Next:**
  - Design Fall 2026 pilot courses (BADM 211, 310, 320) using BADM 350 as template
  - Faculty development planning for Fall 2026
  - Extend outcomes to other departments (BUS, ACCY, FIN)

### 2026-01-04
- **Completed:**
  - AI curriculum integration matrix for BADM core (7 courses)
  - Sample L-C-E learning outcomes document
  - Leadership documentation (cover page + course reference)
  - GitHub Pages site: https://vishalsachdev.github.io/gies-ai-curriculum/
  - Updated course_metadata.json with official core + AI status
  - Added is_core flag to 131 extracted syllabi JSON files
- **Next:**
  - Faculty development planning for Fall 2026
  - Extend learning outcomes to other departments
  - Develop specific module designs for high-priority courses

---

## Key Files

| Location | Description |
|----------|-------------|
| `docs/` | GitHub Pages site (leadership documentation) |
| `docs/index.md` | Cover page for leadership |
| `docs/courses.md` | Course reference with JSON links |
| `strategy/` | Strategic planning documents |
| `strategy/AI_INTEGRATION_STRATEGY.md` | Primary synthesis document |
| `strategy/UNDERGRAD_CORE_AI_MATRIX.md` | BADM core mapping |
| `strategy/SAMPLE_AI_LEARNING_OUTCOMES.md` | L-C-E learning outcomes |
| `badm-syllabi/` | Syllabus extraction data |
| `badm-syllabi/data/course_metadata.json` | 131 courses with AI status |
| `badm-syllabi/badm350/` | BADM 350 synthesis (5 variants -> common template) |

---

## Related

- **Strategy detail:** See `strategy/CLAUDE.md` for comprehensive strategic context
- **Syllabus pipeline:** See `badm-syllabi/PIPELINE.md` for extraction methodology

---

*Last Updated: January 5, 2026*
