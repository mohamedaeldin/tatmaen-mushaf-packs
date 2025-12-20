# WithAllah Mushaf Packs

Mushaf data packs for the WithAllah iOS app.

## Available Packs

### Option A: Text Pack (`mushaf_madani_text.zip`)
- Size: ~15 MB
- Contains: JSON page data with Uthmani script text
- Uses Core Text rendering with KFGQPC Uthmanic Script HAFS font

### Option B: Images Pack (`mushaf_madani_images.zip`)
- Size: ~200 MB
- Contains: High-resolution PNG images of all 604 Mushaf pages
- Pre-rendered at 1200x1920 resolution

## Pack Structure

Each pack ZIP contains:
```
manifest.json          # Pack metadata and version info
files_index.json       # File checksums for integrity verification
pages/                 # Page data (JSON or PNG)
  page_001.json/png
  page_002.json/png
  ...
  page_604.json/png
```

## Releases

Download packs from the [Releases](https://github.com/mohamedaeldin/withallah-mushaf-packs/releases) page.

## License

Quran text is in the public domain. This repository contains formatted data for app usage.
