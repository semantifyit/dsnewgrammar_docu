## Tabular Grammar Visualizer

This project includes HTML files that describe the "grammar" of Domain Specifications.
Every Node in the grammar is described by with a JSON-Object. The overview for each Node includes the allowed key-value pairs of that object, along with a short description.

Since the properties of a JSON Object can be in any order, it is not adequate to speak of a "grammar", and an EBNF representation (and consequently railroad diagram) is not suitable. Because of the cyclic relationships, multi ranged properties, and special explanation for property ranges, it is not a good idea to use ER diagrams. The here showed tabular representation makes a better job in giving a quick/short overview of each node than any other considered visualization.

Properties are ordered by requirement > relevance/importance (e.g. $ keywords > others)