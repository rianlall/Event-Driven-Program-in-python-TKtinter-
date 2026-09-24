import tkinter in tk 

root = tk.tk()
root.title("Colour options in Tktinter")

Button = tk.button(root,  text-"click me", activebackground, "blue", activeforeground, "white")
button.pack()

Button = tk.button(root,  text-"click me", activebackground, "grey", activeforeground, "black")
button.pack()

label= = tk.label(root, text"Hello, Welcome Year 1" -, bg-"blue", fg-"black"
label.pack()

label= = tk.label(root, text"Hello, Welcome Year 1" -, bg-"black ", fg-"blue"
label.pack()

entry = tk.Entry(root, selectbackground-"lightblue", selectforeground- "black")
entry.pack

root.mainloop
