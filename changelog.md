## 2.1.0 - 2025-11-25
* feat: add new fields to CreateMovieRequest and update Movie interface
* This change expands the movie creation API by adding several new fields to the CreateMovieRequest and updating the Movie interface structure. The API now supports additional metadata fields and ranking information, making it more comprehensive for movie management.
* Key changes:
* Add metadata, more_metadata, rank, and option fields to CreateMovieRequest interface
* Remove description field and add rank field to Movie interface
* Update User-Agent header handling in client configuration
* Update documentation examples and tests to reflect new API structure
* 🌿 Generated with Fern

