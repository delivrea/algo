# algo


L=[] #initialisation liste vide
n=int(input("Saisir un nombre entier"))
for k in range (1,n+1):
 if n%k==0:
  L.append(k)
print(L)
