---
title: Series A

resources:

- src: 3x2_photo.png
  name: Photo name 1
  params:
    order: blue
    description: Photo description. If you want to add your own link, specify button_text and button_url here.
    button_text: Button text
    button_url: "https://example.com"

- src: 3x2_with_exif.jpg
  name: Photo with EXIF
  params:
    order: 1
    description: This photo has EXIF info that is automatically extracted. Only JPG and TIFF files supports EXIF. If the automatically extracted time is incorrect, use "timestamp" field to supply your own time.
    timestamp: 2020-01-01 19:45

- src: landscape_panorama.png
  name: Panorama
  params:
    order: 3
    description: Use the "title" field on top of this file to specify a series name for a stylized appearance. It is hidden if "title" is unspecified.

- src: portrait.png
  name: Portrait
  params:
    order: 4
    description: Some description 2.

- src: square.png
  name: Square
  params:
    order: 5
    description: Some description 4.

---
