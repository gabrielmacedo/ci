---
title: Trabalho da Disciplina Cronografia da Ciência da Informação


---

## Exemplos
Parte 1

| Consulta | Claude Shannon (Q92760) |
| -- | -- |
| Scholia | https://scholia.toolforge.org/author/Q92760 |
| Wikidata | https://w.wiki/6ZYL |

SPARQL
```sparql
SELECT ?propertyLabel ?valueLabel WHERE {
  wd:Q92760 ?property ?value.
  SERVICE wikibase:label {
    bd:serviceParam wikibase:language "en".
    ?property rdfs:label ?propertyLabel.
    ?value rdfs:label ?valueLabel.
  }
}
```


## Ver:

http://www.histropedia.com/ (timeline)
