
Creamos Views para ver anuncios que tienen potencial cuando estamos escalando

```table-of-contents
title: 
style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
minLevel: 0 # Include headings from the specified level
maxLevel: 0 # Include headings up to the specified level
include: 
exclude: 
includeLinks: true # Make headings clickable
hideWhenEmpty: false # Hide TOC if no headings are found
debugInConsole: false # Print debug info in Obsidian console
```

# View Para identificar Anuncios que estan para escalar

- Create View 
- A nivel de Anuncio lo vamos a hacer
- Luego le damos en **"Ad Amount Spend"** is greater than 250
- Luego **"Ad Purchase ROAS"** is greater than 2
- Los anuncios que queremos escalar son los que tienen un ROAS de 2 o están por encima.
- Además ponerle **"Ad delivery is Active"**
- Luego de Nombre Scale -> Ads to Scale

# View Para identificar los que tenemos que Parar

-  Luego le damos en **"Ad Amount Spend"** is greater than "120" -> Este "120" tiene que ser tres veces nuestro BE CPA
-  Luego **"Ad Purchase ROAS"** is between 0 y 1.6 
- ponerle **"Ad delivery is Active"**
- De nombre Kill 

# View para ver anuncios que tienen gasto, no terminan de ser rentables pero no nos hacen perder dinero

- **Ad Amount Spent** is greater than 120
- **Ad ROAS** is between 1.6 to 2 
- **"Ad delivery is Active"**
- 