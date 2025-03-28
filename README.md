adres edytora GraphQL: http://localhost:8080/graphiql

przykładowe zapytanie:
`query bookDetails {
  bookById(id: "book-1") {
    id
    name
    pageCount
    author {
      id
      firstName
      lastName
    }
  }
}`