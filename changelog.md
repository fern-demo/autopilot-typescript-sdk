## 3.0.0 - 2025-11-20
* feat: add metadata fields and remove description from movie API
* Update movie creation and retrieval endpoints to include new metadata fields while removing the deprecated description field. This enhances the API's data model for better movie metadata handling.
* Key changes:
* Add metadata and more_metadata required fields to CreateMovieRequest
* Remove description field from Movie interface
* Update documentation examples to include new metadata fields
* Remove User-Agent header from client configuration
* Update test cases to reflect new API structure
* 🌿 Generated with Fern

