# Release Notes

## 2026-07-01

* Added sponsor recognition for SentDM, Songsterr, and Deno in the project overview.
* Improved release publishing reliability by turning off package manager caching during publish jobs.
* Enhanced runtime performance by inverting loop order in a hot path to reduce update overhead.
* Updated package publishing to use staged npm releases for more controlled delivery.
* Corrected test configuration so JSX test files ignore the standard dependency directory as intended.
* Fixed hydration recovery so missing expected excess DOM children during initial render are handled more safely and avoid related crashes.
* Refined component update handling to avoid redundant work and reduce unnecessary state writes.
* Streamlined cleanup after rendering and unmounting to reduce retained references and lower the risk of memory growth over time.
* Strengthened workflow security and consistency by pinning automation actions to specific trusted versions.
* Expanded server rendered loading support so delayed content can attach more reliably as streamed content arrives.
* Stabilized follow up updates so pending subtree and sibling work flushes reliably when rerenders occur before deferred screen updates run.
* Balanced generated IDs across async loading boundaries so rendered output stays consistent even when content resolves in different orders.
* Restored recovery from failed partial renders so interrupted content cleans up safely and avoids later crashes.
* Consolidated a bundle of rendering recovery fixes so this release keeps stability improvements aligned across supported release lines.