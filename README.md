#>> LOGIC

Logic plays a big role in any program. Every language has it's own way of documenting and handling logic. Let's take a look at how Ruby does it.

	== 		equals
	!=		does not equal
	>		greater than
	<		less than
	>=		greater than or equal to
	<=		less than or equal to
	&&		and
	||		or

These operators are used to check whether a statement is true or false. For example:

	5 == 5
		>> true
	
	5 == 8
		>> false
	
	2 > 9
		>> false
	
	7 <= 12
		>> true
	
	"string" == "string"
		>> true
	
We've seen many of these symbols in our math classes. A few that we may have not seen are `&&` and `||`. These operators help us string together two different statements and return a boolean value.

	true && true
		>> true
	
	true && false 
		>> false
	
	false && false
		>> false
		
	
	true || true
		>> true
		
	true || false
		>> true
	
	false || false
		>> false
		
So, for example:

	(5 != 2) && (2 > 7)
		>> false

This statement returns `false`, because the first statement is `true` and the last statement is `false`.		

Let's try another:

	(3 == 5) || (9 >= 10)
		>> false

This statement returns `false` because the first statement is `false` and the last statement is `false`.

Try a few out on your own!

	(4 != 4) 
	
	
	(8 <=9)
	
	
	((4*5) > 10) 
		
	
	(1 == (1**2))
	
	
	(100 == 100) && (1 < 4)
	
	
	(6 < 10) || (0 >= 0)
	
	
	((50/10) == 5) && (2*5 > 4)
	
Now write some logic statements of your own! See if you can fool the person next to you.
	
	


	
	
	
