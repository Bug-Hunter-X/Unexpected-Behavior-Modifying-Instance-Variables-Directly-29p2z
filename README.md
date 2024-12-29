# Unexpected Behavior When Directly Modifying Instance Variables in Ruby

This repository demonstrates an uncommon bug in Ruby related to directly modifying instance variables using `instance_variable_set`. While functional, this practice can lead to unexpected behavior and make code harder to maintain and debug.

The `bug.rb` file shows how directly modifying instance variables can bypass method accessors and potentially lead to inconsistencies if other parts of the code rely on the accessor methods.

The solution in `bugSolution.rb` showcases a better approach: using accessor methods to modify instance variables for better code organization and maintainability.  This ensures that all modifications are handled consistently and in a controlled manner.