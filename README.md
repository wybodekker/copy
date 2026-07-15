# copy

copy from scanner to pdf or image file(s)

## Properties

|key|value|
|-:|:-|
|  script:|copy|
|   short:|copy from scanner to pdf or image file(s)|
|    type:|ruby|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|2.05|
| license:|GNU General Public License|
|   intro:|copy, without any options or arguments, scans an image on|
|         |the first available device, at the default size, producing|
|         |a one page PDF (two pages on a duplex scanner), which is|
|         |then displayed with your favorite pdf viewer. The default|
|         |size is the maximum size of the device, unless **DEFAULTX**|
|         |and/or **DEFAULTY** have been set in de configursation file.|

## Options

|option|description|
|:-|:-|
|**General options**||
|-h			|print this help and exit|
|-H, --help		|show full documentation via less and exit|
|-V, --version		|print version and exit|
|-v, --verbose		|be verbose|
|**Device options**||
|-0			|set the scan device nr to 0 (or 1..9)|
|			|the default is 0 (Brother DS-940DW (USB))|
|    --list		|List all devices|
|**brightness,contrast,density options**||
|-b, --brightness=X	|set brightness correction to X percent|
|			| (default: 0)|
|-c, --contrast=X	|set contrast correction to X percent (default: 0)|
|-d, --density=X		|set contrast correction to X dpi (default: 200)|
|**Color mode options**||
|-C, --color		|Color mode (the default)|
|-G, --gray		|Gray instead of Color mode|
|-L, --lineart		|Lineart instead of Color mode|
|**Positioning options**||
|-l, --left=X		|set left offset to X mm (default: 0)|
|-t, --top=X		|set top offset to X mm (default: 0)|
|-x, --x=X		|set width to X mm (default: 210)|
|-y, --y=X		|set height to X mm (default: 297)|
|-A, --A=X		|set page size to X, where X can be A0..A8|
|**Output options**||
|-o, --outfile=X		|set output filename to X (default: copy)|
|-i, --imagetype=X	|set image type to X; default: pdf|
|-j, --jpg		|output to jpg, equivalent to -ijpg|
|**Conversion & Interaction options**||
|-s, --start=X		|Starting number for multiple output files (default: 1)|
|-n, --number=X		|Number of sheets to scan (1 or more, default: 1)|
|-q, --quality=X		|jpg conversion quality (%,default 75)|
|-r, --rotate=X		|rotate X degrees clockwise|
|-e, --examples		|show some examples of use|
