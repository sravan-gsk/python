s=input().split('.')
d={'py':'python','txt':'text','xls':'excel','doc':'document'}
>>> f=s[-1].lower()
>>> if f in d:
	print(d[f])
else:
   print('invalid extension')
