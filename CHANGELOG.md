# Changelog

## v1.1.2

### Added or Changed
- Change license to Unlicense; releasing the project fully into the public domain
- Add simplified project cover image


## v1.1.1

### Added or Changed
- Fixed back to top alignment (revert changes)


## v1.1.0

### Added or Changed
- Fixed back to top link alignment deprecated tag, use CSS style instead
- Added contrib.rocks to show top contributors


## v1.0.0

### Added

- Option to specify an endpoint for contact form submissions
- Basic information sent along with custom contact form endpoint
- Option to enable prefetch speculation rule under Optimization plugin (Experimental)
- Option in Safelink to show destination link after clicking scroll-down button
- Link generator page for external Safelink use

### Fixed

- Issue with blogger-feed by using version 0.0.9 (Resolved in v0.0.8)
- Timestamp overflow issue in comments
- Issue where related posts/products didn't always select Product label for Product posts
- Page scrollability issue when lightbox is active
- Size inconsistency between header icons and mobile menu icons
- Resource loading issue when HTTPS redirect is turned off
- PWA plugin usage when link[rel=manifest] already exists
- Middle ads showing in preview mode
- PWA app name display issue with non-English characters
- Scroll to top/bottom functionality

### Improved

- Live search feature and marked it as stable
- PWA to work even if HTTPS redirect is off (when visited over HTTPS)
- PWA feature and marked it as stable

### Implemented

- Experimental Safelink feature

### Removed

- Comment legacy iframe style toggle due to Blogger supporting only one style
- Unnecessary navigation links used for demo purposes
- 13-item limit in tabbed menu
