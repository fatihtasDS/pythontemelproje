# pythontemelproje
www.patika.dev


Ödev 1- Bir listeyi düzleştiren (flatten) fonksiyon yazın. 

List = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
List_flat = []
def flatten(x):
    for i in x :
        if isinstance(i, list):
            flatten(i)
        else:
            List_flat.append(i)

flatten(List)
print(List_flat)



Ödev 2- Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın.

List = [[1, 2], [3, 4], [5, 6, 7]]
List.reverse()
for i in range(len(List)):
    (List[i]) = (List[i])[::-1]

print(List)
