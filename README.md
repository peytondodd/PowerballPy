# Powerball number generator 

Pseudo-random number generator for 'Powerball' in Python 2 & 3.

## Usage 

~~Update: `pwrball.py` is the latest iteration of this script.~~

Program can be run directly from a shell with: 
`python powerball_2.0.py` or `python3 powerball_2.0.py`

Program generates the following set:

* 5 pseudo-random numbers between 1 and 69, inclusive (with no duplicates), and
* 1 pseudo-random number between 1 and 26, inclsuive. 

to a `PrettyTable` 

User designates the number of sets they'd like to create.

## Todo: 
- [x] Format output to a nice table.
- [x] Refactor: separation of concerns. 
- [ ] Argument parsing so you can run this directly w/out invoking script 
- [ ] Add unit tests.
- [ ] Integrate with travis-ci & landscape.io 

## History 

First commit Apr. 21, 2016 @20:23 ET. 

Unified programs for Python 2 & 3 Aug. 4, 2016.  

## License 

[MIT License](https://opensource.org/licenses/MIT). 'Nuff said.  
