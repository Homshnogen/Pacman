### Vax-man in Python with PyGame

This is a modification of Pacman with the following rules:

* Vax-Man can kill a ghost if he comes into contact with it (vaccinates it).
* Contact with a ghost does not kill Vax-Man.
* Each ghost that has not yet been hit multiplies itself every 30 seconds (the infection grows).
* The goal of the game is to collect all the dots before the number of ghosts grows to 32 times the original number.

Original code for this project: https://github.com/hbokmann/Pacman

## Notes

I think 30 seconds is much too long between multiplications.

I also think 32 times the initial number (4 in original pacman) is way too many.

Currently, the ghosts have pre-determined paths, and I would like to change this.