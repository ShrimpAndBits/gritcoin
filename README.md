# What you say?

Gritcoin is the world's first, only, and best grain-based currency.

# Where do Gritcoin come from?

Coins are created through a process called milling.  It's nature
is as mysterious and strange as it is wonderful and erotic.

# THE COB #

The kernel of the matter is THE COB - a sequential record of currency
events ordered into neat little rows.  For reasons obscure, THE COB must
always be written in all caps.

THE COB is a text file.  Each line is a niblet.  Niblets are a space-
delimited collection of fields.  There are 2 kinds of niblets:

* millings - The creation of one or more new coins is a milling.  The
fields of a milling are:

   * milling - this literal string
   * number of coins - a positive, non-zero integer
   * recipient - github username of the recipient of the new coins
   * note - up to 1024 bytes of optional additional text associated with the milling.  OK to contain spaces.

* givings - The transfer of one or more coins from one person to another.
The fields of a giving are:

   * giving - this literal string
   * number of coins - a positive, non-zero integer
   * donor - github username of the donor of the new coins
   * recipient - github username of the recipient of the new coins
   * note - up to 1024 bytes of optional additional text associated with the milling.  OK to contain spaces.

A simple version of THE COB might look like:

    milling 10 Alice A wonderful bounty for Alice.
    giving 3 Alice Bob Bob was nice, he gets some coins.
    milling 5 Bob An oil strike, but not as large as Alice's.
    giving Bob 8 Alice Bob's wallet is empty, but his heart is full.

Here are some invalid niblets:

    monkey 14 Alice Bob Monkey?
    giving 3.4 Bob Alice No fractions!
    milling 0 Alice No no-ops!
    milling -46 Bob That's just silly.

# Making a Transfer #

Got some Gritcoin?  Want to feel the pleasure of giving?  Here's what
you gotta do.

1. Get a github account and determine your github id.

2. Log yourself into github in your fancy web browser.

test1
test2 - from a writer
