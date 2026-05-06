# WordPress Plugin Generator Professional

A modern, browser-based scaffolding tool for professional WordPress plugins.

## Features

- **Premium UI**: Dark-mode, high-fidelity interface.
- **Modern PHP Standards**: Support for PSR-4 namespaces and autoloading.
- **Feature presets**:
    - Settings Pages (Admin).
    - Custom Post Types (CPT).
    - Shortcodes.
    - REST API Endpoints.
- **Multilingual UI**: Support for Portuguese, English, and Spanish.
- **Standalone**: Works entirely in the browser using JSZip.

## How to Use

1. Enter your plugin metadata (Name, Slug, Author, etc.).
2. Toggle the features you want to implement.
3. Preview the generated code in the "Preview" tab.
4. Click **Download ZIP** to get your ready-to-use WordPress plugin.

## Technical Details

- **Namespace**: Automatically generated based on Author and Plugin Name.
- **Hooks**: Uses standard WordPress actions and filters.
- **Security**: Includes `defined('ABSPATH') || exit;` in all files.

## License

MIT License.
