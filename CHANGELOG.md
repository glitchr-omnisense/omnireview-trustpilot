# Changelog

## [Unreleased]

### Fixed

- The factory's docblock said the `locale` option is also the invitations' language: it is the
  locale of `/web-links` only, and an invitation is sent in its own `Invitation::$locale` (the
  customer's language). No behaviour changed.
