# JumpStart

_Give your small project a JumpStart_

JumpStart is a small library for quickly getting basic input, database, user session functionality on smaller projects.

## Features
- Single file include that's less under 1000 lines of code
- Includes CORS headers and preflight
- Compatible with MySQL/MariaDB and SQLite
- Database managed sessions

## Jumpstart user access levels
When logged out users are given the default access level of -1. When logged in with their password users have a delegated access level ranging from 1 to 9 to allow for a basic heirarchy of users with different security levels. Users can have multiple pins codes which when logged in with (instead of their password) will give them an access level of 0. Pin codes are designed for things like script authentication, _**they are stored in plain text**_ and can be disabled by uncommenting a killswitch in the library.

## Missing/To be added
- User creation/deletion functions
- User password & pin management
