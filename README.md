import textwrap
def merge_the_tools(string, k):
    c=0
    s=''
    for i in string:
        if i not in s:
            s=s+i
        c+=1
        if c==k:
            print(s)
            c=0
            s=''
   
string, k = input(), int(input())
merge_the_tools(string, k)
