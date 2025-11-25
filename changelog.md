## 3.0.0 - 2025-11-25
* feat: enhance IMDB movie data model with additional fields
* Add new metadata and ranking fields to the IMDB movie functionality, expanding the data model to support richer movie information. The CreateMovieRequest interface now requires additional metadata fields and ranking information, while the Movie interface has been restructured to remove the description field in favor of a metadata field and new rank field.
* Key changes:
* Add metadata, more_metadata, and rank fields to CreateMovieRequest interface
* Replace description field with metadata field in Movie interface
* Add rank field to Movie interface
* Update documentation examples to include new required fields
* Remove User-Agent header from default client headers
* Update test fixtures to match new data model structure
* 🌿 Generated with Fern

