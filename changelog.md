## 3.0.0 - 2025-11-20
* feat: add metadata fields and update API interface
* Update the IMDB API to include metadata and more_metadata fields in the CreateMovieRequest interface while removing the description field from the Movie interface. This enhances the data model to support additional metadata collection during movie creation.
* Key changes:
* Add metadata and more_metadata required fields to CreateMovieRequest interface
* Remove description field from Movie interface
* Update documentation examples to include new metadata fields
* Remove User-Agent header from client configuration
* Update test fixtures to reflect new API structure
* 🌿 Generated with Fern

