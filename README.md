# Assignment-5.2
Subject, verb, object
subjects=["Americans ","Indians "]
verbs=["play","watch"]
objects=["Baseball","Cricket"]
a=[i+j+" "+k for i in subjects for j in verbs for k in objects]
for i in range(len(a)):
    print (a[i])
