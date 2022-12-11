# Wordle Solver
### Brief
I create a solver for pop game WORDLE. With this program, you can:
1. Just give it a hint each round when it guesses a word, and you'll be able to solve puzzles quickly.
1. Extend the corpus from your word list file if needed.

### Usage
Enter the folder where `main.py` is located, and

* run the solver directly with

    ```python main.py```

* extend the corpus and run the solver with

    ```python main.py [-u <path>][--update <path>]```
    
### Interactions
In each round, the solver will first guess a word. At this time, you have to give it a **hint** according to the result (the default is green, yellow and gray spots), and proceed in this way until the end of the game. E.g: If the result shows like this, 

![](https://github.com/coolguazitech/WordleSolver/blob/main/wordle_eg.jpg)

then the hint you'll give it is 'XBXXA', where 'X' stands for gray, 'A' for green, and 'B' for yellow.
If the result shows there is no such word, enter one '!'.

