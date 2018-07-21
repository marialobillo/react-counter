## Exercises

> Why does React only allow information to be passed down in the hierarchy? What are the advantages and disadvantages of this approach? Discuss this topic with your mentor.

A: React uses one-way data binding, so the info is moving from parent to child. That makes that is easy to find the source of data, no messy routes. But if you want to share the state you can lift it up to their closest common ancestor. That method needs more code that two-way data binding but it's easier find any bugs.
