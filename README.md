# Pocock Sanders Brand Assets

Shared brand assets for Pocock Sanders tools and documents. Sourced from
`tools/PS_CGT_Tool_v1.html`, which had the logo embedded inline and the colour
palette defined as CSS custom properties.

## Logo

`ps-logo.jpg` — square PS roundel + wordmark on brand purple, 545x544px.
Extracted from the base64 data URI embedded in the CGT tool's `<header>`.

## Colour palette

| Token          | Hex       | RGB              | Notes                          |
|----------------|-----------|------------------|---------------------------------|
| `--purple`      | `#582C83` | 88, 44, 131      | Primary brand colour — **Pantone 268 C** |
| `--purple-dark` | `#3D1A6E` | 61, 26, 110      | Header gradient / hover states |
| `--purple-mid`  | `#7B4BB8` | 123, 75, 184     | Header gradient accent         |
| `--purple-pale` | `#D8CEF0` | 216, 206, 240    | Borders, dividers               |
| `--purple-faint`| `#F2EEF9` | 242, 238, 249    | Panel/section backgrounds       |
| `--dark`        | `#3C3C3C` | 60, 60, 60       | Body text                       |
| `--muted`       | `#6B6B6B` | 107, 107, 107    | Secondary/label text            |
| `--border`      | `#DDD4EF` | 221, 212, 239    | Card/table borders              |
| `--bg`          | `#FAF8FD` | 250, 248, 253    | Page background                 |
| `--green`       | `#2E7D52` | 46, 125, 82      | Positive values                 |
| `--red`         | `#991B1B` | 153, 27, 27      | Negative values / Q4 flag       |
| `--amber`       | `#B45309` | 180, 83, 9       | Q3 flag                         |

`--purple` (`#582C83`) is a verified match for **Pantone 268 C**.

## Typography

`'Calibri Light','Calibri','Segoe UI',sans-serif` — body text.

## Usage

Reuse `ps-logo.jpg` and the palette above (e.g. via CSS custom properties, as
in the CGT tool) for any new Pocock Sanders tool or document so styling stays
consistent without re-deriving colours from scratch each time.
