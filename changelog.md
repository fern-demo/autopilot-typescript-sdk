## 3.0.0 - 2025-11-20
* feat: update Movie API with new metadata fields and remove description field
* This change updates the Movie and CreateMovieRequest interfaces to include new required metadata fields while removing the description field. The createMovie method now accepts additional metadata parameters, and the Movie response structure has been simplified.
* Key changes:
* Add metadata and more_metadata fields to CreateMovieRequest interface
* Remove description field from Movie interface
* Update all code examples and documentation to reflect new API structure
* Remove User-Agent header from client configuration
* Update test fixtures to match new request/response formats
* 🌿 Generated with Fern

