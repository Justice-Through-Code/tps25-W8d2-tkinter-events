# tps25-W8d2-tkinter-events

Breakout #1 – Respond to Key Event
Goal:
 Help understand how event binding allows widgets to respond to specific key presses, such as the <Return> key (Enter). This solidifies the concept of event-driven programming and encourages thinking about user interaction patterns.

Instructions:
Fellows should implement the following:
    Create a window with an Entry widget where users can type in a message.
    
    Create a Label widget below it that will display a response.

Use .bind("<Return>", ...) to connect pressing Enter to a function that:
    Retrieves the text from the Entry field

    Displays it in the Label

    (Bonus) Clears the Entry field afterward

Additional Challenges (Time permitting):
    Add a character counter next to the Entry box that updates live with each keypress.

    Add error handling if the input is empty.

    Add another binding for <Escape> to close the application or clear the label.


---------------------------------------------------------------------------------------

Breakout #2 – Interactive Label Color
Goal:
 Give fellows hands-on experience with mouse event handling in Tkinter. This reinforces how GUIs respond not only to keyboard inputs but also to mouse actions like hovering and clicking.

Instructions:
Fellows should:
    Create a Label widget with text (e.g., “Hover over me!”).

    Use .bind("<Enter>", ...) to change the text color when the mouse pointer enters the label area.

    Use .bind("<Leave>", ...) to reset the text color when the pointer leaves the label.

    (Bonus) Add .bind("<Button-1>", ...) to change the background color when the user clicks on the label.


Additional Challenges (Time permitting):
    - Toggle between two background colors on each click.

    - Display the current mouse coordinates using event.x and event.y.

    - Change font size dynamically on hover.

    - Add sound or animation (if advanced enough).