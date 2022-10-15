# Pi-Erlang
Hello there I have made a program in Erlang language.
It works by taking a number and print the patter:14159... till the number specified i.e., digit index
I first defined math module since the pattern 
 % hello world program
-module(helloworld).
-module(math).
-export([start/0]).

start() ->
    io:fread('enter',"~f)".
    io:fwrite(math:math.pi',"~f").
    
    
