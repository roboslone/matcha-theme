# Changelog

This document tracks key updates and improvements for the Matcha Ceremony theme extension.

The changelog follows aspects of [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and uses [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.1] - 2026-05-24

### Fork Maintenance

- Restored the packaged `themes/` and `src/` assets from the published 1.0.0 extension build
- Removed the welcome command, welcome view content, and runtime entrypoint so the package is theme-only
- Fixed the remote-host installation behavior by dropping executable extension code from the manifest
- Added explicit fork attribution to the original author, `fullstacklabXD`, and the original repository

## [1.0.0] - 2026-01-22

### Release Highlights

- 🍵 **Matcha Ceremony** — signature theme evoking tranquil Japanese tea atmosphere
- 🌅 **Dawn** — gentle sunrise variant with calming warmth
- 🌆 **Dusk** — deeper, richer background for evening work
- 🌙 **Midnight** — for those who code into late hours; high contrast, crisp edges
- 🧘 **Zen** — minimalist palette for maximum focus
- 🌸 **Sakura** — whimsical pastels with soft pink accents

### What's New

- Intelligent syntax scopes for improved semantic highlighting
- 6-color rainbow brackets for comfortable navigation
- Terminal color set with unique dark greens and golds
- Git line diff highlighting for additions/changes/destructive removals
- Special Markdown and code block styling for technical writing
- Custom icon for theme preview in VS Code

### Supported Languages

- JavaScript, TypeScript, Python, Rust, Go
- HTML, CSS, SCSS
- Markdown, JSON, YAML
- C, C++, and more
- Enhanced token differentiation for JSX/TSX and markdown headers

### Color Motifs

- **Matcha** (`#7D9B76`) – keywords, flow control
- **Bamboo** (`#A4C49B`) – success, special variables, borders
- **Rice Paper** (`#E8DCC4`) – string literals, UI highlights
- **Wisteria** (`#B8A9C9`) – numeric values, decorators
- **Sea Foam** (`#8FA8A0`) – function names, definitions
- **Kintsugi Gold** (`#C9B896`) – parameters, constants
- **Celadon** (`#7BA3A3`) – types, class identifiers

### Technical Notes

- Requires VS Code 1.60.0 or newer
- Fine-tuned color contrast for accessibility (meets WCAG AA/AAA for key UI)
- JSON theme schema checks enabled
- User documentation and tips included in extension
- MIT Licensed

### Removed

- Support for legacy/experimental VS Code color APIs (pre-v1.50) not included for simplicity
