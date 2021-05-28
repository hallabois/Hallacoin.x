# Halla.coin
[https://hallabois.github.io/Halla.coin/](https://hallabois.github.io/Halla.coin/)
---

# Ohjeet
[npm](https://www.npmjs.com/get-npm) tulee olla asennettuna

## Asenna riippuvuudet
```npm install```
## Käynnistä http-serveri
```npm run dev```
Hostaa nettisivun koneellasi, normaalisti osoitteessa https://localhost:5000

# Arkkitehtuurista
/public/                ```Compilattu koodi ja staattinen media (mm. 3d-mallit)```

/scripts/						    ```turha```

/src/								    ```Lähdekoodi```

/src/App.svelte			    ```Nettisivun päätiedosto, perjaatteessa "index.html"```

/src/main.js				    ```Wrapperi, tuskin tarpeellista koskaan avata tai muokata```

/src/scene.svelte		    ```3D-kolikon luova javascript-tiedosto, käyttää kirjastoa "three.js"```

src/Loadingbar.svelte   ```Teksti, joka näkyy kun kolikkoa vielä ladataan```

# Analytiikka
https://simpleanalytics.com/hallacoin.ml - Kunnioittaa kävijöiden yksityisyyttä paremmin kuin google, ei käytä cookieita :)
Lisää analytiikka-palvelun lupauksia: https://docs.simpleanalytics.com/what-we-collect?ref=simpleanalytics.com
