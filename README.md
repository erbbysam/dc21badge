Overview
========

DEFCON 21 badge hacking.  Work in progress.

Details
=======
Badges have playing card designs varrying by suit and number.  On the
back of each card is a string of numbers.  These appear to be 2-digit
numbers ranging from 01-26 which are ordinals into a mapping of
the alphabet.  The mapping is either the standard A-Z mapping or ROT-13,
seemingly indicated by the suit.  At least some of the sentence
fragements are from Rush's Tom Sawyer.

Badges also have a 3-digit binary number on the back.  Some badges also
depict a simple number generator that produces the following sequence.

    001 (1) <-+
    100 (4)   |
    010 (2)   |
    101 (5)   |
    110 (6)   |
    111 (7)   |
    011 (3) --+


for f in *.txt; do ./decode $f; done

    THOUGHHISMINDISNOTFORRENT
    DONTPUTHIMDOWNASARROGANT
    PATHSNOTOFTENREPEATED
    TRYSOMETHINGELSE
    MAYTAKEYOUDOWN
    THEFIRSTISTHELAST
    GISTEREDTHATTAPAT
    NTHISKEYX
    EEDINTHEREALORDER
    FIRSTISTHELASTBEE

