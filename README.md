# cors-mofos
Get tired of CORS anywhere keep dying

Just a minimal proxy server for enabling CORS support.  

Deloy the server & make CORS request as following:  
Instead of  
```https://pokeapi.co/api/v2/ability/150/```  
Do this:  
```https://cors-mofos.vercel.app?url=https://pokeapi.co/api/v2/ability/150/&target=https://pokeapi.co`  

(Simply put the target API URL in the ```url``` query, add change the target to `https://pokeapi.co` )
