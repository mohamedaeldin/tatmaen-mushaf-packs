# Tatmaen Mushaf Packs

Mushaf image packs for the Tatmaen iOS app.

## Available Editions

All editions contain 604 pages (page_003.png to page_606.png) in both light and dark modes.

| Edition | Arabic Name | Description | Size |
|---------|-------------|-------------|------|
| `madinah_hafs_standard39_v1` | مصحف المدينة | Standard Madinah edition | ~350 MB |
| `qurancomplex_mumtaz_v1` | المصحف الممتاز | Premium Mushaf | ~350 MB |
| `qurancomplex_khas1_v1` | المصحف الخاص | Special Mushaf | ~350 MB |
| `qurancomplex_jawami_v1` | المصحف الجوامعي | Comprehensive Mushaf | ~400 MB |
| `qurancomplex_adi_v1` | المصحف العادي | Standard Mushaf | ~300 MB |
| `qurancomplex_wasat_v1` | المصحف الوسط | Medium Mushaf | ~250 MB |

## Directory Structure

```
packs/
  {edition_id}/
    metadata.json       # Edition metadata
    README.md           # Edition description
    pages/
      light/            # Light mode images
        page_003.png    # Al-Fatiha
        page_004.png    # Al-Baqarah start
        ...
        page_606.png    # An-Nas
      dark/             # Dark mode images (grayscale inverted)
        page_003.png
        ...
        page_606.png
```

## Page Numbering

- `page_003.png` = Mushaf page 1 (Al-Fatiha)
- `page_004.png` = Mushaf page 2 (Al-Baqarah start)
- `page_606.png` = Mushaf page 604 (An-Nas)

Formula: `file_number = mushaf_page + 2`

## Source

Qurancomplex editions are sourced from:
**King Fahd Complex for Printing the Holy Quran**
https://qurancomplex.gov.sa

## Usage

Images are served via Git LFS. To download a specific page:

```
https://media.githubusercontent.com/media/mohamedaeldin/tatmaen-mushaf-packs/main/packs/{edition_id}/pages/{mode}/page_{number}.png
```

Example:
```
https://media.githubusercontent.com/media/mohamedaeldin/tatmaen-mushaf-packs/main/packs/qurancomplex_mumtaz_v1/pages/light/page_003.png
```

## License

Quran text and images are in the public domain. This repository contains formatted data for app usage.
