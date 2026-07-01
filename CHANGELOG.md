# Changelog

## 2026-07-01

* Fixed recovery after rendering errors so partially rendered subtrees clean up correctly and do not crash on later updates.
* Improved `useId` stability so asynchronous Suspense content keeps consistent generated IDs regardless of resolve order.
* Refined effect flushing so pending subtree effects run together before a synchronous rerender proceeds.
* Enhanced streamed hydration so deferred Suspense content restores the correct DOM and preserves working event handlers.
* Updated automation dependencies used in continuous integration workflows.
* Reduced memory retention after rendering and unmounting so replaced trees release references more reliably.
* Streamlined hook updates to avoid redundant work during component update checks and diff completion.
* Corrected hydration error recovery so suspending content without extra DOM children no longer crashes and still reports the original error.
* Repaired the test configuration so dependency exclusions use the correct modules directory name.
* Modernized package publishing so staged npm releases run through the updated publish flow.
* Accelerated shallow prop comparisons to reduce overhead during compatibility checks.
* Simplified the publish workflow by disabling package manager caching during release publishing.
* Expanded sponsor recognition in the project overview with additional tier 3 sponsor logos.