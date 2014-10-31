10-31-2014-HW
=============
def strCompare(str):
    for i in range(len(str)-1):
        for x in range(len(str)-i):
            if str[i]==str[x]:
                return True
            
