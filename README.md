# decorators.python
def demo():
    return 5
def decor(d):
    def add():
        return d()+10
    return add
x=decor(demo)
print(x())
