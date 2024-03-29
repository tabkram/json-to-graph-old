# json-to-graph [![online demo](https://img.shields.io/badge/json_to_graph_online-grey?logo=globe)](https://tabkram.github.io/json-to-graph/)

Simplify your graph rendering with this online tool! Just feed it JSON objects and watch the magic happen

### [Explore the Online Demo!](https://tabkram.github.io/json-to-graph/)  🚀

## Data Format

This project supports a semi-standardized JSON-based graph format known
as [Cytoscape JSON](https://js.cytoscape.org/#notation/elements-json), which adheres to
the [json-graph-specification](https://github.com/jsongraph/json-graph-specification).

## Dependencies

### Main Dependencies:

- **cytoscape ^3.21.1**
    - A feature-rich graph library written in pure JS with a permissive open-source license (MIT) for the core (
      Cytoscape.js library and all first-party extensions) 🌐

- **elkjs ^0.7.1**
    - The [Eclipse Layout Kernel (ELK)](https://www.eclipse.org/elk/)'s layout algorithms for JavaScript
    - elkjs is the successor of [klayjs](https://github.com/kieler/klayjs).
    - Implemented by the Eclipse Foundation in Java, the source code is compiled to JS by the elk.js project using GWT.

- **cytoscape-elk ^2.0.2**
    - The elk layout algorithm adapter for Cytoscape.js 🔄

Feel free to explore the [Online Demo](https://tabkram.github.io/json-to-graph/) to visualize your JSON-based graphs
effortlessly! 🎉
