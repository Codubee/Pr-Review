# Code review / Pull request review

## Purpose
A code review or pull request review is a process where someone other than the author of a piece of code reviews code. It is done when a developer creates a pull request and requests a review of the code.


Reviewing code helps developers find any bugs or errors before any code is merged.


## How to perform
When reviewing code there are a series of questions you 
want to ask yourself. Questions can include:
- Does the code written follow a good design?
- Is the code written functionally correct?
- Is the code written too complex? Can it be simplified?
- Does the code have any test cases written?
- Do the methods and variables have good names?
- Are the comments that are written good? Do they make sense? 
- Does the code follow our teams [styleguide](https://google.github.io/styleguide/)
    
    
    
## Example 

```javscript
// This method adds 2 to the input and returns it
function addingTwo(input){
    return input + 3;
}   
```

Lets do a code review for the code written above.

- ### Does the code written follow a good design? If we look at the code, there doesnt seem to be much of a design. 
    - It is a method, has a method name, and an input. Looks good so no comments here.

- ### Is the code written functionally correct?
    - Looking at the code it looks like they wanted to create a function that added two, but this adds three so the code is incorrect. We would then write a comment letting the person know to fix this.

- ### Is the code written too complex? Can it be simplified?
    - This code looks very neat and easy to follow. So no comments are given here.

- ### Does the code have any test cases written? 
    - It does not look like any test cases are written with this code. We would write a comment to this user letting them know that they have to write test cases with their code.

- ### Do the methods and variables have good names? 
    - Looking at the code, the method name is clear but the input variable is not very clear. What happens if we have more than one input into this function. We could leave a comment asking the developer to come up with a better input variable name.

- ### Are the comments that are written good? Do they make sense? 
    - The comments look to be descriptive and put in a good place.


- ### Does the code follow our teams [styleguide](https://google.github.io/styleguide/)? 
    - Since there is not styleguide to refer to, we cannot tell if they have violated a style guide, therefore no comment about following a styleguide is left.