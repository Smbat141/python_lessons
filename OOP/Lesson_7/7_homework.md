# Homework №7

```
	1.	Ինչով են տարբերվում __getattr__ և __getattribute__ method-ները:
	
	2.	Ինչ առավելություն և թերություններ ունեն private attribute-ները:
	
	3.	Գրել God class որը կունենա հետեվյալ attribute-ները և method-ները
		first_name, count_of_hands, super_power
		clap() - կանչում է voice_after_clap()-ը եթե count_of_hands-ը 2+ է
		voice_after_clap() - ծափ տալու ձայն է հանում(ճլտ):
		
		3.1	Որոշեք թե հետեվյալ method-ներից որոնք պետք է լինեն public և որոնք private:
		
		3.2	Գրել երկու class ` Zeus որը կլինի God-ի ժառանգ և Herkules որը կլինի Zeus-ի ժառանգ,
			այդ class-ները կունենան իրենց class attribute-ները և method-ները(public, protected, private)
			
	4	Herkules class-ը պետք է ունենա 3 method
			
		get_public() - վերադարձնում է իր և իր բոլոր parent-ների public attribute-ները և method-ները:
		get_protected() - վերադարձնում է իր և իր բոլոր parent-ների protected attribute-ները և method-ները:
		get_private() - վերադարձնում է իր և իր բոլոր parent-ների private attribute-ները և method-ները:
		
		
		Նախազգուշացում - dir()-ից չօգտվել:
		
		Հուշում՝ կարող եք օգտվել class-ի mro() method-ից կամ __bases__ attribute-ից:
```


### Research
```
	1.	__slots__ attribute: 
	2.	property() function: 
```


### Links

```
Կարող եք օգտվել հետեվյալ link-երից:

https://www.geeksforgeeks.org/private-variables-python/
https://www.geeksforgeeks.org/private-methods-in-python/
https://www.geeksforgeeks.org/polymorphism-in-python/
```
