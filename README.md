# README

[DISCLAIMER	2](#disclaimer)

[Introduction	3](#introduction)

[Terminology	3](#terminology)

[Modes	3](#modes)

[Options	3](#options)

[Utilities	3](#utilities)

[Tools	3](#tools)

[Canvas	3](#canvas)

[How to Use	4](#how-to-use)

[Mode Glossary	5](#mode-glossary)

[Options	5](#options-1)

[Utilities	6](#utilities-1)

[Tools	6](#tools-1)

[Important References	7](#important-references)

# DISCLAIMER {#disclaimer}

As this is Speech Recognition software, we cannot guarantee the accuracy of what is spoken. Speech recognition may produce offensive or harmful results that are inaccurate and not in line with our beliefs or views. Please keep this in mind when using this software. We recommend a quiet environment for this to work effectively because it is sensitive.  
	

# Introduction {#introduction}

Robot Ross is one of the world’s first fully automated\* speech-to-art software. It allows the user to draw art using a canvas with speech recognition alone\*. 

*\*  The user still needs to press buttons to work the web application. Everything else is 100% fully automated via voice.* 

## Terminology {#terminology}

Before we go and teach you how to use the software, there are a few things you need to know. 

### Modes {#modes}

Modes are the things you design with, such as tools and utilities.

### Options {#options}

Options can be used throughout the programme to do everything related to art. They are not **tools**, which are explained later. Some examples of these options are to change the position of the tool placement or the colour of the tool being used. 

Options can only be entered with speech. Some are not essential but are crucial to creating beautiful artwork. 

### Utilities {#utilities}

Utilities are speech-recognised actions that can be performed to finish a task. Utilities are not **tools**, but they work hand-in-hand with tools to finish an art piece. Some examples of these utilities are to finish the stroke of a line or to close a shape. They are essentially an extension of tools.

Utilities can only be accessed with speech.

### Tools {#tools}

Tools are the bread and butter of the art piece. Essentially, they are the objects that you place onto the canvas. You can only make an art piece by using tools. Some examples of these tools are doing lines, circles, rectangles and text. 

### Canvas {#canvas}

The canvas is what you place objects on.

## How to Use {#how-to-use}

Select the “utility” drop-down option and press the record button next to the drop-down menu to use a utility. Then, speak into the microphone about the utility you want (a list of utilities is below). The program will facilitate that utility's action.

To use a tool, press the “tool” drop-down option and then the record button next to the drop-down menu. Then, speak into the microphone what tool you want (the list of tools is below). The program will facilitate that tool's action at the position the user entered (in the options). Some actions require another tool or utility to be previously spoken.

Press the record button next to your desired option to use an option. There are two options: number options, which require you to speak a number, and string options, which require you to speak alphanumeric text. (The list of options is below.)

When you speak an option, numeric or alphanumeric (x and y positions and canvas width and height), the application will display these so you don’t have to remember what you said. 

Remember that you can always return to this document by clicking the “Help” link or speaking “Help” as a utility.

***Note: The program only accepts one-word commands and only one word at a time (ie. colour names that are more than one word will not work)\!***

# 

# 

# 

# Mode Glossary {#mode-glossary}

These are the lists of options, utilities and tools that are available. 

## Options {#options-1}

This is the list of options available, ordered alphabetically.

| Name | Description | Option type | Example |
| :---- | :---- | :---- | :---- |
| Colour (fill) | Fills all future shapes with the chosen colour | String  | Red |
| Colour (line) | Draws all future lines with the chosen colour | String | Blue |
| Canvas height | Makes the canvas the chosen height (in px) | Number | 354 |
| Canvas width | Makes the canvas the chosen width (in px) | Number | 832  |
| X position 1 | The canvas will move to that x position when selected by a tool. Also used for calculating the width of a rectangle. | Number | 239 |
| X position 2 | Used for calculating the width of a rectangle and also the endpoint of a line. | Number | 352 |
| Y position 1 | The canvas will move to that y position when selected by a tool. It is also used for calculating the height of a rectangle. | Number | 123 |
| Y position 2 | Used for calculating a rectangle's height and a line's end point. | Number | 321 |

 

## Utilities {#utilities-1}

This is a list of the utilities available, ordered alphabetically.

| Name | Description | Requires |
| :---- | :---- | :---- |
| Clear | Clears the entire canvas (work in progress) | N/A |
| Help | Brings up this help manual | N/A |
| Reset | Resets all the values and drawing back to the previously saved state | N/A |
| Save | Saves the canvas (work in progress) | A drawing to be made |

## Tools {#tools-1}

This is the list of tools available, ordered alphabetically.

| Name | Description | Requires | Optional | Example |
| :---- | :---- | :---- | :---- | :---- |
| Circle | Draws a circle using two points (work in progress) | X position 1, X position 2, Y position 1, Y position 2 | Colour (Fill) Colour (Line) | ![][image1] |
| Curve | Draws an arc using two points (work in progress) | X position 1, X position 2, Y position 1, Y position 2 | Colour (Line) | ![][image2] |
| Line | Draws a line from point 1 to point 2 | X position 1, X position 2, Y position 1, Y position 2 | Colour (Line) | ![][image3] |
| Quad | Draws a rectangle, where the first position is the top left position and the second position is the bottom right position, vice versa if the second position is smaller than the first position | X position 1, X position 2, Y position 1, Y position 2 | Colour (Fill) | ![][image4] |

# Important References {#important-references}

Here are the valid colour names: 

[Valid Colour Names](https://www.w3schools.com/colors/colors_names.asp) \*

\*Only one word colours are supported by this program

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGIAAABcCAYAAACV1WDTAAAE8UlEQVR4Xu2dvS88XxSHRXQURKUjW21H4S9QUSroNJJNNEK1GlnR0IlErdRpbPwDGo1GohGlhmhE4939/j7zy8i4d+7bzJn38yQ3ODs7O/c8dmfuzJm7A+I/BgYGuBXdZBHf39/i6+sraJ+fn+Lj40O8v7+Lt7e33/b6+qpt0eXwPDwf6wnXifX//PzgZZ3p9/tibW1NtNttMTIyIubn50Wn0xHdblf0er3gJ/5GvNVqBctheTyvKsSKCFsoI2yhFFsLkx+2UEDYbOzv74vR0VGxsrIiLi4u5Ie9eH5+DtaD9e3t7ckPlwZFBP5b0aIyoi2aYF2TnxOuK1x3HAcHB8F/+/HxsfwQKff398Hr4PXKhCIiiiwlSdMlH++cmZmZwhPy9PQUbAe2p0iMImTCpLo0E0NDQ+L29lYOFwq2p8jt8hKRls3NTbG9vS2HSwX2KdjOvMlFxPT0tByqBNjuu7s7OZwJmYq4vr4ODimrzM3NjZibm5PD5GQmYnFxMehEXUB/siQTERMTE3KoFmTZL1IR5+fncqiWYHBIDZkIjFqvrq7kcG2hHqWTiFhfXw8O+5oE+ot+U5FaxMLCghxqFFT9TyWC+u1ZVWZnZ+WQN4lFYMfcpH2CjbQHKolE4LrD0dGRHG40yAfykhRvEWdnZ8GpZEYFeUF+kuAtouwn7YomaX68RODcEWNncHBQDllxFoGzkHU6d5Q1vmdtnUVU9VR2Ufjmy0kEjxeS4ZM3JxEbGxtyiHHAJ29WEah4YJLjmj+rCFQ5MMlB/lzGXUYRRZeY1AWX6xdGEb57fiY5WhEvLy/8sUQI8mlCKyKPyoUmYcunVsTq6urv70x6bPmMFZF1IXBTMeU1VsT4+PifhRgaTHmNFeEzImTcMeVVEcGnurNFl19FBG55YrJDl19FxPDwsLwMQ4guv4qIqldvlx1dfhURactCGDO6/CoimlY6mTe6/CoimOyJu57NIgrg5OREDrGIIoi7pZlFFMDu7q4cYhFFsLOzI4dYRBHwR1NJ4J11Sbi8vJRDLKII4q5fKyJ0Q3CGBl1+FRGmixdMenT5VURMTk7KyzCETE1NyaEARYTuwgVDgy6/igjdpTyGBl1+FRHg9PT0z0IMDaa8xorgmtdsMOU1VoSpEIpJjimvsSJA0vuFmXhs+dSKGBsb+/2dSY8tn1oRXJZPS9xpjShaEcC0c2FoMYrgiU9oWFpakkMKRhEMDVtbW3JIwSrC9fZUJh7X/FlFoAbn4eFBDjMOPD4+xtYwxWEVAXSFs4wZn7w5iQB8BOWHb76cRfA0QX64fiSFOIsAtltUmf85PDyUQ1a8RDBuxNUt2fAWwZMr6sl1ckWwvLwshxiRLi+JRACXGVeaRNp8JBYBfKZKqzOFTkkdQjVJeVWh6n9qEYBqY6oGZb9JRACKt2eVoO4vmQigq+usG2l3zHGQigA4hKvrOAP9SnOIaoJcBMCgJulk5WUF/Uk6WHMhExEhKC+k3KEVQeW/EDCK7ynhslCbr8iMgsGf7t6AsoHtzHuwmpuIkE6nU9p6KWyX6zVmanIXEcJfLP6XwkREwc7QNh0nNXg9vK6tAi8vSiEiBNUiOE7HZzR15QjWh/VipknqdVNQKhE6+v1+cMtTu90OPsMxCxj2Nd1uV/R6veAn/ka81WoFy2F5PK8qVEJEE2ARJYFFlIR/HaKRE7580G4AAAAASUVORK5CYII=>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADsAAAB/CAYAAABR7LrJAAAExklEQVR4XuWdq0s9QRTHr298vxB8gAhiEIOCoIgGg0EQLAaxWYwiGC0Gk8UgCDaDzSYYDQaLYLX4B1gsZsv98T0y/vYeZ3dnd2d3Z85+ivfOuXr5MLPzODO71uqOMDo6Wq/VavWrqyseskaNF5RJZ2cnCedFfn85JS0tLfWmpiZebAXnZAFk29raeHFmnJR9eXmh5tzf389DmXBSFhwdHZHw9PQ0D6XGWVmwsrJCwpubmzyUCqdlwfj4OAmfn5/zUGKclwXd3d0k/PX1xUOJ8EIW2BiSvJEFkG1tbeXFxngl+/7+Ts25p6eHh4zwShacnJyQ8OTkJA/F4p0sWF9fJ2H8TIKXsgA1C2HUtCneygJcuxDGtWyC17IAvbPpkOS9LIAsxuE4RMhiZoXmjJlWFCJkAebOEMZcOgwxsgCrIwhjtaRDlCzA+hfCWA9zxMkCZDggjIxHEJGyADksPiSJlQV8SBItC9CckY+m1ywmDuwwQJh2HHhQIh0dHfXm5uZqyI6MjFRHdnh4mDqqSsgODAxUR7a3t5fG3UrIYuhBJ1UJ2fb29p+9Xx6QCLIZNF/mAYlg2MHwUwlZzJFp6ccDEsF0cWlpqTqyOzs71ZE9Ozurjuzr66t82aenJ5IF4mWPj4+rI7u2tlYd2YmJid/Em3jZrq4umhsD8bJYxw4NDdFr8bJowvPz8/RavCw6p8PDw5/XLCaK7+9vkv38/KT3omWDYywQLTs3N9ew3yNaFjvxwUPaomVVhkIhWhbX69bW1v/3gZg41NLu930gJor9/f2GnhiIlR0bG6vOzjtyxfyorlhZNOHV1dXGsoZ3goBsJU7LbG9v/+mcwN8SAWBfR3dwU6QsemGkYzgiZdGET09PebE82YODA+31CvSlHjM4OEgLAB3iZMOuVyBOFk348vKSFxOiZDc2NkKvVxAe8RCciFEJcR2iZHXz4SBiZC8uLiKbMIiOegTOJ/L1K0eMLESnpqZ4cQMiZNXuejDfpEOErC4Fo0OELEQhHIf3so+Pj9qshA7vZZHxN2nCwHtZ1KrpI1m8lsUCPW4iEcT8kw6CA9O6XFMYXsuiVrHSMcVb2eXl5URNGCT7tEOgB+7r6+PFkXgpe3d3R7X68PDAQ5F4KYvjA2FJtSi8lE3aMSm8k52ZmUncMSnS/VaJRKVK4/BKNmx3zpT0v1kC6JTinjIShTey6qFXz8/PPGSMN7I4IxGVEzbBC9mbm5vIbQ1TvJBFjWZ5Kp/CeVk1NdRtLifFeVnUapI1axROy15fX1Ot4j46Gzgti+vU5kOdnZVVR95vb295KDXOymK2pB6AYwsnZdUO+sfHBw9lwklZrGzUXVY2cU5WPRY0D/L5qxmAqLqdzDZOyaJDMt23SYMzsmqoSfJU26Q4I4saxb2ueeKEbJ6dUpD8vyGGt7c3El1cXOQh65QuixWNrVVNHKXKLiwsUK3GnXKxRamyEDXdNbdBabJYvqXZr8lCKbK4iRe1anLCxSaFy6rTaLOzszyUO4XLYvJgM/uQhEJlcXK0iMlDGIV9897eHoniiVtlUZgsRPNYkCehEFnMkIoeZnTkLquu06z/MsoGucqqxNnu7i4PlUJusvf39ySa9khAHuQmi/EU99m4xD9arNTtxEzLLAAAAABJRU5ErkJggg==>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGoAAABpCAYAAADStbY5AAAC1klEQVR4Xu3cLZPiQBRG4fmHSCwWiUVisUgsEuRYJBYJEovEIth9ZyazbBcUCemv230eM1ttT7HJTdL9cfvr8/NTf5Cxj+Yf0+n0fh2Z+Q0ll8vltlqt7peQif9CNebzubuExB6Gkt1u5y4hoaehzufzbbPZuMtI5Gmoxmg0cpeQwMtQMplM3CVE1iqUDIdDdwkRtQ4lxEqnUyjZ7/fuEiLoHEoWi4W7hMDeCiXr9frrFh5xvB1KNBTzX2EcvUI1GIzD8xJKuG6F5S2U8KokHK+hhEdOYXgPJQzG/gUJJTwf9CtYKOEFpD9BQzUYjPuLEorBuL8ooeR0OvFZWg/RQsn1ev360gndRQ3VYDDuLkkoYTDuJlkoGQwG7hKeSBpKZrOZu4QHkocSBuPXsggl+uadO8Lnsgkl2+3WXcKPrEIJ16zHsgslGoyXy6W7XLUsQzX4df2TdSjhuvUt+1DsgvyWfajGeDx2l6piJpTUfM0yFUpqfT5oLpTU+OTdZCg5HA7uUtHMhhINxRqOa2A6lOg7DH2PUTrzoURfOJV+LkYRoRolD8ZFhZJSX0IWF0pK/O69yFBS2o6SYkNJSYNx0aGklI89iw8lJewvriKU6FwMy6oJJZYH46pCiTbVWfx1VReqYW0XZLWhxNJgXHUosTIYVx9KLMQi1I/cB2NC3cl5MCaUI9cDIwn1QI5DMaGeyO0FJKFeyOW6RagWcrgjJFRLqY8HIlRLqXdBEqqjVM8HCfWGFHeEhHpT7O0/hOoh5i5IQvUUa4MCoTyIcTwQoTzRMQshN9cRyqPj8RjsXAxCBRBiMCZUIL6PWiBUQD5v3wkVmK/BmFAR+PhlESqSvtcsQkXU51wMQkX27gtIQiXwzmBMqES6HhhJqMTavoQkVAbafPBJqEy8GowJZQShjCCUEYQyglBGEMoIQhlBKCMIZQShjCCUEYQyglBGEMoIQhlBKCP+APlUzLp5t2EyAAAAAElFTkSuQmCC>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGoAAABtCAYAAABJJPQvAAABHklEQVR4Xu3UuwkAMQwFQfXf9H2CS84NaGEejAOlC57LEpv/wXZOqMiEimyevQ/7HQd2Og4s4uuLECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECpCqAihIoSKECri2w2C5VKJTGaDYQAAAABJRU5ErkJggg==>