 WebP Converter (Safe Version)

Automatically converts uploaded images in WordPress to optimized WebP format
using PHP Imagick.

This lightweight plugin converts images ONLY if the resulting WebP file
is smaller than the original.
<p align="center">
  <img src="dash.jpeg" alt=" WebP Converter Media Settings" width="800">
</p>

============================================================

FEATURES

- Automatic WebP conversion on image upload
- JPEG, PNG, GIF, HEIC support (server dependent)
- Resize to max width / height (aspect ratio preserved)
- EXIF orientation correction
- Adjustable compression quality
- Safe mode: original images are never deleted
- Fully compatible with WordPress Media Library
- Does not affect existing images

============================================================

REQUIREMENTS

- WordPress 5.0 or higher
- PHP Imagick extension with WebP support

============================================================

INSTALLATION

OPTION 1: MU-PLUGIN (RECOMMENDED)

1. Create the folder if it does not exist:
   wp-content/mu-plugins/

2. Copy the plugin PHP file into that folder.

MU-plugins are always active and cannot be disabled accidentally.

------------------------------------------------------------

OPTION 2: STANDARD PLUGIN

1. Upload the plugin folder to:
   wp-content/plugins/

2. Activate the plugin from:
   WordPress Admin → Plugins

============================================================

USAGE

1. Go to:
   WordPress Admin → Settings → Media

2. Enable:
   Convert uploaded images to WebP

3. Adjust:
   - Max width / height
   - Compression quality (recommended: 75–85)

4. Save changes

5. Upload a NEW image from your computer

Note:
Images uploaded before activation are NOT converted.

============================================================

HOW IT WORKS

- Intercepts image uploads using wp_handle_upload
- Converts image to WebP via Imagick
- Compares original vs WebP file size
- Uses WebP only if it is smaller
- Leaves original file untouched for safety

============================================================

NOTES

- HEIC support depends on server configuration
- Imagick must be
- 
## Settings Preview

