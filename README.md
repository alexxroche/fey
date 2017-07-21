Ever since XV I've been looking for the perfect image viewing program.
feh does exactly what I need for all static raster images (jpeg,png...)

This wrapper script calls feh with the flags and arguments that I would
have had as defaults.

I also use feh to view images over http using: feh -qxw --rcfile= https://[user[:pass]@]www.example.com/path/2/image.jpg

The gif viewer that I use is sxiv and have an equivalent wrapper called gifs.

The first half of my wrapper script binds into my personal bash lib to attempt to automatically install feh if it is missing.

Honourable mention to: qiv -emtifl --vikeys "$@"

