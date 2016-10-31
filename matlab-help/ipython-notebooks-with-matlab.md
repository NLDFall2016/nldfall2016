# Using MATLAB in a Jupyter Notebook

> Or, how to avoid MATLAB's IDE/CLI altogether and create a document
> that is easier to both read and write.

If you're not familiar with Jupyter/IPython notebooks, they're a 
  nice way to write code interspersed with text, where the code
  can actually run from the document itself. It's kind of like 
  RStudio's R Markdown format, but it has extensions to a bunch 
  of languages, including MATLAB.
  
## Installation

You will need Python 3.4+, specifically with Jupyter. The easiest 
  way to go about this is to [download Anaconda](https://www.continuum.io/downloads).

Then, you need the MATLAB kernel for Jupyter. ([source](https://github.com/Calysto/matlab_kernel))
  In a terminal:

```sh
pip install matlab_kernel
python -m matlab_kernel install
```

(If you get an access error on the first command, try `pip install --user matlab_kernel`)

## The Notebook

From a terminal (`cmd.exe` on Windows, Terminal on Mac or Linux, 
  Ctrl+Alt+T on Ubuntu-based systems), run `jupyter notebook`. This
  will start up a browser with Jupyter running. 
  
Go to `New` -> `MATLAB`. This will open a notebook. 

In the toolbar, you can switch between writing MATLAB code and text
  by clicking the dropdown menu that says "code" (which assumes MATLAB),
  and selecting "Markdown" (see [this cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  if you're unfamiliar with markdown—don't worry, it's designed to be
  basically plain text). Each cell is one type of writing, but you can
  add a new cell (`Insert` -> `Insert Cell Below`) to start a section of code 
  when you were writing in Markdown, for example.
  
To run a chunk of code (or render your Markdown), hit `Ctrl+Enter`. 

Remember to save (`File` -> `Save and checkpoint`), and you can download
  it as a PDF or a bunch of different formats when you're done.

  
