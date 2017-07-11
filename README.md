$Website-Optimization-Project
========

$Website-Optimization-Project involved optimizing a provided website with a number of optimization and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.
    

Running the Application
------------

Begin $Website-Optimization-Project by opening:

	https://gabbygeo.github.io/OptimizationProject/  


Optimization and Performance Enhancement Steps Taken
--------

For index.html:  
- CSS style was minified and inlined in index.html
- Images were saved locally and size was optimized
- Google font script was moved to index.html
- Eliminated render-blocking Perfmatters.js 
- Made google-analystics asynchronous 

For Views/js/main.js and views/pizza.html:
- Eliminated the determineDX function
- Simplified changePizzaSizes function
- Moved var Items outside of updatePosition function and selected by class name, not by query all
- Reduced number of moving pizzas to 50
- Optimized size of pizza images
- CSS style was minified and inlined in pizza.html
- Changed querySelectorAll to getElementById or getElementsByClassName for improved performance
- Moved pizzasDiv variable outside the for loop
- Created local var top outside the loop
- Moved var elem outside the for loop
- Created movingPizzas var outside the loop

Contribute
----------

- Source Code: https://gabbygeo.github.io/OptimizationProject/

Support
-------

If you are having issues, please let us know.
Email: gabriellejf@gmail.com 

License
-------

The project is not licensed.
