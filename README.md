## Container based on ubuntu:xenial with installed pdf2htmlEX.
Included a manifest file without a default viewer.

## Convert pdf to html
Html file is here `~/pdf/test.pdf`

Run `docker run -it --rm -v ~/pdf:/pdf vamli/pdf2htmlex pdf2htmlEX test.pdf` to convert pdf to html.
Run `docker run -it --rm -v ~/pdf:/pdf vamli/pdf2htmlex pdf2htmlEX` to see available options.
