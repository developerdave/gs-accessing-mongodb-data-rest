# Accessing MongoDB Data with REST
Following the [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/) guide. 

- Spring application that let's you create and retrieve `Person` objects stored in a `MongoDB NoSQL` database.
- Uses the features of `Spring HATEOAS` and `Spring Data MongoDB`.
- The MongoDB is run within a docker container

## Starting Docker
Run `docker-compose up` in the terminal

## Person Repository
The repository is an interface and will allow you to perform 
various operations involving `Person` objects. It
gets these operations by extending `MongoRepository`, 
which in turn extends the `PagingAndSortingRepository` interface
defined in Spring Data Commons.

## Testing the application
See [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/) for 
details of how to test the application.