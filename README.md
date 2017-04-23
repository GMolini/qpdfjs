# qpdfjs

QPdfJs is a desktop application - Portable Document Format (PDF) viewer that is built with Qt and PDF.JS

## Contributing

QPdfJs is an open source project and always looking for more contributors.

## Getting Started

## Getting the Code

To get a local copy of the current code, clone it using git:

    $ git clone git@github.com:yshurik/qpdfjs.git
    $ cd qpdfjs
    
Next, open qpdfjs.pro file in Qt Creator and complete the build or use qmake utility
to generate Makefiles and build the QPdfJs with make command:

    $ qmake qpdfjs.pro
    $ make release
    
## Usage 

QPdfJs is simple desktop application. It can be excuted with command line arguments - list of qpdf files to be opened and shown.

    $ qpdfjs file1.pdf file2.pdf
