doc1=open("book1.txt","r",errors='ignore')
data1=doc1.read()
data1
doc2=open("chapter 1.txt","r",errors='ignore')
data2=doc2.read()
data2
punctuations="<>,.!@#$%^&*~''{}""()[]:;?/\_-“”—’"
no_punct=""
for char in data1:
    if char not in punctuations:
        no_punct=no_punct+char
print(no_punct)
punctuations="“”<>,.!@#$%^&*~''{}""()[]:;?/\_-—’"
no_punct2=""
for char in data2:
    if char not in punctuations:
        no_punct2=no_punct2+char
print(no_punct2)
def solve (s,t): 
    s=s.lower()
    t=t.lower()
    slist =s.split(" ")
    tlist =t.split(" ")
    return len(list(set(slist)&set(tlist)))
no_punct
no_punct2
print(ob.solve(no_punct,no_punct2))
