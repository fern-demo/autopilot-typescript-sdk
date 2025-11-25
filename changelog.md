## 2.1.0 - 2025-11-25
* feat: add new fields to movie creation and update generator version
* This change adds three new fields to the movie creation API and updates the Fern TypeScript SDK generator to version 3.28.11. The movie creation workflow now supports additional metadata fields and ranking capabilities.
* Key changes:
* Add metadata, more_metadata, and rank fields to CreateMovieRequest type
* Remove description field from Movie type and add rank field
* Update README and API documentation with new field examples
* Upgrade generator from version 3.28.6 to 3.28.11
* Switch to native Headers API for better HTTP header handling
* Add custom vitest matchers for header testing in test suite
* 🌿 Generated with Fern

