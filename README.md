# Bugtracker
## Building a GraphQL Server with Spring Boot

### GraphQL is a query language for APIs or a syntax that describes how to ask for data.
GraphQL offers greater flexibility

-----------------------------------------------------------------------------------------
To run and test the app :
Run and check on [localhost](http://localhost:8080/graphiql)
Sample Query

{
  findAllApplications
    {
      id
      owner
     }
}

Response: 
{
  "data":
  {
    "findAllApplications":
        [ { "id": "1" ,
          "owner": "Paul"},
          { "id": "2”,
           "owner": "Jane }]
   }
}
