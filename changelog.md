## 3.0.0 - 2025-11-25
* feat: add metadata fields to movie API and remove deprecated properties
* Add support for new metadata fields in movie creation and responses while cleaning up deprecated properties and headers. This enhancement allows for more detailed movie information storage and retrieval.
* Key changes:
* Add metadata, more_metadata, and rank fields to CreateMovieRequest interface
* Remove description field from Movie interface and add rank field
* Remove deprecated User-Agent header from client configuration
* Update all documentation examples and tests to include new fields
* 🌿 Generated with Fern

