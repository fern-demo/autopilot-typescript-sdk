## 3.0.0 - 2025-11-20
* feat: add new metadata fields and remove User-Agent header
* This change adds two new required metadata fields to the CreateMovieRequest interface and removes the description field from the Movie interface. The User-Agent header has been removed from the client configuration, and all documentation and tests have been updated to reflect these API changes.
* Key changes:
* Add metadata and more_metadata fields to CreateMovieRequest interface
* Remove description field from Movie interface
* Remove User-Agent header from client headers
* Update all examples and tests to include new required fields
* 🌿 Generated with Fern

