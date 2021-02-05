# unb_lib_zircon
## Drupal 8 Theme Based on Bootstrap.

UNB Libraries Theme.

## License
- unb_lib_theme is licensed under the MIT License:
  - http://opensource.org/licenses/mit-license.html
- Attribution is not required, but much appreciated:
  - `unb_lib_zircon theme by UNB Libraries`

## Notes
- Currently using Bootstrap version 4.5.3 (see global-styling theme library)
  - Subthemes compiling sass should add the following `require-dev` package:  
    "twbs/bootstrap": "~4.5.3",

- Add Font Awesome Icons module, 2.x branch for icons:
  - https://www.drupal.org/project/fontawesome
  - load only the <b>free</b> icon subset, i.e. the <b>Solid</b> and <b>Brand</b> icons <i>(else the non-free icon font
    may take precedence and not display)</i>
     - this is done via the Font Awesome Settings > Partial File Configuration admin config form:
       <kbd>/admin/config/content/fontawesome</kbd>
