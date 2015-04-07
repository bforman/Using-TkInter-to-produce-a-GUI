# Using-TkInter-to-produce-a-GUI
This repository discusses TkInter (Tk Interface), a module from the standard Python library, and how it can be used to produced a GUI.

#Problem
We want to create a visual GUI for a infinite player and we know that TkInter is the standard Python GUI module, but we do not know much about the module or its capabilities yet. Thus we need to learn about TkInter and how it is used in order to utilize it and begin producing our visual for the player.

#Questions
1. What kind of packages does TkInter have for displaying text, message prompts, dialogue boxes, etc.?
2. Does TkInter have packages that provide a variety of differently shaped objects to put on the GUI?
3. How does TkInter split up the GUI? Are there different layers or panels?

#Resources
1. [TkInter Python Docs](https://docs.python.org/2/library/tkinter.html)
2. [Displaying Text](http://effbot.org/tkinterbook/text.htm)
3. [Displaying Message and Dialogue Boxes](http://effbot.org/tkinterbook/tkinter-standard-dialogs.htm)
4. [Widget Classes](http://effbot.org/tkinterbook/tkinter-classes.htm)

###Mini Abstract of Relevance for [TkInter Python Docs]
This resource serves as a handy reference that answers parts of all three questions above. This documentation provided by Python includes information about: modules included and supported by TkInter, setting options (for buttons, panels, etc.), data types used in Tk, how to use widgets and couple widgets together, how to work with images, and more.

###Mini Abstract of Relevance for [Displaying Text]
This link goes into detail on how to use the Text widget in order to display text on a GUI produced by TkInter. The concepts of the widget are covered, as well as when to use the Text widget. This resource also breaks down how positions within the text are indexed, and how you can index by line/column, line-end, beginning, current, and other line-based positions. This link also gives detail on how to customize the appearance of the text by using functions provided by the module, and tags that allow you to modify specific attributes.
This resource answers question: 1

###Mini Abstract of Relavance for [Displaying Message and Dialogue Boxes]
This resource explains how to display message prompts and dialogue boxes on a GUI produced by TkInter. It goes into detail about tkMessageBox, and shows how if the standard message box provided by default does not suit your need you can then change the box by using a message box option which utilizes different: constanst, strings, and widgets. This link also provides a list of useful helper functions that can be used to build off of the standard message bo including: showinfo, showwarning,showerror, askquestion, and more.
This resource answers question: 1

###Mini Abstract of Relevance for [Widget Classes]
This resource provides links to documentation on all 15 qidgets that TkInter supports, while also helping to clarify how the GUI can be laid out. Using the different widgets, you can separate your GUI into the following different components:
- Button
- Canvas
- Frame
- Label
- Menu
- Scrollbar
- Top-Window
just to name a few..
Canvas provides the functionality of being able to draw graphs and plots, and create graphics. This allows you to incorporate whatever design, shape, or look, you please into your GUI. Label can also be used for displaying images. This answers question: 2
The entire layout of the GUI is controlled by the use of the above widgets. But Frame is the main widget used to group other widgets together. The GUI Frame can have a border and a background, then other widgets are included within the frame. Within the frame you can place anything you want to be in the GUI, including: buttons, message boxes, check boxes, menu, canvas, label, radio button, scrollbar, and other elements. Lastly there is a qidget called Top-level that is displayed as a window separate of the frame, which could be useful if you could benefit from possibly having a title window or something of that sort.
This resource also answers question: 3
