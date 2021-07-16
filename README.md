# MOST-FREQUENT
string=str(input("enter a string"))
count=0
dic={}
for i in string:
    print(i)
    count+=1
    if(i in dic):
        dic[i]+=1
    else:
        dic[i]=1
print(count)
print(dic)
l=sorted(dic.values())
print("sorted dictionary is",l)
