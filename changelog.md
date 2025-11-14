## 3.0.0 - 2025-11-14
* feat: add metadata fields to movie creation and update SDK configuration
* This change introduces new metadata capabilities to the movie API by adding required `metadata` and `more_metadata` fields to the CreateMovieRequest interface. The Movie interface structure has been simplified by removing the `description` field while retaining the `metadata` field. Additionally, SDK configuration has been updated with generator version changes and HTTP header modifications.
* Key changes:
* Add required `metadata` and `more_metadata` fields to CreateMovieRequest interface
* Remove `description` field from Movie interface
* Update generator version from 3.28.6 to 3.28.7 and CLI version from 0.113.1 to 0.112.0
* Remove User-Agent header from client configuration
* Update documentation examples and tests to reflect new required fields
* Upgrade various dependency versions in pnpm-lock.yaml
* 🌿 Generated with Fern

