# BADM Core Courses: Syllabi Reference

Direct links to extracted course syllabi (JSON format) for all BADM core courses analyzed in the curriculum integration project.

---

## Analytics & Quantitative Core

| Course | Title | Syllabi |
|--------|-------|---------|
| **BADM 210** | Business Analytics I | [View JSON](../badm-syllabi/data/extracted_llm/210.json) |
| **BADM 211** | Business Analytics II | [View JSON](../badm-syllabi/data/extracted_llm/211.json) |

**Status:** ✅ Both already AI-integrated

---

## Functional/Business Core

| Course | Title | Syllabi |
|--------|-------|---------|
| **BADM 275** | Fundamentals of Operations Management | [View JSON](../badm-syllabi/data/extracted_llm/275.json) |
| **BADM 310** | Management and Organizational Behavior | [View JSON](../badm-syllabi/data/extracted_llm/310.json) |
| **BADM 310OL** | Management and Organizational Behavior (Online) | [View JSON](../badm-syllabi/data/extracted_llm/310OL.json) |
| **BADM 320** | Principles of Marketing | [View JSON](../badm-syllabi/data/extracted_llm/320.json) |
| **BADM 320OL** | Principles of Marketing (Online) | [View JSON](../badm-syllabi/data/extracted_llm/320OL.json) |

**Status:** ❌ None have dedicated AI integration; high priority for Fall 2026

---

## Strategy & Law Core

| Course | Title | Syllabi |
|--------|-------|---------|
| **BADM 300** | The Legal Environment of Business | [View JSON](../badm-syllabi/data/extracted_llm/300HON.json) |
| **BADM 300HON** | The Legal Environment of Business (Honors) | [View JSON](../badm-syllabi/data/extracted_llm/300HON.json) |
| **BADM 449** | Business Policy and Strategy | [View JSON](../badm-syllabi/data/extracted_llm/449.json) |

**Status:** ⚠️ BADM 449 has case study reference; BADM 300 needs integration

---

## How to Use This Reference

1. **Click a course link** to view the extracted syllabus as JSON
2. **Search for:**
   - `learning_objectives` — Current course learning outcomes
   - `topics` — Weekly schedule and topics
   - `assessments` — Current assessment methods
3. **Cross-reference** with learning outcomes in [SAMPLE_AI_LEARNING_OUTCOMES.md](SAMPLE_AI_LEARNING_OUTCOMES.md)

---

## Data Format

Each JSON file contains:
- `course_number` — Course code (e.g., "210")
- `course_title` — Full course title
- `catalog_description` — Official catalog description
- `learning_objectives` — Array of course learning objectives
- `topics` — Week-by-week topics and readings
- `assessments` — Assessment methods and weights
- `is_core` — Boolean flag indicating if this is a core requirement
- `instructor` — Current instructor(s)
- `semester` — Semester/year of syllabus

---

## Notes

- **Missing:** Regular section of BADM 300 (only Honors variant extracted)
- **Variants:** Online (OL) sections available for BADM 310, 320
- **All extracted from:** `/badm-syllabi/data/extracted_llm/`

---

## For More Context

- **Integration Matrix:** [UNDERGRAD_CORE_AI_MATRIX.md](UNDERGRAD_CORE_AI_MATRIX.md) — Full course mapping to AI tracks and priorities
- **Learning Outcomes:** [SAMPLE_AI_LEARNING_OUTCOMES.md](SAMPLE_AI_LEARNING_OUTCOMES.md) — Sample AI learning outcomes by course
- **Strategy:** [AI_INTEGRATION_STRATEGY.md](AI_INTEGRATION_STRATEGY.md) — Full strategic context and frameworks

---

*Last Updated: January 4, 2026*
*Repository: Gies AI Curriculum Integration Documentation*
