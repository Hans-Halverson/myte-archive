# myte-archive

Archive of old versions of the Myte language. Contains the following:

## mytek

The first implementation of Myte, and by far the most complete of the old versions. Implemented in Kotlin from around 11/2017 - 08/2018, and consists of a parser, lexical analyer/type checker, and tree walk interpreter.

Very feature complete, including support for basic data types, variants types, pattern matching, traits, collections, etc. Not well tested however, and the type checker tries to do a lot of inference and is fairly buggy.

## myter

The beginnings of a Myte implementation in Rust. Implemented a significant chunk of the parser, lexical analyze/type checker, and tree walk interpreter.

## mytepp

Only the very beginnings of a parser for Myte in C++.

## sublime-text-syntax

Syntax definition of the Myte language implemented in `mytek` for use in Sublime Text. Conforms to the TextMate grammer-like `.sublime-synatx` specification to enable syntax highlighting in Sublime Text.