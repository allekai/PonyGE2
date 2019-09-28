# Notes regarding the development of a new GE application

## Adding new problems
See also: [Ch. 7.5 from Paper](https://arxiv.org/pdf/1703.08535.pdf)

1) A new grammar file named with a `.bnf` suffix placed in `grammars/`
2) A new fitness function implemented as a class in a file `fitness/NAME.py`. Existing fitness functions may be reused
for supervised learning problems
3) For supervised learning, a new dataset split into `datasets/NAME/Train.csv` and `datasets/NAME/Test.csv`  (txt works
as well)


Here is the [documentation](https://github.com/PonyGE/PonyGE2/wiki) for PonyGE2.