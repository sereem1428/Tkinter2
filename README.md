from tkinter import *
from tkinter import ttk
window = Tk()
window.geometry('400x400+400+200')
window.title('SIRIN FAHAD')
def click():
    print('SIRIN FAHAD55')


fm =LabelFrame(window, text="SIRIN FAHAD" ,height=200, width=200, bg="#CF5B5B", padx=80, pady=80)
fm.place(x=100, y=100)

bt =Button(fm, text="Login" , command = click)
bt.pack()


window.mainloop()
