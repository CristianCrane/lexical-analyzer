This is the first step in building a programming language from scratch - the lexical analyzer. 

This program scans each token (eg. space separated character/sequence of characters) one-by-one and ensures that all tokens are at least part of the alphabet that has been defined for the given programming language.

At the heart of the program is a finite state automaton which allows the ability to keep track of valid keywords & symbols. Each token is then extracted and the state of the machine changes accordingly. If an undefined symbol is extracted, the appropriate error message is shown.

Now that we can detect whether we at least are dealing with the correct symbols/tokens in a given statement, the next step is to figure whether these tokens are in the correct order. 

This will be handled in the next project, the top-down-parser.
