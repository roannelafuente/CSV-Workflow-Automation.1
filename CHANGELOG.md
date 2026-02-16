# 📑 CHANGELOG

All notable changes to the CSV Workflow Automation Tool are documented here.

---

## Initial Release
- First release of the CSV Workflow Automation Tool.  
- Automated CSV → Excel conversion with professional formatting.  
- Pivot table generation for quick fallout analysis.  
- End Test number validation to ensure data integrity.  
- Tkinter GUI for file selection, filter dropdowns, and status logging.  
➡️ [View Initial Release](https://github.com/roannelafuente/CSV-Workflow-Automation)

---

## v1.0.0 – Wafermap Prototype
- Introduced wafermap visualization with **random coloring** (prototype stage).  
- Continued automation of CSV → Excel workflows and pivot table generation.  
- Fallout analysis by filtering `C1_MARK` values and calculating End Test fallout percentages.  
➡️ [View v1.0.0 Release](https://github.com/roannelafuente/CSV-Workflow-Automation-v1.0.0)

---

## v1.1.0 – Production Wafermap
- Third release featuring **production-ready wafermap color coding** via defined `color_map`.  
- Accurate `C1_MARK` lookup for End Test mapping.  
- Scrollable status box for improved log navigation.  
- GUI branding with title and developer attribution.  
- Replicates workplace wafermap references for reproducibility and audit-ready insights.  
➡️ [View v1.1.0 Release](https://github.com/roannelafuente/CSV-Workflow-Automation-v1.1.0)

### v1.1.1 – Wafermap Bug Fix
- Fixed issue where numeric `C1_MARK` values (e.g., `"1.0"`) failed to match intended color mapping keys (e.g., `"1"`).  
- Values are now normalized to ensure consistent lookups.  
- Special characters and alphanumeric mappings remain unaffected.  
➡️ [View v1.1.1 Patch]()
