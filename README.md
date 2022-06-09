# Connector
Jasper Wilson <jaspermwilson@gmail.com>

## Description

A project in collaboration with Kumar Abhilasha (abhilasha.kumar@wustl.edu) and the Diverse Intelligences Summer Institute (https://www.diverseintelligencessummer.com/).

This project implements the nodeGame framework to run an online multiplayer experiment. This experiment involves two players, a guesser and a clue-giver. The goal of the clue-giver is to give a single word clue that allows the guesser to select two pre-selected words from a list that both players have access to. The players take turns guessing and giving clues until the guesser guesses correctly or they guess incorrectly three times. The players repeat this process for ten boards, guessing three word pairs for each board (with one additional board for practice). Afterwards they fill out a demographics survey. 

At each stage of the experiment the participants list the options that they considered in chronological order. This allows us to compare the times they spent searching for words to help model the search space.

See Kumar_Connector.pdf to access the paper that motivated this study. For the full motivation and results of this experiment please read the final research paper posted at https://psyarxiv.com/axw8v/. It is currently still in review for publication.

To use this game follow the steps at https://github.com/nodeGame/nodegame/wiki/Getting-Started-v6 and create a new game, replacing its files with this project. 


## License

[MIT](LICENSE)
