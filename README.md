<div align="center">

## Debugging Client Side Javascript Using Visual interdev


</div>

### Description

Debugging Client Side Javascript with Visual Interdev, allows you to step through your code one line at a time and test the variable values.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Roger D Taylor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/roger-d-taylor.md)
**Level**          |Beginner
**User Rating**    |4.1 (37 globes from 9 users)
**Compatibility**  |
**Category**       |[Debugging and Error Handling](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/debugging-and-error-handling__2-63.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/roger-d-taylor-debugging-client-side-javascript-using-visual-interdev__2-1872/archive/master.zip)





### Source Code

```
I know that not everyone uses MS Visual Interdev but you really should get a copy. I think that for general ground up developent of js code there is nothing better.
Ok, This is pretty simple really. First of all,
Load a HTML document into Interdev (one that have some javascript in it !!) now, you should notice that running down the left side of the edit window is a thin grey band. Select a line in your javascript and click this line, you should see a small red dot appear in it, Those of you familiar with VB will know this very well. You have just inserted a breakpoint in the code... now go to the Debug Menu Item and Select the processes menu item. once this menu item has opened you should see at least one entry with the title 'Active Desktop'. Now close the window, and run your script in the browser. Go back to interdev and open the processes menu item once more... notice that your a new item has been added to the window, Select this new item and click the 'Attach' button. Notice that the new item has been added to the bottom window. Select the new item from the bottom window and click the break button. Go to your browser window and refresh the page, once do what ever you need to do to get the Javascript running you should see that you are thrown back to Interdev where you can step thought the code simply by pressing F11.
Hovering your mouse over the variabes will show you there value.
There you go, thats all there is to it.
```

