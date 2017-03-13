# gol
[![Build Status](https://travis-ci.org/aalvarado/gol.svg?branch=master)](https://travis-ci.org/aalvarado/gol)
[![Code Climate](https://codeclimate.com/github/aalvarado/gol/badges/gpa.svg)](https://codeclimate.com/github/aalvarado/gol)

Conway's game of life

### Dependencies
* Ubuntu - Ncurses development library - `libncursesw5-dev`
* OSX - Ncurses `brew install ncurses`

### Usage

clone the project, run `bundle install` and then run:

```
$ ruby start.rb
```

Use arrow keys or h,j,k,l to move, use the spacebar to make a cell alive or dead.

Once you're ready hit `enter` and the game will start.

Hit `q` again to quit the program.

### Run tests

```
$ rspec
```
