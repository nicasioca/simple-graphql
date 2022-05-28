Run example by:

1. `cargo run`

2. Enter into the playground a graphql query like:

> REQUEST
```
  {
    hero {
      name
      friends {
        name
      }
    }
  }
```

 > RESPONSE
```
  {
    "data": {
      "hero": {
        "name": "Luke Skywalker",
        "friends": [
          {
            "name": "Han Solo"
          },
          {
            "name": "Leia Organa"
          },
          {
            "name": "C-3PO"
          },
          {
            "name": "R2-D2"
          }
        ]
      }
    }
  }
```