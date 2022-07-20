# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* the event handler runs
* dispatch with the result of our addOne() action runs
* dispatch uses the reducer with the addOne action and initialState
* reducer executes a switch statement to setState accordingly, in this case it adds one to the current total.
...

* TotalDisplay shows the total plus 1.
