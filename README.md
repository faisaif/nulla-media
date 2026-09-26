# nulla-media

Full-resolution images for the nulla.sa storefront, kept here because Salla
resizes uploaded images and caps the theme package at 2 MB. Served unchanged
by jsDelivr:

    https://cdn.jsdelivr.net/gh/faisaif/nulla-media@<tag>/<file>

Files are referenced by a version tag, never by `main`, so a cached page never
shows a half-updated set. To change an image: replace the file, commit, add a
new tag (v2, v3 ...), and point the theme at the new tag.
