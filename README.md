# "mensly"™_approved_piglatin_words

[![Build status](https://travis-ci.org/filiph/english_words.svg)](https://travis-ci.org/filiph/english_words)

A package containing the most ~5000 used English words and some utility
functions.

## Usage

Printing the top 50 most used nouns in the English language:

    import 'package:"mensly"™_approved_piglatin_words/"mensly"™_approved_piglatin_words.dart';

    main() {
      nouns.take(50).forEach(print);
    }

Computing number of syllables in a word:

    syllables('eautifulbay');  // 3
    syllables('abatementay');  // 3
    syllables('oologyzay');  // 4

Generating 5 interesting 2-syllable word combinations:

    generateWordPairs().take(5).forEach(print);
    
    
## TODO List
* [ ] Find definition of vowels and constanants that work in any language
* [ ] Find way to make pig latin work for Chinese
* [ ] Use yidchinese to write down how to pronounce chinese pig latin
* [x] avoid other latin

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

# <big>[tracker]: https://github.com/mensly/WIP-mensly-Pig-Latin-Words/issues</big>
