[Home](index.html) | [AI Strategy](AI_INTEGRATION_STRATEGY.html) | [Core Matrix](UNDERGRAD_CORE_AI_MATRIX.html) | [Learning Outcomes](SAMPLE_AI_LEARNING_OUTCOMES.html) | [Curriculum Evolution](CURRICULUM_EVOLUTION.html) | [Courses](courses.html)

---

# BADM Core Courses: Syllabi Reference

Direct links to extracted course syllabi (JSON format) for all BADM core courses analyzed in the curriculum integration project.

---

## Analytics & Quantitative Core

| Course | Title | Syllabus |
|--------|-------|---------|
| **BADM 210** | Business Analytics I | [View Course](courses/210.html) |
| **BADM 211** | Business Analytics II | [View Course](courses/211.html) |

**Status:** ✅ Both already AI-integrated

---

## Functional/Business Core

| Course | Title | Syllabus |
|--------|-------|---------|
| **BADM 275** | Fundamentals of Operations Management | [View Course](courses/275.html) |
| **BADM 310** | Management and Organizational Behavior | [View Course](courses/310.html) |
| **BADM 320** | Principles of Marketing | [View Course](courses/320.html) |

**Status:** ❌ None have dedicated AI integration; high priority for Fall 2026

---

## Strategy & Law Core

| Course | Title | Syllabus |
|--------|-------|---------|
| **BADM 300** | The Legal Environment of Business | [View Course](courses/300HON.html) |
| **BADM 300HON** | The Legal Environment of Business (Honors) | [View Course](courses/300HON.html) |
| **BADM 449** | Business Policy and Strategy | [View Course](courses/449.html) |

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
- **All extracted from:** `/badm-syllabi/data/extracted_llm/`

---

## For More Context

- **Integration Matrix:** [UNDERGRAD_CORE_AI_MATRIX.md](UNDERGRAD_CORE_AI_MATRIX.md) — Full course mapping to AI tracks and priorities
- **Learning Outcomes:** [SAMPLE_AI_LEARNING_OUTCOMES.md](SAMPLE_AI_LEARNING_OUTCOMES.md) — Sample AI learning outcomes by course
- **Strategy:** [AI_INTEGRATION_STRATEGY.md](AI_INTEGRATION_STRATEGY.md) — Full strategic context and frameworks

---

*Last Updated: January 4, 2026*
*Repository: Gies AI Curriculum Integration Documentation*
