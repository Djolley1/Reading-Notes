# Class 07

Explain why we need domain modeling. 
- domain modeling is a foundational step in software development that fosters collaboration, improves communication, guides design decisions, and ultimately contributes to the creation of robust and effective software systems.

Why should tables not be used for page layouts?
- Layout tables reduce accessibility for visually impaired users
- Tables produce tag soup
- Tables are not automatically responsive

List and describe 3 different semantic HTML elements used in an HTML <table>.
- <thead>, <tbody>, and <tfoot>`

What is a constructor and what are some advantages to using it?
- A constructor is just a function called using the new keyword. When you call a constructor, it will:

- create a new object
- bind this to the new object, so you can refer to this in your constructor code
- run the code in the constructor
- return the new object.

How does the term this differ when used in an object literal versus when used in a constructor?
- in an object literal, this refers to the object itself.
- In a constructor function, this refers to the newly created instance of the object.

Explain prototypes and inheritance via an analogy from your previous work experience.
- The blueprint of a building I maintain represents a class, before we work on a certain part of the building we should model it out to understand the maintenance. Once you've work on that part of the building you apply the same routine maintenance procedures to other parts of the building of the same type. You consistently modify the prototype (blueprint) to include changes as things go along.