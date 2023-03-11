# verfirer-for-2048movment_verifer = ['up', 'down', 'left', 'right',]
def movment_detshion ():#seeing if your movment is verifyed
    x = input("type you movment (all lowercase)")
    if ((x) in movment_verifer):
        y = ("true")
        print ("true")
    else:
        movment_detshion ()
movment_detshion ()
