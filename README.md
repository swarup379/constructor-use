#illustrate use of constructor
class abc():
    def __init__(self,var):
        print("the value is in class method")
        self.var=var
        print("the value is:",var)
obj=abc(10)
