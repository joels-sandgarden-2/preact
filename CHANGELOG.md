# Changelog

## 2026-07-01

* Fixed recovery after rendering errors so partially rendered subtrees clean up correctly and do not crash on later updates.
* Improved generated ID stability so asynchronous fallback content keeps consistent identifiers regardless of resolve order.
* Refined effect handling so pending updates run together before a synchronous rerender proceeds.
* Enhanced streamed hydration so deferred content restores the correct page state and preserves working event handlers.
* Updated workflow dependencies used in automated checks and release tasks.
* Reduced memory retention after rendering and unmounting so replaced trees release references more reliably.
* Streamlined state update handling to avoid redundant work during repeated render checks.
* Corrected hydration recovery so suspending content without extra rendered nodes no longer crashes and still reports the original error.
* Repaired the test configuration so dependency exclusions use the correct modules directory name.
* Modernized package publishing so staged npm releases run through the updated publication flow.
* Accelerated compatibility checks to reduce overhead during shallow property comparisons.
* Simplified release publishing by disabling package manager caching during publication.
* Expanded sponsor recognition in the project overview with additional tier 3 sponsor logos.