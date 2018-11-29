# OScrabl

OScrabl is implemented in OCaml. This implementation assumes having Ocaml and OPAM installed as per the Fall 2018 CS 3110 course installation guidelines. OCaml only runs in Unix-based environments.

Instructions:

Run the following:

opam install yojson

opam install ANSITerminal


To launch the game, navigate into the "OScrabl" directory and run: 

make play


Controls:

place <letter> <x-coordinate> <y-coordinate>
  
exchange <letter1> <optional: letter2> ... <optional: letter7>
 
score

help

recall

pickup

quit

