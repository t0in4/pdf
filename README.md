# pdf

## reducing pdf size

#### sudo apt install ghostscript

### gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/printer -dNOPAUSE -dQUIET -dBATCH -sOutputFile=out.pdf input.pdf 

## batch converting *.odt to pdf

### $ for file in ../*.odt; do libreoffice --headless --convert-to pdf "$file"; done

## or

### $ libreoffice --headless --convert-to pdf *.odt

