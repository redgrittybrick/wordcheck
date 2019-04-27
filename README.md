wordcheck
=========

Bitcoin seed-phrases
--------------------

If you have a Bitcoin wallet or some other cryptocurrency wallet, it is
likely you have a 12 word "seed phrase" or "recovery phrase" which can be
used to recreate your wallet if necessary (e.g. if your computer's hard-disk
dies or if your computer is otherwise lost stolen or broken)

The words in these seed-phrases are chosen randomly from a short list
(or dictionary) of words chosen to be clearly distinct and easy to spell.
The standard list is known as BIP39

Sometimes people write down their seed-phrase incorrectly. This program
can be used to check that the seed-phrase is composed of valid words.

wordcheck checks a list of words against the BIP39 dictionary.

How to use wordcheck
--------------------

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
     
Why you can trust wordcheck
---------------------------

It is important never to let anyone else know your seed phrase.
You can download the source-code for this program and read it.
It is very short and easy to understand.

You can download the Go programming-language compiler from https://golang.org/
and use it to compile the source code `wordcheck.go` into the runnable
program `wordcheck.exe`.

If you trust me you can just download the executable `wordcheck.exe` into a
folder on your Windows PC and run it from there. 

You should be safe to run
any program like this if you run it on a computer
that is not connected to the Internet and if you enter your words in random
order, or check them in small groups.
If you compile the program from source code thattyou have read, 
you don't need any precautions like this though.
