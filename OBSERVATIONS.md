# Pass by value/reference

   After I run "PassByDemo.java" I note that 'num' is still 50, but 'box.value' changed to 100.
  That means when I pass primitive types to a function, it is being passed by value,
  but when I pass objects, it is being passed by reference.

# Static behavior
# How does count change when new objects are created?
  When creating a new object from the 'Counter' class, the constructor added 1 to the last value of 'count' 
  (but because it is a static variable, it is general to the class).
# Can you access it via the object and class? Any difference?
  yes , no difference .. but it's best practice to access it from the class name.

# Constants
# What happens if you uncomment the assignment line?
  compile error , because it is constant variable it can not be changed after it has been initialized.
# Why is it static? 
  to make it common between objects and belong to a class, not a specific object.
  
  
  
