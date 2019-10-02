@ Conditionals

- One useful way to think about JavaScript is to think of all of the code we're writing as happening inside of a function.

- Conditionals can be thought of in English sentences to discover their variables, i.e.
  - If it is X, then I will Y
  - If it is raining, then I will cry
  - If it is sunny, then I will dance
  - If X = 2, then increment X by 1
    - Else decrement X by 1
    
Q. _Where does complex logic filter in? Not everything in the world can be filtered into a set of binary options; variables may not be known, or are still being discovered._ 

A. 

Q. What is a situation where you would declare a variable first, but not know its actual value until later?
```
var declared;

if (declared === undefined) {
  console.log('declared is undefined');
}
```
Wouldn't it make more sense to wait until you know what declared is so you don't need the conditional? It's hard to think about what declared might be in a program. Or is this just the power of programming? That you don't need to wait to find out the value in order to still have control over it?

A.

Q. What is a truthy/falsey value?
A. A value that will be forced into being true or false when evaluated by rules of JavaScript.

# Pseudocode
- Generating pseudocode prior to writing actual code is easier than starting with actual code.

Q. How to I use indexOf to find a value algorithmically if I don't know what value in an index I need?

A. Perhaps if I've declared the variable already I can sort the index to give it the value it closest to the one I want it to have

Q. If/Else statements -- when to use which?
A. It's a Venn Diagram, sometimes you use one or the other, sometimes you can use both.
