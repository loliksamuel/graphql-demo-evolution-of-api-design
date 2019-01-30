# GraphQL Demo

#### From the talk _From RPC to GraphQL: APIs design from past to present_

## how to run

```bash
npm install
npm start
```

## https://graphql.org/learn/queries/

---
## queries
```bash
{
  posts {
    id
  }
}
```
```bash
query posts1 {
      posts {
      # queries can have comments
        id
      }  
}
```
```bash
query posts2 {
      posts {
        id, tags, summary
      }  
}
```

```bash
query postId {
      posts {
        id, tags, summary, categories,publishDate, author {
          id, name
        }
      }  
}
```
```bash
query autors1 {
  authors {
    id
    
  }
}
```
```bash
mutation postId {
  posts {
    id
    tags
    summary
   
  }
}
```

## License

MIT
