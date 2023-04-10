---
title: Trabalho da Disciplina Cronografia da Ciência da Informação


---


Parte 1

Consulta SPARQL na Wikidata:
Claude Shannon (Q92760): https://w.wiki/6ZYL

```
SELECT ?propertyLabel ?valueLabel WHERE {
  wd:Q92760 ?property ?value.
  SERVICE wikibase:label {
    bd:serviceParam wikibase:language "en".
    ?property rdfs:label ?propertyLabel.
    ?value rdfs:label ?valueLabel.
  }
}
```
