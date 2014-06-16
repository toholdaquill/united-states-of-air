HOWTO
=====

Grab yourself a copy of the-second-bat-guano-war.html. This is the 
master file. Then download Calibre:

    http://calibre-ebook.com/download
  
Run:

    ebook-convert the-united-states-of-air.html the-united-states-of-air.epub \
    --cover the-united-states-of-air-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "The United States of Air: a Satire" \
    --title-sort "United States of Air: a Satire, The" \
    --preserve-cover-aspect-ratio
  
or if you're a Kindle user:

    ebook-convert the-united-states-of-air.html the-united-states-of-air.mobi \
    --cover the-united-states-of-air-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "The United States of Air: a Satire" \
    --title-sort "United States of Air: a Satire, The" \
    --prefer-author-sort
    
or if you just want a PDF:

    ebook-convert the-united-states-of-air.html the-united-states-of-air.pdf \
    --cover the-united-states-of-air-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "The United States of Air: a Satire" \
    --title-sort "United States of Air: a Satire, The" \
    --paper-size a4 \
    --pdf-add-toc \
    --pdf-page-numbers \
    --preserve-cover-aspect-ratio \
    --margin-bottom 72 \
    --margin-top 72 \
    --margin-left 72 \
    --margin-right 72

Calibre's full command-line interface is documented here:

    http://manual.calibre-ebook.com/cli/ebook-convert.html
