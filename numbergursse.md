import random
n=random.randint(1,20)
#print(n)
i=input('''GUESS THE NUMBER BTW 1  AND 20\n''')
i=int(i)
count=0
while i!=n:
	if i<n:
		print("choose a little bit greater ")
		i=input()
		i=int(i)
	elif i>n:
		print("choose a little but smaller number ")
		i=input()
		i=int(i)
	count=count+1
if i==n:
	print(f"you won in {count+1} chances")
print("hi")
