# Simple chess AI

This script is a simple AI playing chess, and is written from the instructions from this article : <https://medium.freecodecamp.org/simple-chess-ai-step-by-step-1d55a9266977>

## Requirements

This script requires python3, the python-chess library and optionnaly virtualenv

## Install in a virtualenv

First, install as root user virtualenv if not previously installed.

```
pip3 install virtualenv

```
Virtualenv is now system-wide installed

Then clone the repository :

```
git clone https://gitlab.com/mikachou/chess-ai
```

Go into the just created directory (chess-ai by default) and initialize a virtualenv :

```
virtualenv venv
```
Then activate virtualenv :
```
source venv/bin/activate

```
Finally install python-chess package :
```
pip3 install python-chess
```
The script should now be usable.

## How to use
Launch the script with following command :
```
python3 cli.py
```
Human plays as white, AI as black.
Chessboard represents white pieces as uppercased letters, black pieces as lowercased letters.
Player types a move by using [algebric notation](https://en.wikipedia.org/wiki/Algebraic_notation_(chess)).