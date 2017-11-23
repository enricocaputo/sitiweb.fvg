---
layout: post
title: 'Dati Strutturati: cosa sono e come aggiungerli ai siti web'
excerpt: Se Google comprende il markup delle tue pagine, può utilizzare tali informazioni per aggiungere rich snippet e altre funzionalità al tuo risultato di ricerca.
author: SITIWEB | Agenzia Web
date:   2017-11-18
last_modified_at: 2017-11-18
categories: 'tutorial'
comments: true
---
<img itemprop="image" src="/img/structured-data-markup.jpg" alt="Dati Strutturati e microdata aiutano a posizionare il sito web sui motori di ricerca" title="Dati Strutturati e microdata aiutano a posizionare il sito web sui motori di ricerca">

## Dati strutturati, cosa sono e a cosa servono:

<a href="http://schema.org/" rel="nofollow" title="vai al link esterno Schema.org">Schema.org</a> è un progetto nato dalla collaborazione tra Google, Microsoft e Yahoo! con lo scopo di migliorare il Web creando un vocabolario comune per la descrizione dei dati sul Web. Se aggiungi il markup schema.org alle tue pagine HTML, molti prodotti, inclusa la Ricerca Google, e società potranno comprendere i dati del tuo sito. In modo simile, se aggiungi il markup schema.org alla tua email in formato HTML, anche altri prodotti, oltre a Gmail, potrebbero comprendere i dati.

### Posizionamento sui motori di ricerca
L'indice di ricerca dei motori di ricerca si evolve continuamente man mano che vengono aggiunti e modificati i contenuti sul Web. Queste modifiche ai contenuti, così come gli aggiornamenti agli algoritmi di posizionamento, possono modificare la posizione degli URL nei risultati di ricerca e a volte anche rimuoverli. Ecco perchè se
aggiungiamo, aggiorniamo e miglioriamo i contenuti e i dati strutturati del nostro sito web possiamo ottenre
rich results che conducono a molte conversioni. cosa sono i rich results? Continua a leggere, vedrai che non è
nulla di complicato ma di certo è un costante lavoro di affinamento e richiede parecchio tempo e competenza in SEO.

### Rich result e rich snippet
Rich results e rich snippets sono sinonimi: un risultato avanzato nella Ricerca Google con funzioni visive o interattive aggiuntive. Precedentemente erano noti anche come "scheda informativa".


## Dati strutturati, come Aggiungerli al sito web:

Puoi utilizzare tipi diversi di markup per descrivere i tuoi dati con il vocabolario di schema.org. Puoi utilizzare i microdati e JSON-L. I microdati e il formato JSON-LD sono due modi diversi per eseguire il markup dei tuoi dati utilizzando il vocabolario di schema.org. È meglio scegliere i microdati o il formato JSON-LD ed evitare di utilizzare entrambi in un'unica pagina o email. Google preferisce i microdati per i contenuti web.

### Json
Esempio:

```

  <script type="application/ld+json">
  {
  "@context": "http://schema.org/",
  "@type": "Recipe",
  "name": "Grandma's Holiday Apple Pie",
  "author": "Elaine Smith",
  "image": "http://images.edge-generalmills.com/56459281-6fe6-4d9d-984f-385c9488d824.jpg",
  "description": "A classic apple pie.",
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4",
    "reviewCount": "276",
    "bestRating": "5",
    "worstRating": "1"
  },
  "prepTime": "PT30M",
  "totalTime": "PT1H",
  "recipeYield": "8",
  "nutrition": {
    "@type": "NutritionInformation",
    "servingSize": "1 medium slice",
    "calories": "230 calories",
    "fatContent": "1 g",
    "carbohydrateContent": "43 g",
  },
  "recipeIngredient": [
    "1 box refrigerated pie crusts, softened as directed on box",
    "6 cups thinly sliced, peeled apples (6 medium)",
    "..."
  ],
  "recipeInstructions": [
    "1...",
    "2..."
   ]
  }
  </script>

```


### Microdata
Esempio:

```

  <!DOCTYPE HTML>
  <html>
   <head>
    <title>Photo gallery</title>
   </head>
   <body>
    <h1>My photos</h1>
    <figure itemscope itemtype="http://n.whatwg.org/work" itemref="licenses">
     <img itemprop="work" src="images/house.jpeg" alt="A white house, boarded up, sits in a forest.">
     <figcaption itemprop="title">The house I found.</figcaption>
    </figure>
    <figure itemscope itemtype="http://n.whatwg.org/work" itemref="licenses">
     <img itemprop="work" src="images/mailbox.jpeg" alt="Outside the house is a mailbox. It has a leaflet inside.">
     <figcaption itemprop="title">The mailbox.</figcaption>
    </figure>
    <footer>
     <p id="licenses">All images licensed under the <a itemprop="license"
     href="http://www.opensource.org/licenses/mit-license.php">MIT
     license</a>.</p>
    </footer>
   </body>
  </html>

```

### Strumento di verifica Markup Dati strutturati
Inserisci l'URL della tua pagina o il codice HTML contenente il markup nello
<a href="https://search.google.com/structured-data/testing-tool" rel="nofollow" title="external link - vai allo strumento test dati strutturati di Goolge"> Strumento di Test peri i Dati Strutturati </a>
per verificare se il markup è presente e corretto.
