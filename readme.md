# Notes and Exercises from Fundamentals of Numerical Computation

Important note: I do not have access to the solutions, and have not carefully checked my solutions. 

Useful things to know:

* jnb files are great for publishing and git, but there does not seem to be a way to work with these interactively.  SO use Weave.convert_doc(infile,outfile) to convert them to notebooks for interactive work.

* FundamentalsNumericalComputation contains all the code from the book, and also many libraries are exported from it. However, even though those libraries are installed, they are not in the root environment and so you cant use them seperately without 'adding' them again. I am still trying to understand how the package system works, and at the moment i find it confusing.