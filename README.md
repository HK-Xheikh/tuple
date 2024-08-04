#--------(tuple)--------#
tuple1=("hasnain","haris","huzzi")
print(type(tuple1))
x=list(tuple1)
print(type(x))
x.remove("huzzi")
print(x)
print(type(x))
y=tuple(x)
print(y)
print(type(y))


#-------{set}-------#
list1=["sohail","fawad","hasnain","huzzi","haris","sohail","fawad"]
print(list1)
x=set(list1)
print(x)


#-----type of set {unionset}--------#
set1={10,20,30,"huzzi","hasnain",40,50,60}
set2={10,20,30,"huzzi","hasnain",40,50,60,70,80,90}
x=set1.union(set2)
print(type(x))
print(x)


#-----type of set {subset}--------#
set1={10,20,30,"huzzi","hasnain",40,50,60}
set2={10,20,30,"huzzi","hasnain",40,50,60,70,80,90}
x=set1.issubset(set2)
print(type(x))
print(x)


#-----type of set {superset}--------#
set1={10,20,30,"huzzi","hasnain",40,50,60}
set2={10,20,30,"huzzi","hasnain",40,50,60,70,80,90}
x=set1.issuperset(set2)
print(type(x))
print(x)


#-----type of set {superset set me loop}--------#


set1={10,20,30,"huzzi","hasnain",40,50,60}
set2={10,20,30,"huzzi","hasnain",40,50,60,70,80,90}
x=set1.issuperset(set2)
print(type(x))
print(x)
for i in {set}:
    print(x)


#--------dicnoary---------#

dic={
       "name":"huzzi","age":24,"male":True

}
x=dic.get("age")
print(x)
print(dic["name"])



dic={
       "name":"huzzi","age":24,"male":True

}

for i in dic.keys():
    print(i) 

dic={
       "name":"huzzi","age":24,"male":True

}

dic["age"]=30
print(dic)

dic={
       "name":"huzzi","age":24,"male":True

}

dic.update({"city":"karachi"})
print(dic)


del dic ["age"]
print(dic)


