# Dancraft Studioz website

## Open the website

Extract the ZIP first, then open `index.html` in a browser. Keep the files and folders together. For hosting, upload the contents of the extracted folder to your host's publishing folder.

## Replace images

All website images are in `assets/images/`. To replace an image everywhere it is used, save your new image in that folder with the same filename and in the same format. For example, the homepage hero uses `large-format.webp` and the logo uses `dancraft-logo.png`.

To use a different name or extension, add the new image to `assets/images/` and edit the relevant HTML image path. For a background image, update the CSS path. Update the image's alt text when the subject changes.

The shared stylesheets are in `styles/`, JavaScript is in `scripts/`, and the project pages are in `project-detail/`. Each page tries the editable files first. Embedded copies of the original images and CSS load if their separate files cannot be opened.
