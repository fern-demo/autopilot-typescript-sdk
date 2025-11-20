## 3.0.0 - 2025-11-20
* feat: update movie API with new metadata fields
* Updated the movie creation API to include additional metadata fields and modified the movie structure. The CreateMovieRequest interface now accepts two new required metadata fields, while the Movie response type has been simplified by removing the description field.
* Key changes:
* Add metadata and more_metadata fields to CreateMovieRequest interface
* Remove description field from Movie response type
* Update documentation examples and tests to reflect new API structure
* Remove User-Agent header from default client configuration
* 🌿 Generated with Fern

