## 3.0.0 - 2025-11-20
* feat: update movie API schema with new fields
* Update the Movie and CreateMovieRequest interfaces to better support movie data management. The Movie interface has been streamlined by removing the description field, while the CreateMovieRequest interface now includes additional metadata fields for enhanced movie information storage.
* Key changes:
* Add metadata and more_metadata fields to CreateMovieRequest interface
* Remove description field from Movie interface to streamline the data model
* Update all code examples and documentation to reflect the new schema
* Remove User-Agent header from client configuration
* Update test cases to match the new API structure
* 🌿 Generated with Fern

