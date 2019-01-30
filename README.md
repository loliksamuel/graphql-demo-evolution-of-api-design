# GraphQL Demo

#### From the talk _From RPC to GraphQL: APIs design from past to present_

## Getting Started

```bash
npm install
npm start
```

##https://graphql.org/learn/queries/

---
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
## License

MIT
