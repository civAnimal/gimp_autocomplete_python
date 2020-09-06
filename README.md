## GIMP Auto-Complete Python API for Sublime Text

This auto-complete plugin covers __1000+__ Functions and Constants available in GIMP's Plugin API. All these functions and constants are now just a few keys away. Simply type some letters of the function and press `Enter`. The full function name, qualified by module identifier `pdb`, together with arguments(if any) shall appear at cursor location. Imagine how much typing that would save you.



### Examples

 Text Entered  |  Result
-------------- | -----------------------------------------------------------------------------------------
 `fundst`      | `pdb.gimp_image_undo_group_start(image)`
 `flus`        | `pdb.gimp_displays_flush()`
 `fthwl`       | `pdb.gimp_image_thaw_layers(image)`
 `fgactl`      | `pdb.gimp_image_get_active_layer(image)`
 `fitsn`       | `pdb.gimp_item_set_name(item, name)`
 `fgau`        | `pdb.plug_in_gauss(run_mode, image, drawable, horizontal, vertical, method)`
 `fcub`        | `pdb.plug_in_cubism(run_mode, image, drawable, tile_size, tile_saturation, bg_color)`
 `fgsa`        | `pdb.python_fu_gradient_save_as_css(run_mode, gradient, file_name)`
 `ffo`         | `pdb.python_fu_foggify(run_mode, image, drawable, name, colour, turbulence, opacity)`
 `fstcm`       | `pdb.script_fu_set_cmap(run_mode, image, drawable, palette)`
 `fba`         | `pdb.script_fu_blend_anim(run_mode, image, drawable, value, value, toggle)`
 `cpfi`        | `PF_IMAGE`
 `cpfd`        | `PF_DRAWABLE`
 `crgba`       | `RGBA_IMAGE`
 `crnoi`       | `RUN_NONINTERACTIVE`
 `ctr`         | `TRUE`


### Tips

* Remember, `f` is for ... Functions, and `c` is for ... Constants.
* You don't need to type `pdb` or `.` or any of the prefixes, like `gimp`, `python_fu`, `script_fu`, etc. Just type a few letters from the "true name" of a function/constant. Observe the patterns used in examples.
* You could use `Tab` and `Shift+Tab` to cycle forward and backward through arguments.


### Installation

* Download the plugin (or clone this repository).
* After extraction, copy `gimp_autocomplete_python` folder to Sublime Text's _Packages_ folder.
* You can locate this folder from Sublime Text by using the menu command: _Preferences_ → _Browse Packages_.
* You could start using this plugin straight away; no restart required.


### Notes

* The data is based upon GIMP 2.10.20.01.
* All deprecated functions have been filtered out.
* A Scheme version of this plugin is available here: https://github.com/civAnimal/gimp_autocomplete_scheme/
* This plugin is released under ... GNU General Public License (v3).


### Feedback & Comments

* Email:     civanimal@gmail.com
* Twitter:  `civAnimal`


Copyright © 2020 civAnimal
