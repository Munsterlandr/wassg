# Wow, Another Static Site Generator (WASSG)
This project exists because of a gripe of mine with other SSGs: they abstract too much from the HTML. Instead of that, this one takes the opposite approach: everything is just HTML (or XML) with some extra code thrown in. Think of it more like a Preprocessor than a normal Static Site Generator.

## How to use
A core part of WASSG is that it just has you add ```.wassg``` to the end of files you want it to process. This makes it extremely versatile. As for the syntax itself, it's inspired by annotations.

The program splits each page up into sections, which are defined by calls. These are divided into the operation itself, a label, and data. The call begins with an @, then is the operation, then optionally the label is given by following the operation with $, then the data is given within curly brackets.

### Examples

