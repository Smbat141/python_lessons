# Homework №5

```
	1.	Ինչ է ժառանգականությունը և ինչ խնդիր է լուծում:
	
	2.	Ինչ է abstact class-ը և ինչ առավելություն է տալիս:
	
	3.	Գրել FilterText class որը պետք է ունենա text attribute որը կլինի հետեվյալ string-ը:
		
		'055-445-789 E.Mask 124.06.2014 093-587-135 Nemo 1.09.1887 E.Auditore 24.17.2020 096-2288-987 R.Rocknrolla'
				
		Հուշում ՝ պետք է օգտագորցեք Operators overloading և regex
		
		3.1 x = FilterText(text)
		    x.names # ['E.Mask', 'E.Auditore', 'R.Rocknrolla']
		    x.dates # ['1.09.1887', '24.17.2020']
		    x.phone_numbers # ['055-445-789', '093-587-135']
			
		3.2 x[1]    # E.Mask
		    x[1:3] # ['E.Mask', '124.06.2014']
			
		3.3 x[0] = 'G.Ritchie'
		    x.text # G.Ritchie E.Mask 124.06.2014 093-587-135 Nemo 1.09.1887 E.Auditore 24.17.2020 096-2288-987 R.Rocknrolla
```

### Research
```
	1. __bool__ method  
	2. __len__ method 
	3. if գրելու դեպքում նախորդ method-ներից որին է տրվում առավելություն:
```


### Links

```
Կարաք օգտվեք ստեղից

https://www.geeksforgeeks.org/__getitem__-and-__setitem__-in-python/
https://python-reference.readthedocs.io/en/latest/docs/dunderattr/getattr.html
https://python-reference.readthedocs.io/en/latest/docs/dunderattr/setattr.html
https://python-reference.readthedocs.io/en/latest/docs/dunderattr/getattribute.html
```
