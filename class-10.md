# Understanding the JavaScript Call Stack<br>
What is a ‘call’? the invocation of a function is to “call” the function <br>
How many ‘calls’ can happen at once?One<br>
What does LIFO mean?LIFO stands for Last in First out, temporarily store and manage function calls. The last function to be added to the stack will be the first one returned <br>
Draw an example of a call stack and the functions that would need to be invoked to generate that call stack. <function1() {<br>
console.log(call stack)<br>
}<br>

function2() {<br>
function1()<br>
}<br>

function3() {<br>
function2()<br>
} <br>
What causes a Stack Overflow?recursive function (a function that calls itself) without an exit point.<br>
JavaScript error messages<br>
What is a ‘refrence error’?when you try to use a variable that hasn’t been declared yet<br>
What is a ‘syntax error’?When something cannot be parsed syntactically.<br>
What is a ‘range error’?Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up<br>
What is a ‘type error’?When trying to use or access data that has an incompatible data type.<br>
What is a breakpoint? Used for debugging, will make your code run as long as a condition is met in breakpoint<br>
What does the word ‘debugger’ do in your code?tests your code and shows return in the "local" tab<br>
