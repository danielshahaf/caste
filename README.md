# caste - view raw pastebin content

`caste` shows the content of a pastebin.

## Motivation

This happens every day on Freenode:

> &lt;me&gt; jrandom: pastebin the error message you get.
> &lt;jrandom&gt; http://pastebin.com/Yas84GQN

Opening that URL gives a lot of things around the content.  The URL you really
want is:

> &lt;jrandom&gt; http://pastebin.com/raw/Yas84GQN

This project allows you to run:

    caste http://pastebin.com/Yas84GQN

to view the paste contents, as though by

    curl -s http://pastebin.com/raw/Yas84GQN


# Maturity

Currently only one pastebin is known.  I'll add more as I run into them in practice.


# Etymology

Portmanteau of `cat(1)` and `paste (n.)`.


# Similar projects

The only similar project I'm aware of is <https://github.com/e36freak/read_paste>.
