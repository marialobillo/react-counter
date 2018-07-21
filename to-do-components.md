## Exercises

> In your own words, explain what happens behind the scenes when you use JSX.

A: The JSX code is compiled, this code

```
 <div>Hello {this.props.toWhat}</div>

```

is compiled is something like this:

```
 React.createElement(
   'div',
   null,
   `Hello ${this.props.toWhat}`
 )

```

If we don't use JSX we need to use a much longer code because we need to call a createElement method from React, and pass all the arguments. That method is tedious so using JSX is not plain Javascript but it's much easier.
