## 2.1.0 - 2025-11-24
* feat: add new metadata fields to CreateMovieRequest and update Movie type
* This update extends the CreateMovieRequest interface with two new metadata fields and modifies the Movie type structure. The changes are backward compatible as they add new fields without removing or changing existing ones.
* Key changes:
* Add metadata and more_metadata fields to CreateMovieRequest interface
* Remove description field from Movie type and keep metadata field
* Update examples and tests to reflect the new API structure
* Remove User-Agent header from client configuration
* Update generator version from 3.28.6 to 3.28.7
* 🌿 Generated with Fern

