# Nielsen's Heuristic Evaluation - Kwezy Buses
**Date:** November 21, 2025  
**Evaluator:** Student 22311351007  
**Interface:** https://www.kwezybuses.com/index.php

## Evaluation Framework
Using Nielsen's 10 Usability Heuristics to identify usability problems.

### Severity Rating Scale
- **4 - Catastrophic:** Must be fixed before release
- **3 - Major:** Important to fix, high priority
- **2 - Minor:** Should be fixed, low priority
- **1 - Cosmetic:** Fix if time permits

---

## Heuristic 1: Visibility of System Status
**Issue:** No feedback when users interact with the site
- No loading indicators
- No confirmation of user actions
- No indication of current page/section

**Severity:** 3 (Major)  
**Impact:** Users don't know what's happening or where they are  
**Recommendation:** Add breadcrumbs, loading states, active page indicators

---

## Heuristic 2: Match Between System and Real World
**Issue:** Route presentation doesn't match mental model
- Routes listed alphabetically, not by popularity or logic
- "kasungu" lowercase vs "Blantyre" capitalized (inconsistent)
- No use of familiar booking patterns (origin → destination)

**Severity:** 2 (Minor)  
**Impact:** Confusing terminology and organization  
**Recommendation:** Use consistent capitalization, familiar booking interface

---

## Heuristic 3: User Control and Freedom
**Issue:** No way to undo, redo, or go back
- No clear navigation to other sections
- Users trapped in single-page view
- No emergency exit (home button, back button)

**Severity:** 3 (Major)  
**Impact:** Users feel trapped, frustrated  
**Recommendation:** Add clear navigation, breadcrumbs, home button

---

## Heuristic 4: Consistency and Standards
**Issue:** Multiple consistency violations
- Inconsistent capitalization ("kasungu" vs others)
- No standard booking interface pattern
- Table design breaks web conventions
- Inconsistent spacing and formatting

**Severity:** 3 (Major)  
**Impact:** Confusing, unprofessional appearance  
**Recommendation:** Standardize all text, follow web conventions

---

## Heuristic 5: Error Prevention
**Issue:** No mechanisms to prevent user errors
- No input validation (no inputs exist!)
- Can't select wrong dates (no date selection exists)
- Static page prevents most errors but also prevents functionality

**Severity:** 4 (Catastrophic)  
**Impact:** No booking functionality means primary task cannot be completed  
**Recommendation:** Add booking form with validation

---

## Heuristic 6: Recognition Rather Than Recall
**Issue:** Users must remember all information
- Must scroll back and forth to compare routes
- No visual comparison tools
- No way to save/bookmark favorite routes
- Must remember pricing structure

**Severity:** 3 (Major)  
**Impact:** High cognitive load, difficult comparisons  
**Recommendation:** Add comparison feature, filters, favorites

---

## Heuristic 7: Flexibility and Efficiency of Use
**Issue:** No shortcuts or accelerators
- No search functionality
- No filters or sorting options
- No "recent searches" or "popular routes"
- Same experience for novice and expert users
- Must scroll through entire list every time

**Severity:** 4 (Catastrophic)  
**Impact:** Inefficient, time-consuming, frustrating  
**Recommendation:** Add search, filters, quick access to popular routes

---

## Heuristic 8: Aesthetic and Minimalist Design
**Issue:** Information overload
- 23+ routes displayed simultaneously
- Large, cluttered tables
- No white space
- No visual grouping or hierarchy
- Every route gets equal visual weight

**Severity:** 4 (Catastrophic)  
**Impact:** Overwhelming, difficult to scan, poor first impression  
**Recommendation:** Show limited routes, add search/filter, improve layout

---

## Heuristic 9: Help Users Recognize, Diagnose, and Recover from Errors
**Issue:** No error handling (no interactive elements to generate errors)
- No form validation messages
- No helpful error messages
- No suggestion when search returns no results (search doesn't exist)

**Severity:** 3 (Major)  
**Impact:** When booking is added, errors will be poorly handled  
**Recommendation:** Design clear, helpful error messages for future features

---

## Heuristic 10: Help and Documentation
**Issue:** No help or documentation
- No FAQ section
- No tooltips or help text
- No contact information visible
- No instructions on how to book
- Terms and Conditions links in footer (likely not helpful)

**Severity:** 3 (Major)  
**Impact:** Users don't know how to proceed  
**Recommendation:** Add FAQ, help section, clear instructions

---

## Summary of Critical Issues

### Must Fix (Severity 4)
1. **No booking functionality** - Core feature missing
2. **No search/filter** - Impossible to find routes efficiently
3. **Information overload** - All routes shown at once

### High Priority (Severity 3)
1. No system status feedback
2. Poor navigation and user control
3. Consistency violations
4. Recognition vs recall issues
5. No error handling
6. Missing help documentation

### Total Usability Violations: 15+

## Recommendations Priority
1. Add route search functionality
2. Implement booking flow
3. Redesign layout with visual hierarchy
4. Add filters and sorting
5. Improve mobile responsiveness
6. Standardize formatting and text
7. Add navigation elements
8. Include help documentation

---
**Evaluation Complete:** November 21, 2025