
Steps to use this:

1. Launch index.html -> this will bring you to the home page
2. Click on any link
3. First three links take you to static informational pages
4. Fourth link, Cam's Pizzeria takes to you a site with interactive content
5. Scrolling up or down will result in the pizzas in the background moving!
6. Right below the 'Our Pizzas!' is a slider. You can use the slider to change the size 
   of the pizza. Three options are available: small, medium and large

*******************Optimization Steps************************************

page speed insights steps for score greater than 90

1. async google analytics script

2. store pictures instead of linking to them

3. inlined css

4. replace img and js with optimized contents



pizza.html -> main.js

<5ms pizza updates


1. Remove switch statement in determineDx function replaced with array

2. changePizzaSize - retrieved randomPizzaContainer with getElementByClassName

3. removed for loop, determined newWidth once, then set that property on all randomPizzaContainers

*Result of the above, pizza resize time below 5 ms 

60 fps

1. In updatePositions() function, replaced querySelectorall with getElementsByClassName

2. stored the 5 iterations of phase into an array, computed in a separate for loop

3. replaced items[i].style.left with items.style.transform

4. added transform parameters into the .mover CSS

5. for the sliding pizzas, made only 5 columns and 20 pizzas, not 200

