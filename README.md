wordcheck
=========

wordcheck checks a list of words against the BIP39 dictionary.

The words are entered on the command line as in the following example

    wordcheck able add aim box cat dog eye fee gap hen moose zoo

The output will be

      1 able                           - OK
      2 add                            - OK
      3 aim                            - OK
      4 box                            - OK
      5 cat                            - OK
      6 dog                            - OK
      7 eye                            - OK
      8 fee                            - OK
      9 gap                            - OK
     10 hen                            - OK
     11 moose                          - Not in bip39 dictionary
     12 zoo                            - OK
     
