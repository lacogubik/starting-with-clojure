# Starting with Clojure

Introduction into Clojure ecosystem. Guide to functional awesomnes on JVM. paralel, functional, powerful, easy, fluent, frictionless, endless, open, fun 

## Setting yourself up and starting with REPL — Tooling and development, setup, init start

First install Leiningen https://github.com/technomancy/leiningen (Maven done right)

Then setup your IDE.
Emacs is very popular choice (did not used it personally), See https://github.com/clojure-emacs/cider and there is also emacs tutorial in the brave clojure tutorial

For IntelliJ there is fairly new plugin called Cursive https://cursiveclojure.com/. It adds Paredit-style structural editing, code navigation, a symbolic debugger and adds REPL into IntelliJ. Currently in Early Access Program.

LightTable - http://lighttable.com/ More info at http://blog.jayfields.com/2014/01/repl-driven-development.html

TODO Debugging examples — maybe video from LightTable, macro from Foguses book.


## Tutorials — taking first steps in Clojure

Great interactive intro into Clojure is Kyle Kingsbury's Clojure from ground up. http://aphyr.com/tags/Clojure-from-the-ground-up

http://www.braveclojure.com/functional-programming/
http://christophermaier.name/blog/2011/07/07/writing-elegant-clojure-code-using-higher-order-functions




https://github.com/functional-koans/clojure-koans

4clojure.com



## Books - More organised way, more structured way, library?

Programming Clojure (2nd edition) by Stuart Halloway and Aaron Bedra Probably best book to start with I would strongly advise you to try to run all the code examples in the REPL as you are progressing through the book.

The Joy of Clojure, 2nd Edition by Michael Fogus and Chris Houser Great book, which presents lot of advanced concepts and goes really deep. I would not recommend this for start but once you will know some Clojure this book will show you real Clojure power.

Clojure Cookbook Community authored book with lot of useful recipes, you can build it from sources on github.

Structure and Interpretation of Computer Programs, by Abelson, Sussman, and Sussman

## Core libraries and dev stack — Writing your first app, bulding something, scafolding

If you are coming from the Java ecosystem it might surprise you that there are not really big frameworks such as Spring in Clojure, but rather lot of smaller libraries with focused usage.

I do believe that this better approach (Composing from smaller more focused libraries) but for somebody just learning language it might not be easy to start developing.

Ring — Compojure, Liberator, Chesire, Midje, Korma

https://github.com/BrightNorth/bn-webservice

http://www.clojure-toolbox.com/

## Talks worth seeing, talking, presenting, ideas

Simple made easy by Rich Hickey

http://www.infoq.com/presentations/Value-Values

http://clojure.org/state

Simplicity Ain’t Easy by Stuart Halloway

Are we there yet by Rich Hickey

Who to follow Rich Hickey, Stuart Halloway, Michael Fogus, PrismaticEngineering @PrismaticEng, Cognitec, http://planet.clojure.in/, http://cognitect.com/podcast, @aphyr

@cgrand, @cemerick, @marick, @weavejester, @stuartsierra, @seancorfield, @Baranonsky, @richhickey

Michael Fogus interviewed prominent Clojure community members in his “take 5″ series:Anthony Grimes, Jim Crossley, Colin Jones, Daniel Spiewak, Baishampayan Ghose, Kevin Lynagh, William Byrd, Arnoldo Jose Muller-Molina, and Sam Aaron.

Craig Andera launched the Relevance podcast, where he interviewed many Clojurists such as Timothy Baldridge, Jason Rudolph, Rich Hickey (twice), me!, Clojure conference organizers, Michael Fogus (twice), Stuart Halloway, Alan Dipert, Aaron Bedra, Brenton Ashworth, and David Liebke.

## ClojureScript

Om http://swannodette.github.io/2013/12/17/the-future-of-javascript-mvcs/

https://github.com/magomimmo/modern-cljs


## Other

http://clojure.org/cheatsheet

https://github.com/bbatsov/clojure-style-guide

https://groups.google.com/forum/#!forum/clojure — Clojure mailing list

https://github.com/clojure/core.typed
http://adambard.com/blog/clojure-concurrency-smorgasbord
