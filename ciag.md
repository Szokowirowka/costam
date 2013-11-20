```c

dolna=0; gorna=c; suma=a[0]; /* suma=a[dolna]+a[dolna+1]+...+[gorna]*/

while(gorna<n && suma!=r)
  if(suma<r) {gorna=gorna+1; suma=suma+a[gorna];}
  else {suma=suma-a[dolna];dolna=dolna+1;}
```

```c
#Wstawianie a[k] do uporządkowanego już ciągu a[0],a[1],...,a[k-1]:

i=k;
while (i>0 && a[i-1}>a[i}){
