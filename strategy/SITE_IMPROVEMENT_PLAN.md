# GitHub Pages Site Improvement Plan

**Date:** January 5, 2026
**Source:** Associate Dean user testing feedback
**Status:** Recommendations pending implementation

---

## Implementation Status

### ✅ Completed (2026-01-05)
- [x] Enhanced Executive Communication
  - [x] Executive Brief callout on home page
  - [x] Key Decisions Required section
  - [x] Quick Start for Leadership guide (3-minute read pathway)

### 📋 Pending Implementation

The following recommendations are stored for future implementation:

---

## 2. Visual Communication

**Issue:** Heavy text-based presentation may lose busy administrators.

**Priority:** HIGH
**Estimated Effort:** Medium (4-8 hours)

### Recommendations:

1. **Add visual timeline** showing Spring 2026 design → Fall 2026 launch
   - Tool: Mermaid diagram or timeline visualization
   - Location: AI Strategy page
   - Effort: 1-2 hours

2. **Create track infographic** showing the three AI tracks with example courses
   - Visual showing AI Basics, Agentic Systems, Human Centric tracks
   - Include sample courses in each track
   - Location: Strategic Context section on home page
   - Effort: 2-3 hours

3. **L-C-E progression diagram** showing how students advance from Literacy → Competency → Expertise
   - Arrow-based progression chart
   - Location: Learning Outcomes page
   - Effort: 1 hour

4. **Gap analysis visualization** (currently 3/8 ready, 5/8 need work)
   - Progress bar or dashboard-style visualization
   - Location: Core Matrix page
   - Effort: 1 hour

5. **Curriculum Evolution roadmap diagram** showing Tier 1 (Fall 2026) → Tier 2 (Spring 2027) → Tier 3 (2028+)
   - Multi-phase timeline with milestones
   - Location: Curriculum Evolution page
   - Effort: 2 hours

---

## 3. Decision Support & Risk Management

**Issue:** Missing information administrators need to evaluate feasibility.

**Priority:** HIGH
**Estimated Effort:** High (6-10 hours)

### Recommendations:

1. **Add Faculty Development Requirements section:**
   - How many faculty need training?
   - What partnerships exist (Google mentioned)?
   - Timeline for faculty prep
   - Location: AI Strategy document, new section
   - Effort: 2-3 hours

2. **Include Resource Implications:**
   - Technology needs
   - Staffing requirements
   - Course development effort
   - Location: AI Strategy or new Resources page
   - Effort: 2-3 hours

3. **Add Risk & Mitigation section:**
   - What if we can't hire AI governance faculty?
   - Contingency if BADM 350 enhancement isn't approved
   - Faculty adoption challenges
   - Location: AI Strategy document, new section
   - Effort: 2-4 hours

---

## 4. Navigation Improvements

**Issue:** Not immediately clear how to use the documentation effectively.

**Priority:** MEDIUM
**Estimated Effort:** Low (1-2 hours)

### Recommendations:

1. **Make "START HERE 👉" more visually prominent**
   - Larger badge, highlighting, or colored box
   - Location: Home page, Documents section
   - Effort: 15 minutes

2. **Add anchor links within long documents**
   - Table of contents with jump links
   - Location: AI Strategy document
   - Effort: 30 minutes

3. **Visual hierarchy improvements**
   - Ensure headers follow consistent pattern
   - Add visual separators between major sections
   - Location: All pages
   - Effort: 1 hour

---

## 5. Course Reference Enhancements

**Issue:** Course reference page is functional but could be more powerful.

**Priority:** MEDIUM
**Estimated Effort:** Medium (3-5 hours)

### Recommendations:

1. **Move "How to Use This Reference" to the top**
   - Currently buried at bottom
   - Location: courses.md
   - Effort: 5 minutes

2. **Add filtering options:**
   - Show only courses needing AI integration
   - Filter by track (AI Basics, Agentic Systems, Human Centric)
   - Filter by L-C-E level
   - Note: Requires JavaScript or separate pages
   - Effort: 3-4 hours

3. **Change "View Course" to more descriptive labels**
   - "View Syllabus Details" instead of generic "View Course"
   - Location: courses.md template
   - Effort: 10 minutes

4. **Add course status summary at top**
   - "3 ready, 5 need enhancement, 1 template ready"
   - Location: courses.md
   - Effort: 15 minutes

---

## 6. Content Additions

**Issue:** Missing content that leadership typically asks about.

**Priority:** LOW-MEDIUM
**Estimated Effort:** High (8-12 hours)

### Recommendations:

1. **FAQ section** addressing common leadership questions:
   - How does this compare to peer institutions?
   - What's the competitive positioning benefit?
   - How does this affect accreditation?
   - What happens if a course isn't ready by Fall 2026?
   - Location: New page or section on home page
   - Effort: 3-4 hours

2. **Success Metrics section:**
   - How will we measure effectiveness?
   - Student learning outcomes assessment plan
   - Industry feedback mechanisms
   - Location: AI Strategy document
   - Effort: 2-3 hours

3. **Peer Comparison Summary**
   - Strategy mentions 6 schools but no summary table
   - Create comparison matrix: institution | AI courses | approach | highlights
   - Location: AI Strategy document
   - Effort: 3-5 hours

---

## 7. Mobile/Accessibility

**Issue:** Tables may not display well on smaller screens.

**Priority:** MEDIUM
**Estimated Effort:** Medium (2-4 hours)

### Recommendations:

1. **Test responsive design on tablet/mobile**
   - Check all tables, especially Core Matrix
   - Effort: 1 hour testing

2. **Consider card-based layout for course listings on smaller screens**
   - CSS media queries for responsive tables
   - Effort: 2-3 hours

3. **Add "skip to content" links for accessibility**
   - WCAG 2.1 AA compliance
   - Effort: 30 minutes

---

## Priority Ranking Summary

### Immediate (already completed):
- ✅ Executive Brief callout
- ✅ Key Decisions Required section
- ✅ Quick Start for Leadership

### Next Phase (High Impact, Low-Medium Effort):
1. Make "START HERE" more prominent (15 min)
2. Move "How to Use" to top of Courses page (5 min)
3. Add timeline visual to AI Strategy (1-2 hours)
4. Add course status summary to Courses page (15 min)
5. Change "View Course" to "View Syllabus Details" (10 min)

### Future Enhancements:
- Visual Communication (full suite)
- Decision Support & Risk Management
- FAQ section
- Peer Comparison Summary
- Mobile/accessibility improvements

---

## Notes

- Some recommendations require JavaScript (filtering) which may need MkDocs plugins
- Visual diagrams can use Mermaid (supported by MkDocs Material)
- Timeline visuals could use vis-timeline or custom Mermaid
- Keep design consistent with MkDocs Material theme

---

*This plan preserves all user testing feedback for systematic implementation.*
