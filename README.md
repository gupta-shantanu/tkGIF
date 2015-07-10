# tkGIF
This little script enable usage of GIF animation in tkinter label

#USAGE
Create an ordinary tkinter label and pack it into your form.
For playing animated GIF in this label import tkGIF and do something like following:
    mygif=gifplay(<<tkinter.label Objec>>,<<GIF path>>,<<frame_rate(in ms)>>)
    example:
    gif=GIF.gifplay(self.model2,'./res/neural.gif',0.1)
    gif.play()
    This will play gif infinitely
