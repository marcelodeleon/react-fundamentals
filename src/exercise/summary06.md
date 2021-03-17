# Forms

We saw how to reference form inputs in several ways:
 - Using an id field
 - Using a `ref`
 - Using Controlled Inputs
 
## Validating inputs
Using the `onChange` event we can control the user input and notify errors as
necessary. We implemented this using an `error` state, that was populated
whenever the check in the `onChange` method failed.
 
## Controlled Inputs

This was the most interesting way to use inputs (in case you need to
change/control the value in anyway before setting it). To achieve this
we use the `value` prop and the `onChange` event. Both will be interacting with
state, we used React Hooks for this.
