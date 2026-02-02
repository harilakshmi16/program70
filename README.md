def fact(n):
if n==1:
f=1
else:
f = n * fact(n-1)
return f
num = int(input(&quot;Enter an integer: &quot;))
result = fact(num)
print(&quot;The factorial of&quot;, num, &quot; is: &quot;, result)
