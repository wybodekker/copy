# copy
|     key | description
|     ---:|:---
|  script | copy - copy from scanner to pdf or image file(s)
|    type | ruby
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 2.00
| license | GNU General Public License

copy, without any options or arguments, scans an image on the first
available device, at maximum size, and produces a one page PDF, named copy.pdf,
unless you use the --outfile=X option to change the name to X.pdf..
With the --number option, a multi-page pdf document can be produced.
