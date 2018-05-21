# Tkinter
from Tkinter import*
root=Tk()
root.title("SHOPPING")
root.configure(bg='light blue')
Label(root,text='Welcome to my project',font="Arial 20",bg='light blue').grid(row=0,column=0)
Label(root,text='!!! MUSICAL SHOPPING !!!',height=3,font="Arial 16 bold",fg='red',bg='light blue').grid(row=1,column=0)
Label(root,text="subimitted to Dr. Mahesh Kumar",font="Arial 10 bold",bg='light blue').grid(row=2,column=0)
Label(root,text='project by Shikha mangal',justify='left',font="Arial 8 bold",bg='light blue').grid(row=3,column=0)
Label(root,text='Er.no:-151389',justify='left',font="Arial 8 bold",bg='light blue').grid(row=4,column=0)
Label(root,text='Batch:-B5',justify='left',font="Arial 8 bold",bg='light blue').grid(row=5,column=0)
Label(root,text='Email:- mangal.shikha1997@gmail.com',justify='left',font="Arial 8 bold",bg='light blue').grid(row=6,column=0)

    
def fun():
    root.destroy()
    root1=Tk()
    root1.configure(bg='light green')
    Label(root1,text='WELCOME',font="Arial 16 bold",bg='light green',height=1).grid(row=0,column=0)
    def fun1():
        root1.destroy()
        root2=Tk()
        root2.configure(bg='light green')
        v1=IntVar()
        v2=IntVar()
        v3=IntVar()
        v4=IntVar()
        v5=IntVar()
        v6=IntVar()
        v7=IntVar()
        v8=IntVar()
        img=PhotoImage(file="piano.gif")
        Label(root2,image=img).grid(row=0,column=0)
        Checkbutton(root2,text='Piano',variable=v1,onvalue=4000,font="Arial 16 bold",bg='light green').grid(row=1,column=0)
        Label(root2,text='Rs 4000',font="Arial 16 bold",bg='light green',fg='red').grid(row=2,column=0)
        
        img1=PhotoImage(file="harmo_standard.gif")
        Label(root2,image=img1).grid(row=0,column=3)
        Checkbutton(root2,text='harmonium',variable=v2,onvalue=50000,font="Arial 16 bold",bg='light green').grid(row=1,column=3)
        Label(root2,text='Rs 50000',font="Arial 16 bold",bg='light green',fg='red').grid(row=2,column=3)
         
        img2=PhotoImage(file="drum.gif")
        Label(root2,image=img2).grid(row=0,column=5)
        Checkbutton(root2,text='Drum',variable=v3,onvalue=40000,font="Arial 16 bold",bg='light green').grid(row=1,column=5)
        Label(root2,text='Rs 40000',font="Arial 16 bold",bg='light green',fg='red').grid(row=2,column=5)
         
        img3=PhotoImage(file="guitar.gif")
        Label(root2,image=img3).grid(row=3,column=0)
        Checkbutton(root2,text='Guitar',variable=v4,onvalue=6000,font="Arial 16 bold",bg='light green').grid(row=4,column=0)
        Label(root2,text='Rs 6000',font="Arial 16 bold",bg='light green',fg='red').grid(row=5,column=0)
         
        img4=PhotoImage(file="shenai.gif")
        Label(root2,image=img4).grid(row=3,column=3)
        Checkbutton(root2,text='Shenai',variable=v5,onvalue=2000,font="Arial 16 bold",bg='light green').grid(row=4,column=3)
        Label(root2,text='Rs 2000',font="Arial 16 bold",bg='light green',fg='red').grid(row=5,column=3)
         
        img5=PhotoImage(file="trumpet-009.gif")
        Label(root2,image=img5).grid(row=3,column=5)
        Checkbutton(root2,text='Trumpet',variable=v6,onvalue=4600,font="Arial 16 bold",bg='light green').grid(row=4,column=5)
        Label(root2,text='Rs 4600',font="Arial 16 bold",bg='light green',fg='red').grid(row=5,column=5)
         
        img6=PhotoImage(file="flute.gif")
        Label(root2,image=img6).grid(row=0,column=6)
        Checkbutton(root2,text='Flute',variable=v7,onvalue=3600,font="Arial 16 bold",bg='light green').grid(row=1,column=6)
        Label(root2,text='Rs 3600',font="Arial 16 bold",bg='light green',fg='red').grid(row=2,column=6)

        img7=PhotoImage(file="triangle.gif")
        Label(root2,image=img7).grid(row=3,column=6)
        Checkbutton(root2,text='Triangle',variable=v7,onvalue=1600,font="Arial 16 bold",bg='light green').grid(row=4,column=6)
        Label(root2,text='Rs 1600',font="Arial 16 bold",bg='light green',fg='red').grid(row=5,column=6)

        

        def payment2():
            root2.destroy()
            root4=Tk()
           
            root4.configure(bg='light green')
            Label(root4,text='First name:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=0,column=0)
            e1=Entry()
            e1.grid(row=0,column=1)
            Label(root4,text='Last name:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=1,column=0)
            e2=Entry()
            e2.grid(row=1,column=1)
            Label(root4,text='Email:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=2,column=0)
            e3=Entry()
            e3.grid(row=2,column=1)
            Label(root4,text='contact no.:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=3,column=0)
            e4=Entry()
            e4.grid(row=3,column=1)
            Label(root4,text='Address:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=4,column=0)
            e5=Entry()
            e5.grid(row=4,column=1)
            Label(root4,text='City:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=5,column=0)
            e5=Entry()
            e5.grid(row=5,column=1)
            
            def done():
                root4.destroy()
                root5=Tk()
                Label(root5,text='Payment done',font="Arial 25 bold",fg='dark green').grid(row=0,column=0)
                Label(root5,text='Thank you for Shopping',font="Arial 20 bold",fg='dark green').grid(row=1,column=0)
                
                def exi():
                    root5.destroy()
                Button(root5,text='EXIT',font="Arial 16 bold",bg='light green',command=exi).grid(row=2,column=0)   
            Button(root4,text='Pay',fg='blue',font="Arial 16 bold",bg='light green',command=done).grid(row=6,column=2)
           
           
           
        Button(root2,text='Proceed to payment',font="Arial 16 bold",bg='light blue',command=payment2).grid(row=7,column=4)
        def total():
            total=v1.get()+v2.get()+v3.get()+v4.get()+v5.get()+v6.get()+v7.get()
            Label(root2,text=total,font="Arial 16 bold",bg='light blue',fg='red').grid(row=7,column=6)
            
        Button(root2,text='TOTAL',font="Arial 16 bold",bg='light blue',command=total).grid(row=7,column=5)
        mainloop()
        
    Button(root1,text='MUSICAL INSTRUMENTS',font="Arial 10 bold",command=fun1, bg='light green',height=2).grid(row=1,column=0)
    def fun2():
        root1.destroy()
        root3=Tk()
        
        root3.configure(bg='light green')
        a1=IntVar()
        a2=IntVar()
        a3=IntVar()
        a4=IntVar()
        a5=IntVar()

        i1=PhotoImage(file="mic.gif")
        Label(root3,image=i1).grid(row=0,column=0)
        Checkbutton(root3,text='Mic',variable=a1,onvalue=1000,font="Arial 16 bold",bg='light green').grid(row=1,column=0)
        Label(root3,text='Rs 1000',font="Arial 16 bold",bg='light green',fg='red').grid(row=2,column=0)

        i2=PhotoImage(file="Zebronics-.gif")
        Label(root3,image=i2).grid(row=0,column=3)
        Checkbutton(root3,text='speakers',variable=a2,onvalue=3500,font="Arial 16 bold",bg='light green').grid(row=1,column=3)
        Label(root3,text='Rs 3500',font="Arial 16 bold",bg='light green',fg='red').grid(row=2,column=3)

        i3=PhotoImage(file="computer-speaker.gif")
        Label(root3,image=i3).grid(row=4,column=0)
        Checkbutton(root3,text='computer-speaker',variable=a3,onvalue=2800,font="Arial 16 bold",bg='light green').grid(row=5,column=0)
        Label(root3,text='Rs 2800',font="Arial 16 bold",bg='light green',fg='red').grid(row=6,column=0)

        i4=PhotoImage(file="JBL.gif")
        Label(root3,image=i4).grid(row=4,column=3)
        Checkbutton(root3,text='Earphones',variable=a4,onvalue=800,font="Arial 16 bold",bg='light green').grid(row=5,column=3)
        Label(root3,text='Rs 800',font="Arial 16 bold",bg='light green',fg='red').grid(row=6,column=3)

        i5=PhotoImage(file="headphones.gif")
        Label(root3,image=i5).grid(row=0,column=4)
        Checkbutton(root3,text='Headphones',variable=a5,onvalue=5500,font="Arial 16 bold",bg='light green').grid(row=1,column=5)
        Label(root3,text='Rs 5500',font="Arial 16 bold",bg='light green',fg='red').grid(row=2,column=5)
        def payment2():
            root3.destroy()
            root4=Tk()
            
            root4.configure(bg='light green')
            Label(root4,text='First name:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=0,column=0)
            e1=Entry()
            e1.grid(row=0,column=1)
            Label(root4,text='Last name:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=1,column=0)
            e2=Entry()
            e2.grid(row=1,column=1)
            Label(root4,text='Email:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=2,column=0)
            e3=Entry()
            e3.grid(row=2,column=1)
            Label(root4,text='contact no.:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=3,column=0)
            e4=Entry()
            e4.grid(row=3,column=1)
            Label(root4,text='Address:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=4,column=0)
            e5=Entry()
            e5.grid(row=4,column=1)
            Label(root4,text='City:',fg='blue',font="Arial 16 bold",bg='light green').grid(row=5,column=0)
            e5=Entry()
            e5.grid(row=5,column=1)
            def done():
                root4.destroy()
                root5=Tk()
                Label(root5,text='Payment done..',font="Arial 25 bold",fg='dark green').grid(row=0,column=0)
                Label(root5,text='Thank you for Shopping',font="Arial 20 bold",fg='dark green').grid(row=1,column=0)
                def exi():
                    root5.destroy()
                Button(root5,text='EXIT',font="Arial 16 bold",bg='light green',command=exi).grid(row=2,column=0)   
            Button(root4,text='Pay',fg='blue',font="Arial 16 bold",bg='light green',command=done).grid(row=6,column=2)
            
                
            
        Button(root3,text='Proceed to payment',font="Arial 16 bold",bg='light blue',command=payment2).grid(row=7,column=4)
        def total():
            total=a1.get()+a2.get()+a3.get()+a4.get()
            Label(root3,text=total,font="Arial 16 bold",bg='light blue',fg='red').grid(row=7,column=6)
            
        Button(root3,text='TOTAL',font="Arial 16 bold",bg='light blue',command=total).grid(row=7,column=5)
        
        mainloop()                                                                                                      
    Button(root1,text='MUSICAL ACCESSORIES',font="Arial 10 bold",bg='light green',height=2,command=fun2).grid(row=2,column=0)
    
    
    
        

Button(root,text='Click to view project',justify='right',command=fun).grid(row=7,column=0)

root.mainloop()

