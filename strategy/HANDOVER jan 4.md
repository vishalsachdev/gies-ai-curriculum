# Session Handover: Gies AI Curriculum Integration

**Date:** January 4, 2026
**Session Purpose:** Research synthesis and planning for AI curriculum integration at Gies College of Business
**Status:** Research phase complete; awaiting user input to begin planning phase

---

## What Was Accomplished This Session

### 1. Repository Orientation
- Explored `/Users/vishal/admin/undergrad-ai/` structure
- Identified two main workstreams:
  - `badm-syllabi/` — Python extraction pipeline for BADM syllabi (131 courses extracted)
  - `strategy/` — Strategic documents for AI curriculum integration

### 2. Created Strategy Synthesis Documents

**Created: `AI_INTEGRATION_STRATEGY.md`** (820 lines)
- Comprehensive synthesis of all strategy documents
- 16+ sections covering governance, frameworks, implementation, benchmarking
- **Key addition:** Preamble with official Campus AI Framework (four tracks)
- Source citations throughout for authority
- Appendix mapping each section to authoritative source documents

**Created: `CLAUDE.md`** (241 lines)
- Project context file for strategy folder
- Roadmap, current focus, stakeholders
- How-to guide for different users

### 3. Extracted & Converted Source PDFs

Created markdown extracts for easier agent access:
- `Gies AI Curriculum Task Force Charge Letter - Final_extracted.md`
- `comprehensive_AI_Strategy_Nov 2025_extracted.md`
- `Applied AI in Business Schools - Profiles_extracted.md`

### 4. Integrated Official Campus AI Framework

User provided critical clarification: The official Campus AI Task Force decisions are in `Gies AI Strategy End of Term Update.docx`, NOT the agent-generated `CampusAI-TASK-FORCE-SYNTHESIS.md`.

**Official Campus AI Framework (Four Tracks):**
1. **AI Basics/Fundamentals** — Foundational competencies, use cases, responsible use
2. **AI and ML Technologies** — Technical depth (Python, ML, LLMs)
3. **Agentic Systems & Workflows** — Customizing AI agents for workflows
4. **Human Centric AI** — Ethics, governance, sustainability, policy

**Gies Strategic Options Documented:**
- Option A (Recommended): Contribute to campus tracks
- Option B: Develop parallel Gies program
- Option C: Hybrid approach

**Key Gies Opportunity:** Lead national effort on "Agentic AI for Business Workflows" (Track 3)

---

## Key Documents in `/strategy/`

| Document | Type | Purpose |
|----------|------|---------|
| `AI_INTEGRATION_STRATEGY.md` | Synthesis | **START HERE** - Full strategy synthesis with source citations |
| `CLAUDE.md` | Context | Project context for agents |
| `Gies AI Strategy End of Term Update.docx` | **AUTHORITATIVE** | Official decisions, campus framework |
| `Gies AI Curriculum Task Force Charge Letter - Final.pdf` | **AUTHORITATIVE** | Official task force mandate |
| `comprehensive_AI_Strategy_Nov 2025.pdf` | **AUTHORITATIVE** | Gies GenAI Strategy document |
| `Applied AI in Business Schools - Profiles.pdf` | Research | Peer benchmarking (6 schools) |
| `CampusAI-TASK-FORCE-SYNTHESIS.md` | **NOT AUTHORITATIVE** | Agent-generated research; reference only |

---

## Key Documents in `/badm-syllabi/`

| Path | Purpose |
|------|---------|
| `data/course_catalog.json` | 95 BADM courses with descriptions |
| `data/extracted_llm/*.json` | 131 extracted syllabi with structured data |
| `PIPELINE.md` | Extraction methodology |
| `CLAUDE.md` | Project roadmap |

### Syllabus JSON Structure
Each extracted syllabus includes:
- `course_number`, `course_title`, `instructor`, `semester`
- `learning_objectives` (array of strings)
- `topics` (array with week, topic, readings)
- `assessments` (type, weight, description)
- `tools_software` (array)
- `prerequisites` (required, recommended, raw_text)

### AI Already in Some Courses
- **BADM 210:** Week 7 = "LLM & Artificial Intelligence Lab"; objective includes "Explore the power of generative artificial intelligence such as ChatGPT"
- **BADM 211:** Week 6 = "Introduction to AI Tools"

---

## User's Task Force Goals (From Charge Letter)

The user wants help with these specific goals:

1. **Develop clear learning objectives** for AI fluency and responsible use, plus discipline-specific AI competencies

2. **Recommend curriculum integration** into undergrad and graduate core curricula; provide guidelines for majors and electives

3. **Review analytics programs** (MSBA, MSBAi, Business Analytics Minor, Data Analytics concentrations) and recommend AI integration

4. **Identify courses for campus initiatives** (short-form credentials, open content, campus AI Minor, X+AI degrees)

---

## Open Questions (Awaiting User Input)

### 1. Scope & Prioritization
- Which programs first? (Undergrad core aligned with Fall 2026, or all together?)
- Which of the four campus AI tracks should Gies focus on most?

### 2. Course-Level Decisions
- What constitutes "AI integration"? (Module? Tools? Assessments? All?)
- Should I identify courses with existing AI content vs. gaps?

### 3. Learning Outcomes Structure
- What format? (Bloom's taxonomy? Literacy-Competency-Expertise? Campus tracks?)
- How granular? (Program-level? Course-level? Both?)

### 4. Constraints & Resources
- Faculty capacity? (New courses vs. embedding in existing?)
- Technology constraints? (Approved tools like campus ChatGPT, Google Gemini?)

### 5. Deliverable Format
- Matrix mapping courses to AI outcomes?
- "AI-ready" vs. "needs integration" course list?
- Proposed course descriptions for campus contribution?
- Sample learning outcome statements?

---

## Recommended Next Steps

### Immediate (Next Session)

1. **Get user answers to open questions above** — especially scope and deliverable format

2. **Run syllabus analysis** across 131 extracted syllabi:
   - Find courses already mentioning AI/ML/LLM/ChatGPT
   - Identify analytics courses that are candidates for AI enhancement
   - Map courses to Campus AI Framework tracks

3. **Create course-to-outcome matrix** based on user's prioritization

### Short-Term

4. **Draft learning outcomes** for AI fluency (all students) and discipline-specific competencies

5. **Identify Gies courses** that could contribute to:
   - Campus AI Minor (Track 1 Fundamentals)
   - Campus Agentic Systems track (Track 3) — **Gies leadership opportunity**
   - X+AI Business degree pathway

6. **Review MSBA/MSBAi programs** against AI integration requirements

### Medium-Term

7. **Create implementation timeline** aligned with Fall 2026 undergraduate launch

8. **Draft academic integrity guidelines** for AI use in courses

9. **Develop Assessment of Learning framework** for AI competencies

---

## Technical Notes

### Syllabus Analysis Commands

To find AI-related content in syllabi:
```bash
cd /Users/vishal/admin/undergrad-ai/badm-syllabi/data/extracted_llm
grep -l -i "artificial intelligence\|machine learning\|chatgpt\|llm\|generative ai" *.json
```

To extract learning objectives mentioning AI:
```bash
python3 -c "
import json, glob
for f in glob.glob('*.json'):
    data = json.load(open(f))
    for obj in data.get('learning_objectives', []):
        if any(kw in obj.lower() for kw in ['ai', 'artificial', 'machine learning', 'llm']):
            print(f'{f}: {obj}')
"
```

### Key File Paths
- Strategy synthesis: `/Users/vishal/admin/undergrad-ai/strategy/AI_INTEGRATION_STRATEGY.md`
- Course catalog: `/Users/vishal/admin/undergrad-ai/badm-syllabi/data/course_catalog.json`
- Extracted syllabi: `/Users/vishal/admin/undergrad-ai/badm-syllabi/data/extracted_llm/`

---

## Context for Future Agent

**User's Role:** Faculty/staff involved in AI curriculum planning at Gies College of Business, UIUC

**Key Constraint:** Official Campus AI Framework is authoritative (four tracks from `Gies AI Strategy End of Term Update.docx`), not the agent-generated synthesis

**Primary Opportunity:** Gies can lead nationally on "Agentic AI for Business Workflows" (Track 3), complementing Grainger's engineering-focused agent course

**Timeline Pressure:** Fall 2026 is firm deadline for undergraduate AI learning initiatives

**Strategy Approach:** Option A (contribution model) — Gies contributes courses to campus framework while developing business-specific applications

---

## Files Modified This Session

| File | Action |
|------|--------|
| `/strategy/AI_INTEGRATION_STRATEGY.md` | Created (820 lines) |
| `/strategy/CLAUDE.md` | Created (241 lines) |
| `/strategy/HANDOVER.md` | Created (this file) |
| `/strategy/Gies AI Curriculum Task Force Charge Letter - Final_extracted.md` | Created |
| `/strategy/comprehensive_AI_Strategy_Nov 2025_extracted.md` | Created |
| `/strategy/Applied AI in Business Schools - Profiles_extracted.md` | Created |

---

*Handover created: January 4, 2026*
*Ready for next agent to continue planning work*
