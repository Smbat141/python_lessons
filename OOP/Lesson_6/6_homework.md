# Homework №6

```
	1.	Ինչ է polimorfizm-ը և ինչ խնդիր է լուծում:
	
	2.	Գրել class TeslaMotors որը կունենա 3 class attribute
		 names = ['Model S', 'Roadster', 'Model 3', 'Cybertruck', 'Model Y', 'Model X']
		 body_types = ['Sedan', 'Coupe', 'Sedan', 'Truck', 'SUVS', 'SUVS']
		 engine_types = ['Electric', 'Electric', 'Electric', 'Electric', 'Electric']
		
		2.1	class-ը պետք է լինի iterable:
		

		2.2	Գրել set_iter_by method որով դինամիկ կորոշենք թե class-ի որ attribute-ի վրա պետք է աշխատի for-ը(dafault-ով names): 

			tesla = TeslaMotors()
			
			>>> for item in tesla:
			... 	print(item) # 1. Model S, 2. Roadster ...
			>>>
			>>> tesla.set_iter_by('body_types')
			>>>
			>>> for item in tesla:
			... 	print(item) # 1. Sedan S, 2. Coupe ...
		
		2.3	in արտահայտությունը նույնպես պետք է աշխատի ըստ մեր նախորոք որոշած attribute-ի:
			
			>>> tesla = TeslaMotors('body_types')
			>>>
			>>> 'Coupe' in tesla   # True
			>>> 'Model S' in tesla # False
			>>> 
			>>> tesla.set_iter_by('names')
			>>> 
			>>> 'Coupe' in tesla   # False
			>>> 'Model S' in tesla # True
```

### Research
```
	1. __call__ method:

	2. <, >, operators
```


### Links

```
Կարող եք օգտվել հետեվյալ link-երից:

https://www.programiz.com/python-programming/iterator
https://realpython.com/operator-function-overloading/#overloading-built-in-operators
```
