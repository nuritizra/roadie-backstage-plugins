# Catalog Backend Module for Gravatar

The `@roadiehq/catalog-backend-module-gravatar` package provides a custom Backstage catalog processor that automatically adds a Gravatar profile picture to `User` entities in the Backstage catalog. The processor computes the Gravatar URL based on the user's email address and populates the `spec.profile.picture` field with this URL.

## Features

- **Automatic Gravatar URL Generation**: The processor generates a Gravatar URL for each user based on their email address using the MD5 hash.
- **Profile Picture Population**: The generated Gravatar URL is added to the `spec.profile.picture` field of `User` entities.
- **Seamless Integration**: This processor integrates easily with the Backstage catalog processing pipeline.