# Global Execution Context (GEC)

Whenever the JavaScript engine receives a script file, it first creates a default Execution Context known as the Global Execution Context (GEC). 

The GEC is the base/default Execution Context where all JavaScript code that is not inside of a function gets executed. 

For every JavaScript file, there can only be one GEC. 

# Function Execution Context (FEC) 

Whenever a function is called, the JavaScript engine creates a different type of Execution Context known as a Function Execution Context (FEC) within the GEC to evaluate and execute the code within that function. 

Since every function call gets its own FEC, there can be more than one FEC in the run-time of a script. 

 

# How are Execution Contexts Created? 

Now that we are aware of what Execution Contexts are, and the different types available, let's look at how the are created. 

The creation of an Execution Context (GEC or FEC) happens in two phases: 

Creation Phase 

Execution Phase 

 

# Difference between undefined and not defined 

undefined 
It works like when we declared a variable in the code but did not assign the value before printing the variable value 

not defined 
It works like when we did not declare the variable and try to call that variable. 

  

 

 
