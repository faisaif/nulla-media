# nulla-media

Full-resolution images for the nulla.sa storefront, kept here because Salla
resizes uploaded images and caps the theme package at 2 MB. Served unchanged
by jsDelivr:

    https://cdn.jsdelivr.net/gh/faisaif/nulla-media@<tag>/<file>

Files are referenced by a version tag, never by `main`, so a cached page never
shows a half-updated set. To change an image: replace the file, commit, add a
new tag (v2, v3 ...), and point the theme at the new tag.

## Sizes (v2)

Each photo also ships in smaller widths (`<name>-<width>.webp`) so a phone
downloads a file sized for its screen; the browser picks one through `srcset`
and big screens still get the full-resolution original. `hero-phone.mp4` is
the phone hero video re-encoded from the tall master at the same 1080x1920
(H.264, CRF 30): about a third lighter, same measured quality as the
previous upload.

## Fonts (v3)

`fredoka-latin.woff2` is Fredoka (variable, 300-700), Latin subset, as served
by Google Fonts. It is the theme's English face ('Nulla EN'). SIL Open Font
License 1.1, see `OFL-Fredoka.txt`.

## Top sizes (v4)

`tea-banner-4005.webp`, `allulose-wide-3840.webp` and `allulose-mobile-3072.webp`
are the full-resolution top steps of each srcset, re-encoded (WebP q86) from
the originals: same pixels a 2x/4K screen needs, a fifth to a third of the
weight. The untouched originals stay in the repo as masters.
