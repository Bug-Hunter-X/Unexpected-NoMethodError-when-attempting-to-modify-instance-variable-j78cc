# Ruby - NoMethodError when modifying instance variable
This example demonstrates a common error in Ruby where trying to modify instance variables without defining a setter method leads to a `NoMethodError`.  The `bug.rb` file showcases the issue, while `bugSolution.rb` provides a solution.

**Problem:** Instance variables in Ruby, by default, only have a getter method implicitly defined. If you try to assign a new value to them directly, it causes a `NoMethodError`.

**Solution:** Explicitly define a setter method (using the `attr_writer`, `attr_accessor`, or by defining a method) to allow modification of the instance variable.