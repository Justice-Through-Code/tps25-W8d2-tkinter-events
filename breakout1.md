# W8D2 - Tkinter Events - Breakout 1

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
