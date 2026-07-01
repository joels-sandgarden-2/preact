# Changelog

## 2026-07-01

* Fixed recovery after rendering errors so partially rendered subtrees clean up correctly and do not crash on later updates.
* Improved generated ID stability so delayed content keeps consistent identifiers regardless of load order.
* Refined effect handling so pending updates run together before an immediate rerender proceeds.
* Enhanced streamed hydration so delayed content restores the correct page state and preserves working event handlers.
* Updated workflow dependencies used in automated checks and release steps.
* Reduced memory retention after rendering and unmounting so replaced content releases references more reliably.
* Streamlined state update handling to avoid redundant work during repeated render passes.
* Corrected hydration recovery so delayed content without extra rendered nodes no longer crashes and still reports the original error.
* Repaired the test configuration so dependency exclusions use the correct modules directory name.
* Modernized package publishing so staged releases run through the updated publication flow.
* Accelerated compatibility checks to reduce overhead during quick property comparisons.
* Simplified release publishing by disabling dependency caching during publication.
* Expanded sponsor recognition in the project overview with additional tier 3 sponsor logos.