# Topics proposals for the C++ intermadiate Co-learning

## plan

- 17.05.2016: doxygen by delf
- 24.05.2016: introduction to design patterns by christian (+ instructions on compiling scribus by ale)
- 1?.6.2016: exporting to epubepub

## ale

- http://www.modernescpp.com/index.php has a few articles on multithreading (http://www.modernescpp.com/index.php/tag/threads)
- go through (and try out) the changes in C++ 14: https://en.wikipedia.org/wiki/C%2B%2B14
- lift (aufzug) programmieren
- going through [THE WAYS TO AVOID COMPLEXITY IN MODERN C++](http://vitiy.info/Slides/MeetingCPP2015/MeetingCPP2015Complexity.pdf)
- scribus als projekt:
  - markdown export / import mit formelle grammatik (generierte c library)
    - https://github.com/aoloe/scribus-plugin-gettext-markdown-2
    - using the `greg` parser generator:
      - using `markdown_parser.leg`
      - generating a `c` library that has to bound to c++ "events"
  - epub export
    - https://github.com/aoloe/scribus-plugin-export-epub
    - it already creates a zip file (that's epub...) with all the needed files with some basic html in there
    - needs a css file with the matching styles
    - needs an heuristic for placing and resizing images
    - needs an heuristic for placing the text in the right order
  - python scripting in c++ applikation einbinden
    - currently uses a(n unmaintained) fork of the `kross` engine (formerly?) used by kde
    - it compiles but fails at runtime: it's stuck at getting the signals and slots to cross the boundaries
    - create a basic scripting engine for integrating python inside of a c++ program
    - create a scripting engine that can work with qt on boths c++ and python side
- inkscape als projekt
- lambdas:
  - http://maitesin.github.io//Lambda_comparison/ and https://news.ycombinator.com/item?id=11697951
- folds (`...`):
  - http://en.cppreference.com/w/cpp/language/fold
- memory analysis / leeks with valgrind
- high level critical view on real world code snippets: http://www.viva64.com/en/b/0391/
- dependency management with conan https://www.conan.io/ (cf. slides for presentation on the 28 may 2016 @ metalab wiki / c++ user group)

## katrin

- uml
- projects:
  - notepadqq


## delf

- interface to R
- doxygen
- profiling
- clang tools for error analyzing
- designing an std alike algorithm
- how to define an API
- concurrency / parallel computing
- c++ for android
- network programming

## christian

- spezifikationen
- design patterns mit head first
  - https://hfdpcpp.codeplex.com/
- computational statistics
- compiling with debug symbols + `ddd` for debugging

# richard
  - `boxbackup`
    - get the gui into shape
