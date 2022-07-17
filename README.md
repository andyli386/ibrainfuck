# Brainfuck Kernel for IPython

IBrainfuck is brainfuck language kernel for [Jupyter.](https://jupyter.org/) It
allows users to use Jupyter Notebook frontend, except where Jupyter executes
python code, IBrainfuck can execute brainfuck code.

This is on top of all of Jupyter's other frontend features like Markdown
rendering, HTML rendering, saving notebooks for later use and even the ability
to view IBrainfuck Notebooks in [Jupyter.](https://jupyter.org/)


## Requirements:

* Python 3.10 in your ``$PATH``
* virtual environment is created

## Installing for the first time

```bash
$ make bf-deps
```
Once Jupyter starts up. In the top right corner:
`Select New -> Brainfuck`

## Running every other time
```bash
$ jupyter notebook
```
Once Jupyter starts up. In the top right corner:
`Select New -> Brainfuck`

### Thanks to:
Thanks to **Joel Buchheim-Moore** for his brainfuck interpreter - [Which I found on github](https://github.com/joelbm24/brainy/blob/master/lib/bfinter.py)

