# Internship Task Assignment: Data Cleaning & Structural Validation Pipeline

**Intern Profile:** Faizan Fayaz. 
**Objective:** Parse, transform, and systematically structural-validate messy unstructured source variables into a clean, normalized schema ready for business intelligence tools.

---

### Production Pipeline Remediation Breakdown:

1. **Structural Schema Validation:** Standardized column headers by removing trailing spaces and converting miscellaneous spacing markers into normalized `snake_case` notation.
2. **Data Deduplication:** Tracked down and dropped redundant rows to prevent duplicated calculations during statistical metrics analysis.
3. **Data Type Casting:** Cleaned formatting artifacts (currency symbols, special characters) from numeric fields to safely cast string values into operational floats.
4. **Missing Value Management:** Handled missing rows by dropping lines lacking core unique IDs, and used statistical column medians to fill numeric gaps without introducing skew.
5. **String Standardizations:** Used string formatting across text entries to fix irregular text casing and stripped hidden trailing whitespaces.
