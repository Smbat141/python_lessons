# Homework №4

```
	1.	Ինչ կտպի mro() method-ը և ինչու(փորձեք research անել, հասկանալ ալգորիթմը և բացատրել)

		class A(object):
			def __init__(self):
				print ("A")

		class B(A):
			def __init__(self):
				print ("B")

		class C(A):
			def __init__(self):
				print ("C")

		class D(B, C):
			def __init__(self):
				print ("D")

		print(D.mro())
		
        2.  Գրել AbstractFile class որը կունենա translate() և write() method
	
            2.1 Գրել EnglishFile class որը կլինի AbstractFile-ի ժառանգ
            
            2.2 translate() method-ը պետք է ընդունի ռուսերեն տառերով գրված տեքստ և վերադաձնի անգլերեն տառերով գրված տեքստ:
                Մեծատառ և փոքրատառ հաշվի չառնել:
                
                Օրինակ ՝    хелло ворлд -> hello world  
                            Хелло Ворлд -> Hello World
                            писат код  -> pisat kod :)
            
            2.3 write() method-ը վերջին թարքմանված տեքստը պետք է գրի file-ում:
            
            2.4 Գրել RussianFile class որը կունենա նույն method-ները բայց տեքստը անգլերենից կդարձնի ռուսերեն:
                
                Օրինակ ՝    hello world -> хелло ворлд
                            Hello World -> хелло ворлд
                            pisat kod   -> писат код :)
                                       
            2.5 Որոշեք թե translate ու write method-ներից որը պետք է լինի abstract և որը սովորական method
```

### Research

```
	1. super() in multiple inheritance
```

### Links

```
Կարաք օգտվեք ստեղից

https://www.programiz.com/python-programming/multiple-inheritance
https://www.geeksforgeeks.org/abstract-classes-in-python/
```
