# julia-book-project
Trying to write a book about Julia

## About me

### Qualitfication

I have been a Data Scientist since 2007. I have used R, Python, and Julia. I have a good understanding of how programming languages are used in the industry.

### Unique characteristics or experiences?

I am a Data Scientist with signficant work experiences. I also worked at a start-up.

## Topic?

Julia
Julia is quickly being recognized as one of the big 3 in data science. However the number of books teaching Julia pales in comparison in number to those teaching R and Python.
This book is important now as Julia is experience rapid growth and the demand for high quality Julia teaching material will only increase. Also, Julia solves a very important problem in Python and R, i.e. the code are written in Python and R because they are easier to use; however native Python or R code are simply not fast enough for many purposes, so critical parts needs to be written in a fast language like C or Fortran.

### How is different?

Many people learn best by example. In this book, we will show how to implement Julia using example code.

In the book we will introduce interesting programming puzzles and show how the user can use Julia to solve them. This will make the book engaging and will attract a certain crowd interested in Julia as an intellectual challenge.

## Book Plan

The reader can confidently

* structure a julia program
* knows the pros and cons of julia
* knows how to structure a julia program for efficiency
* understand types in Julia
* organize Julia code
* write efficient code with julia

### Teach or Reference?

It's definitely intended to teach. Google for stuff is relatively easy and hence it's difficult to write a reference that doesn't get dated.

### Is it In Action, In Practice, Mth of lunchs or Grokking?
No. It's a Learn Julia by a journey through coding/math puzzles. 

### Distintive?

Learn Julia via a series of problems

## Q&A

### What is Julia? 

Julia is a programming language that looks like Python and runs like C. It solves the two-langauge problem.

### What is Julia for?

Julia started life as a numerical programming language so it has strong alignments to the data science community. However, Julia is perfectly capable as a general purpose programming language.

### Why Julia?

Moore's law has ended. Programs are not going to run faster every 18 months just because. The shift towards efficiency is gathering pace and the demand will overwhelm Python and R in the coming decade. The amount of data that needs to be dealt with is getting bigger. A more efficient programming language is called for. 


## Readers?

The reader are expected to have some idea of how to programming. Profiency in high school level math is also required. No hands-on software development experience is needed. They will be taught.

The primary reader is expected to be a student

## Comeptition

Julia's website contains a list of books 

I would recommend Think Julia

## Book size

The book should be about 100 pages.

There shouldn't be graphics of any sort

About 30% should be code listings

## Contact

Name: ZJ
Twitter: @evalparse

## Schedule

## Table of Contents

Chapter 1 - Julia Basics (est 50 pages)
* statement
* if
* loop
* list comprehension
* Dict, tuples, and named tuples
* Recursion - Akerman's function
* Gotchas - overflowing UInt32

Chapter 2 - Functions & Types
* Why is Function important?
* Type-stability
* Multiple dispatching
* Gotcha

Chapter 3 - Advanced Functions & Types
* Efficiency - function barrier, speed decorators `@pure`
* Type hierachy
* Type parametrisation
* Odd types `Val` and `function` types
* FizzBuzz with a twist; using `Val{}` to solve it

Chapter 4 - Practical Julia
* Installing and Updating packages
* Setting up Projects
* `]dev` packages
* IDE choice - Juno, VSCode, Jupyter via IJulia
* Benchmarking
* Testing
* Documenting
* Persisting data
* Debugging
* Reading from File IO

Chapter 5 - Data Wrangling
* Tables.jl
* DataFrames.jl
* CSV.jl, FilesIO.jl
* JDF.jl

Chapter 6 - Interesting Topics in Machine Learnings
* Linear Regression/matrix multiplication
* GLM
* Simpson's paradox
* The Chase solutions
* MLJ framework
* JLBoost for tree-boosting
* Flux MNIST solution
* Parallel Kmeans

