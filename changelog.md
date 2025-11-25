## 2.1.0 - 2025-11-25
* feat: add new fields to CreateMovieRequest and update Movie schema
* Add three new fields to the CreateMovieRequest interface (metadata, more_metadata, rank) and update the Movie interface to replace description with metadata and add rank field. This extends the API to support additional movie data properties.
* Key changes:
* Add metadata, more_metadata, and rank fields to CreateMovieRequest interface
* Update Movie interface to include metadata and rank fields, remove description field
* Update SDK generator version from 3.28.6 to 3.28.9
* Update code examples and tests to reflect new request structure
* Update dependency versions in package lock file
* 🌿 Generated with Fern

