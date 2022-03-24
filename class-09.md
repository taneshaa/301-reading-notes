# Concepts of Functional Programming in Javascript<br>
## https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa <br>


What is functional programming? Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data <br>

What is a pure function and how do we know if something is a pure function?<br>
It returns the same result if given the same arguments (it is also referred as deterministic)<br>
It does not cause any observable side effects. An impure function would receive radius as the parameter, and then calculate radius * radius * PI:<br>


What are the benefits of a pure function? It makes the code easier to test<br>
What is immutability?Unchangebale over time. State can’t be changed after its creation.<br>
What is Referential transparency?When a function is pure and has immutable data.<br>


# Videohttps://www.youtube.com/watch?v=xHLd36QoS4k <br>
What is a module? Independant set of code thats part of a bigger code base <br>
What does the word ‘require’ do? Can allow something to be called on a global state<br>
How do we bring another module into the file the we are working in? let var = require('filename')<br>
What do we have to do to make a module available? modeule.exports = function<br>
