# ALS & ALSSUND
This is the third chapter of the description detailing a card- and cashless system for Spejdernes Lejr 2017 – obviously in English. The first chapter focused on the opportunities provided by this solution. The second chapter was about cost and UI. This chapter chews on the technologies used.
## Pieces to a puzzle
There are 2 main pieces and a small number of minor pieces to the puzzle. The two main pieces are: ALS og ALSSUND. An intelligent off-line first terminal (ALS) which is an app you may download to any Android smartphone, and a server (ALSSUND) which is an application server, Nginx web server, and MySQL database server, all in one.

ALS is worth nothing without the wristbands! They are a minor piece, being manufactured to specs provided by KOM. Part of the terminals will even attach a barcode scanner via USB – another minor piece, bought of-the-shelf.

ALSSUND will require a few resources and offers a set of RESTful API’s for integrating these resources – a set of user attributes and a bank.

