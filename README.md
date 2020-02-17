# CCShell

## Description

This is a simple shell written in C for Ubuntu operating system. It might work very well on the most Unix based systems.

It provides very basic features:

- Commands execution
- Pipes
- Logical operators
- Multiple commands processing 

## About this project

I created this project for my Operating Systems course. It was a real challenge to deal with systems's specific features like `fork`, `pipe`, `evecvp` while spending a lot of time building and debugging a custom made parsing algorithm (not perfect though).

It's not very stable and it can be adjusted a lot, but I reached my goal.

## Special credits

This project was made with the help of my project teammate Adrian Cinca (<https://github.com/Cincaa>)

## Build this by yourself

The project structure is very straight forward. 

In the `include` directory are placed your C headers and libraries goes to the `lib` directory.

To build your project, just execute `make` while your current working directory is `src`.

## Launch 

Execute ./src/ccterminal from your terminal.