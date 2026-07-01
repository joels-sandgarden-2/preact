# Release Notes

## 2026-07-01

* Added sponsor recognition for SentDM, Songsterr, and Deno in the project overview.
* Improved release publishing reliability by turning off package manager caching during publish jobs.
* Enhanced prop comparison performance in compatibility mode to reduce unnecessary work during updates.
* Updated package publishing to use staged npm releases for more controlled delivery.
* Corrected test configuration so JSX test files exclude the standard dependency directory as intended.
* Fixed hydration recovery so suspended or failing content can recover cleanly even when no extra DOM nodes are available.
* Refined hook update handling to avoid redundant work and reduce unnecessary writes during component updates.
* Streamlined cleanup after rendering and unmounting to reduce retained references and lower the risk of memory growth over time.
* Strengthened workflow security and consistency by pinning automation actions to specific trusted versions.
* Expanded hydration support so streamed suspense content can attach to server rendered markup more reliably as content arrives.
* Stabilized effect timing so queued effects flush consistently before follow up renders across related components.
* Balanced generated identifiers across async suspense boundaries so rendered markup stays consistent even when content resolves in different orders.
* Restored error recovery for partially rendered content so failed renders clean up safely and avoid follow up crashes.
* Consolidated several suspense, hydration, cleanup, and effect timing fixes to make rendering recovery more dependable across edge cases.