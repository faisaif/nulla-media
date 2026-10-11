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
