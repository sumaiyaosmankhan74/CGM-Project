# CGM-Project
Instructor :  Masum Ahmed EeSha

This  program starts from the main function…

At first we will set our windows length & width by calling glutinitwindowsize() function.
For setting the windows position,  windows position function will be called.
By triggering createwindow it will create a new window to display our animations.then init function will initialise our program.if init function start to work in cmd  we can see the text init.Following by these reshape function will alsop triggered to sets the reshape callback for the current window.

This program is a story based project so it is handled by several keypresses.By pressing number keys we will move our display to next pages.So for the handling of keypresses we made a function called handlekeypress.In this function we will do several tasks in a continuous manner.we organize our display in 7 keys. Number keys from 1-7 sequentially handle our display one by one.so the display will appear in 7 condition.we will handle this 7 condition by using multiple switches.

In case of keypress 1 we will destroy our initial window 1 and create a new window and set sizes for this window and it will call display1 functions. Like this there are 8 more functions which are recognized as display2,display3,display4,display5,display6 etc.
A particular function will generate a particular pictures.By the combinations of those moving scenes it will create a story to show.

In display1 function multiple functions are called.Each functions are called for each element to display.

Full sky() function generates a blue sky interface.
grass() function is for display green grass in the scene.
background() function will handle the scene background.
There are multiple sky functions to display the moving crow.we will call one by one and organize the whole scenario.

After completing the display 1 functions we will press key 2 and it will push us to display 2 functions.By these method we will call every functions till 8th.
Every new function will generate our next scene & create a new window.each windows will have a voiceover for telling the story.when each key will be pressed and function will be called the voiceover will play automatically.For changing the colour matrix of each scenes we will call glut transferred functions.

Multiple logics & implementation is used for creating each instance like tree,crow,bird,sun,moving stone,sky.
Mmmmmmmmmmm…thats all about my project..Thank you 

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


