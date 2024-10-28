 # Exemple et Deroulement

n=5

init tableau

> inx=index

tab [1|5|4|2|8]

inx 0|1|2|3|4

****************************** i=1 *************************************

key=tab[1]=5

j=1-1=0

Tab[j]=Tab[0]=1

check

(j >= 0) AND (Tab[j] > key)

(0 >= 0)✅ AND (1 > 5)❌

End

tab [1|5|4|2|8]

inx 0|1|2|3|4

****************************** i=2 *************************************

key=tab[2]=4

j=2-1=1

Tab[j]=Tab[1]=5

check

(j >= 0) AND (Tab[j] > key)

(1 >= 0)✅ AND (5 > 4)✅

Tab[j + 1] := Tab[j]

Tab[1+1] = Tab[1]

Tab[2] = Tab[1] //swap

4=5

j=j-1=1-1=0

check

(j >= 0) AND (Tab[j] > key)

(0 >= 0)✅ AND (1 > 4)❌

End

tab [1|4|5|2|8]

inx 0|1|2|3|4

****************************** i=3 *************************************

key=tab[3]=2

j=3-1=2

Tab[j]=Tab[2]=5

check

(j >= 0) AND (Tab[j] > key)

(2 >= 0)✅ AND (5 > 2)✅

Tab[j + 1] := Tab[j]

Tab[2+1] = Tab[2]

Tab[3] = Tab[2] //swap

2=5

tab [1|4|2|5|8]

inx 0|1|2|3|4

j=j-1=2-1=1

check

(j >= 0) AND (Tab[j] > key)

(1 >= 0)✅ AND (4 > 2)✅

Tab[j + 1] := Tab[j]

Tab[1+1] = Tab[1]

Tab[2] = Tab[1] //swap

2=4

tab [1|2|4|5|8]

inx 0|1|2|3|4

j=j-1=1-1=0

check

(j >= 0) AND (Tab[j] > key)

(0 >= 0)✅ AND (1 > 2)❌

End

tab [1|2|4|5|8]

inx 0|1|2|3|4

****************************** i=4 *************************************

key=tab[4]=8

j=4-1=3

Tab[j]=Tab[3]=5

check

(j >= 0) AND (Tab[j] > key)

(3 >= 0)✅ AND (5 > 8)❌

End

End

Sorted array:

tab [1|2|4|5|8]

inx 0|1|2|3|4

DONE ^_^
