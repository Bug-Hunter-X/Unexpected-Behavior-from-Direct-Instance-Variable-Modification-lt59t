# Ruby Bug: Direct Instance Variable Manipulation

This repository demonstrates a common issue in Ruby where directly manipulating instance variables using `instance_variable_set` or `instance_variable_get` can lead to unexpected behavior and violate encapsulation principles.  This is especially problematic in larger projects with multiple developers.

The `bug.rb` file shows the flawed code, while `bugSolution.rb` presents a better approach.