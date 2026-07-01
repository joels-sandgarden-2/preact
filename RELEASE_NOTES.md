# Release Notes

## 2026-07-01

* Added sponsor recognition for SentDM, Songsterr, and Deno in the project overview.
* Improved release publishing reliability by turning off package manager caching during publish jobs.
* Enhanced update speed in compatibility mode by reducing unnecessary prop comparison work.
* Updated package publishing to use staged npm releases for more controlled delivery.
* Corrected test configuration so JSX test files ignore the standard dependency directory as intended.
* Fixed recovery during page attachment so suspended or failing content can continue cleanly even when no extra page nodes are available.
* Refined component update handling to avoid redundant work and reduce unnecessary state writes.
* Streamlined cleanup after rendering and unmounting to reduce retained references and lower the risk of memory growth over time.
* Strengthened workflow security and consistency by pinning automation actions to specific trusted versions.
* Expanded server rendered loading support so delayed content can attach more reliably as streamed content arrives.
* Stabilized follow up updates so queued component side effects run in the right order before later renders.
* Balanced generated IDs across async loading boundaries so rendered output stays consistent even when content resolves in different orders.
* Restored recovery from failed partial renders so interrupted content cleans up safely and avoids later crashes.
* Consolidated a forward port of rendering recovery fixes so mainline releases keep the same stability improvements already delivered elsewhere.