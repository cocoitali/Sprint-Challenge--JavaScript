
1. The bigggest difference between .forEach and .map is that .map returns and array and .forEach does not.

2. A function and a method are both methods of objects. Though they are both functions, for purposes of telling them apart, a method is non-global and a regular old function is global.

3. A closure is a function thats enclosed within another function. The function that's enclosed has access to the outer function's scope as well.

4. You can find out what is calling when the function is called by lookingg for the following information:
     window: if the function is called in the global scope
     explicit: .call(), .apply(), .bind()
     implicit: if there is something left of the dot when the function is called (the function is called as a method)
     new: if you see the keyword: new

5. super() is used to access and call functions on the parent, passing this info down to the child.
