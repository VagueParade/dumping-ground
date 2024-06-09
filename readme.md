# muOS Font Conversion Code


1.Copy this:

`lv_font_conv --bpp 4 --size 20 --font "`


2.Drag in your `.ttf` / `.otf` / `.woff` file.


3.Copy this:

`" -r 0x20-0x7F --format bin --no-compress --no-prefilter -o "./Downloads/default.bin"`



4.Hit enter, and you'll find it in your Downloads folder on PC/Mac.

___________

You can also use this command line to delete all DS Store files before zipping your files.

`find . -name ".DS_Store" -delete`
