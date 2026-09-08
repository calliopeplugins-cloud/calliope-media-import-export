# Export/Import Media

A WordPress plugin for CSV-based media library import, export, preview, batching, and attachment metadata workflows.

## Overview

Export/Import Media helps WordPress administrators move or rebuild media library data without manually re-uploading every file. The Free edition in this repository focuses on CSV export, CSV validation, import previews, batch processing, duplicate prevention, and common attachment metadata such as title, alt text, caption, and description. It can import remote files from CSV URLs and can register files that already exist inside the WordPress uploads directory through Local Import Mode.

The `main` branch contains the validated Free edition codebase for version 1.7.28. Additional commercial features may be available separately through CalliopeWP.

## Key Features

- CSV export for WordPress media library data.
- Date range, media type, and attachment context filters for exports.
- CSV validation and preview before import.
- Batch imports from the WordPress admin.
- Title, alt text, caption, and description metadata support.
- Duplicate prevention in the standard Free workflow.
- Local Import Mode for files already present in `/uploads/`.
- Honor Relative Path option for preserving upload folder structure when available.
- Skip Thumbnail Generation option for faster imports when thumbnails are not needed immediately.
- Downloadable import log after processing.

## Use Cases

- Export a media library to review attachment metadata in a spreadsheet.
- Import media from a CSV prepared during a site migration.
- Register files that were already moved into the uploads directory.
- Preserve titles, alt text, captions, and descriptions for newly imported attachments.
- Run a small media import in batches to reduce timeout risk.

## Requirements

- WordPress: 5.6 or higher.
- PHP: 7.4 or higher.
- WooCommerce is not required by the plugin header.

## Installation

1. Install [Export/Import Media on WordPress.org](https://wordpress.org/plugins/calliope-media-import-export/) from the WordPress Plugins screen, or upload the `calliope-media-import-export` folder to `/wp-content/plugins/`.
2. Activate the plugin in WordPress.
3. Open Export/Import Media in the WordPress admin menu.
4. Start with an export or validate a small CSV import before processing a larger library.

## Documentation

Read the [Export/Import Media documentation](https://calliopewp.com/export-import-media/) for the product guide and Free/Pro scope. The WordPress.org metadata, FAQ, screenshots, and changelog remain in `readme.txt`.

## WordPress.org

View [Export/Import Media on WordPress.org](https://wordpress.org/plugins/calliope-media-import-export/).

## Support

For the Free edition, use the [Export/Import Media support forum on WordPress.org](https://wordpress.org/support/plugin/calliope-media-import-export/). Do not include credentials, private file URLs, customer data, or production logs in public support requests.

## Development

The `main` branch contains the current validated Free version. Use feature branches and pull requests for changes. See `CONTRIBUTING.md` for contribution guidance and `SECURITY.md` for private security reporting.

Do not commit generated ZIP files, database dumps, logs, local configuration files, or credentials.

## License

Export/Import Media is licensed under GPLv2 or later. See `readme.txt` for the WordPress.org license metadata.

## About CalliopeWP

CalliopeWP is the WordPress plugin line developed by Estudio Calliope from Rosario, Santa Fe, Argentina. Explore the [CalliopeWP plugin catalog](https://calliopewp.com/) and [Estudio Calliope](https://calliope.com.ar/).
