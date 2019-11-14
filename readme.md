# Rui's Problem Solution:
```js
a=(m,n,l)=>m>n?0:l.reduce((k,j)=>k+(m%j?0:1),0)+a(m+1,n,l);
```
