## 3.0.0 - 2025-11-20
* feat: add metadata fields and remove description from Movie API
* Update the IMDB API to include additional metadata fields in movie creation while streamlining the Movie interface. The createMovie endpoint now accepts metadata and more_metadata parameters, and the Movie type no longer includes a description field to reduce complexity.
* Key changes:
* Add metadata and more_metadata fields to CreateMovieRequest interface
* Remove description field from Movie interface to simplify data model
* Update all examples and tests to reflect new API structure
* Remove User-Agent header from client configuration
* 🌿 Generated with Fern

