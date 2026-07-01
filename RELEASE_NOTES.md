# Release Notes

## 2026-07-01

* Added sponsor recognition for SentDM, Songsterr, and Deno in the project overview.
* Improved release publishing reliability by turning off package manager caching during publish jobs.
* Enhanced prop comparison performance in compatibility mode to reduce unnecessary work during updates.
* Updated package publishing to use staged npm releases for more controlled delivery.
* Corrected test configuration so JSX test files exclude the standard dependency directory as intended.
* Fixed hydration recovery so suspended or failing content can recover cleanly even when no extra DOM nodes are available.
* Refined hook update handling to avoid redundant work and reduce unnecessary writes during component updates.