# REST API

A simple REST API for managing books, built with Spring Boot, JPA, and H2 database.

## Installation

1. Clone the repository:

   ```sh
   git clone git@github.com:Hermes-fire/java-spring-boot-rest-api.git

   cd java-spring-boot-rest-api
   ```

2. Build and run the project using Maven:
   ```sh
   mvn spring-boot:run
   ```

## API Endpoints

### Books

#### Get All Books

```http
GET api/books
```

Returns a list of all books.

#### Get Book by ID

```http
GET api/books/{id}
```

Returns a single book by its ID.

#### Create a New Book

```http
POST api/books
```

Creates a new book. Requires a JSON body with book details.

#### Update a Book

```http
PUT api/books/{id}
```

Updates an existing book by its ID.

#### Delete a Book

```http
DELETE api/books/{id}
```

Deletes a book by its ID.

### Products (Using DTO)

#### Get All Products

```http
GET api/products
```

Returns a list of all products.

#### Get Product by ID

```http
GET api/products/{id}
```

Returns a single product by its ID.

#### Create a New Product

```http
POST api/products
```

Creates a new product.

#### Update a Product

```http
PUT api/products/{id}
```

Updates an existing product by its ID.

#### Delete a Product

```http
DELETE api/products/{id}
```

Deletes a product by its ID.

## Testing

A Postman collection is available in the `./postman` folder for easy API testing.

## License

This project is open-source and available under the [MIT License](LICENSE).
