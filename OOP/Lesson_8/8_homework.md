# Homework №8

```
    1.  Ձեր նոր տնայինի directory-ում ստեղծեք lexus.txt և tesla.txt file-եր:
	    
        1.1 copy արեք https://github.com/Smbat141/python_lessons/blob/master/OOP/Lesson_8/tesla.txt link֊ի text֊ը ձեր նոր ստեղծած tesla.txt-ի մեջ
        1.2 copy արեք https://github.com/Smbat141/python_lessons/blob/master/OOP/Lesson_8/lexus.txt link֊ի text֊ը ձեր նոր ստեղծած lexus.txt-ի մեջ
	        
    2.  Research արեք մինչև շարունակելը(decorator-ը կարաք տնայինը անելուց հետո նայեք :)
	
    3.	Գրել File class որը կունենա
		
        3.1 file attribute որը կունենա getter, setter (օգտվելով property-ից որպես class attribute):
            
            getter - կգտնի class-ի անունով file(․txt ֆորմատով, այսինքն քանի որ հիմա class-ի անունը File-ա վերադարցնի "file.txt" file֊ը): 
            
            Օրինակ ՝	>>> class File:
                        >>>     ...
                        >>> 
                        >>> f = File()
                        >>> f.file # file object
                        <_io.TextIOWrapper name='file.txt' mode='r' encoding='cp1251'> 

            Եթե class-ի անունով file չլինի սարքել նորը:

            setter - կփոխի fail attribute-ը ու set կանի նոր file
            
            Օրինակ ՝	>>> class File:
                        >>>     ...
                        >>> 
                        >>> f = File()
                        >>> f.file
                        <_io.TextIOWrapper name='file.txt' mode='r' encoding='cp1251'> 
                        >>> self.file = open("new_file.txt")
                        >>> self.file
                        <_io.TextIOWrapper name='new_file.txt' mode='r' encoding='cp1251'> 
                        
    
        3.2 child_file attribute որը կունենա getter, setter, deleter(օգտվելով property-ից որպես decorator):
            
            getter - վերադարձնում է ժառանգ class-ի անունով file-ի text-ը:
            setter - կփոխի ժառանգ class-ի անունով file-ի text-ը:
            deleter - կջնջի ժառանգ class-ի անունով file-ը:
        
            
            Օրինակ`     >>> class Tesla(File):
                        >>>     pass
                        >>>
                        >>> tesla = Tesla()
                        >>> tesla.child_file # 1,Model_S,Sedan,Electric ...
                        >>> tesla.child_file = 'New text about tesla'
                        >>> tesla.child_file
                        New text about tesla
                        >>> del tesla.child_file # remove tesla.txt file
                        
                        >>> class Lexus(File):
                        >>>     pass
                        >>>
                        >>> lexus = Lexus()
                        >>> lexus.child_file # 1,Lexus_IS,Sedan,Gasoline ...
                        >>> lexus.child_file = 'New text about lexus'
                        >>> lexus.child_file
                        New text about lexus
                        >>> del lexus.child_file # remove lexus.txt file
```

### Research

```
    1.  file = open("new_file.txt")
        Ոնց կարանք ստանալ արդեն open արած ֆայլի անունը file object-ից("new_file.txt" string-ը վերը նշված օրինակից)
    
    2.  remove file
    3.  rename file name
    4.  decorators (կրկնել անպայման)
```

### Links

```
Կարող եք օգտվել հետեվյալ link-երից:

https://www.geeksforgeeks.org/python-property-function/
https://www.programiz.com/python-programming/property/
```
