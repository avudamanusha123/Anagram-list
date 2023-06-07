# Anagram-list
list1=[]
n=int(input())
for i in range(n):
   str=input()
   list1.append(str)
list2=list(dict.fromkeys(list1))
def my_fun(list2):
    dict={}
    for word in list2:
        sorted_list="".join(sorted(word))
        if sorted_list in dict:
            dict[sorted_list].append(word)
        else:
            dict[sorted_list]=[word]
    return list(dict.values())
print(my_fun(list2))
