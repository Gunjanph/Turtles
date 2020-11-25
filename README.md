# Turtles

- Algorithms: https://docs.google.com/document/d/1AHLr3z_5bo7-bGJavskwIZoGY4PXOI7BcchHESrsVs0/edit# \
- Graph of algorithms: https://app.creately.com/diagram/JRP8uQYARcp/edit

## Code
- Install Neo4j 
- Open `http://localhost:7474/browser/`
- Run the code in Backend/Basic.cypher by copying in neo4j

### Path
To find path from Root to any node:
`MATCH p=(root)-[*0..]->(n:level3 {name: "<Node name>"})RETURN p;`
