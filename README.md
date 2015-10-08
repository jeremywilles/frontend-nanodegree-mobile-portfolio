
page speed insights steps for score greater than 90

1. async google analytics script
2. store pictures instead of linking to them
3. inlined css
4. replace img and js with optimized contents



pizza.html -> main.js


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

