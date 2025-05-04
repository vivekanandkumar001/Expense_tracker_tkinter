from tkinter import *

from PIL import ImageTk,Image

from tkinter import messagebox

def handle_login():
   email=email_input.get()
   password=password_input.get()
    
   if email=='vkumar0208200@gmail.com'and password=='pass':
        
        messagebox.showinfo('Total expence')
        
   else:
       messagebox.showinfo('email or password is wrong')


root = Toplevel()


root.title('EXPENCE TRACKER')

root.maxsize(600,600)

root.configure(background='#28D8E9')

img=Image.open('images.png')
print (img)

img=img.resize((70,70))

img=ImageTk.PhotoImage(img)

img_label=Label(root,image=img)

img_label.pack(pady=(10,10))

text_label=Label(root,text='expence tracker',fg='white',bg='#28D8E9')

text_label.pack()
text_label.config(font=('verdana',24))

email_label=Label(root,text='Enter Email',fg='white',bg='#28D8E9')

email_label.pack()

email_label.config(font=('verdana',12))

email_input=Entry(root,width=50)

email_input.pack(ipady=6,pady=(1,15))

password_label=Label(root,text='Enter PassWord',fg='white',bg='#28D8E9')

password_label.pack()

password_label.config(font=('verdana',12))

password_input=Entry(root,width=50)

password_input.pack(ipady=6,pady=(1,15))

login_btn=Button(root,text='Login here',bg='white',fg='black',width=20,height=2,command=handle_login)

login_btn.pack(pady=(10,20))

login_btn.config(font=('verdana',10))





root.mainloop()
