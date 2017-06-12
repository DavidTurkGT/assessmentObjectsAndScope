## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.


### Provide examples for all three, below:

#### Scope:
Scope is the area in which a function has access to variables.  Things in the global scope are available to all functions and blocks of code.  If a variable is assigned within a function or block or code only that function or block and any contained function or block has access to it.  In short, with scope you can go down but not up
#### Hoisting:
Hoisting is one of Javascript's fun features.  It is how the interpreter reads your code.  All variable declarations are moved to the top of their respective code blocks.  Then all functions are moved below variable declarations.  Then everything else in the order its written.  Therefore, Javascript doesn't always read your code from top to bottom as you wrote it.

#### Compartmentalization:
Compartmentalization is how you break your code into blocks that serve specific purposes and protect the data that they have within them.  This is done primarily with functions.
