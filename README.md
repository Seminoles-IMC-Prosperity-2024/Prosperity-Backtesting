# Seminoles IMC Porsperity Trading Algorithms

All algorithms are sorted by round. The empty model and starter model are available in the main folder to copy from.

In order to install all proper dependencies use the commands:

    pip install -r requirements.txt
    pip install -U prosperity2bt

To run a backtest use the command:

    prosperity2bt <algorithm location> <round number>

For example:

    prosperity2bt round1/A1.py 1

or

    prosperity2bt starter.py 1

to run the starter file.

## Flags

    --vis

Opens visualizer to see important PnL statistics

    --print

Prints the log in real time for debugging

## Organization

Please push your code frequently so others can see what progress is being made. Also please keep your code organized and follow the file structure:

    round#/algo-name.py

Please make the names distinctive so nothing gets mixed up.

## Source Code

The source code for the backtester and vizualizer can be found here:

https://github.com/jmerle/imc-prosperity-2-backtester
https://github.com/jmerle/imc-prosperity-2-visualizer

more details can be foudn there.




