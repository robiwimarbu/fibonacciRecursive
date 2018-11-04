def fibonacci(num,rs=[]):
	if len(rs) == num:
		print(rs)
		return
		
	if len(rs) == 0:
		ls=1
	elif len(rs) < num:
		if len(rs) == 1:
			ls = 1
		else:
			ls = rs[len(rs)-1]
			ls += rs[len(rs)-2] 
	rs.append(ls)	
	return fibonacci(num,rs)
	
fibonacci(10)
