# test_gb_1
test
<<<<<<< HEAD
 fghnhf 
 
=======
asdfadfad
>>>>>>> b21fa44bdd3b81f8cf532d226158782a2bde41b8

Пробный код на калькулятор

```python

``` from tkinter import *

class Main(Frame):
    def __init__(self, root):
        super(Main, self).__init__(root)
        self.build()

    def build(self):
        pass
 
    def logicalc(self, operation):
        pass

    def update():
       pass


if __name__ == '__main__':
    root = Tk()
    root["bg"] = "#000"
    root.geometry("485x550+200+200")
    root.title("Калькулятор")
    root.resizable(False, False)
    app = Main(root)
    app.pack()
    root.mainloop()