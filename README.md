## Supermarket List API

API in Node.js using Express and Mongoose to connect Database.

### Technologies

- Node.js
- Express
- Mongoose
- MongoDB
- Nodemon

### Required Technologies

- Node.js installed (https://nodejs.org)
- MongoDB instance running:
  Ex: Running with docker

```
docker run --name supermarket-list -p 27017:27017 -d mongo
```

### Steps to run the project

1. Clone the repo:

```

git clone https://github.com/fabricio22br/supermarket-list-api

```

2. Navigate to the repo:

```

cd supermarket-list-api

```

3. Install the dependencies:

```

npm install

```

4. Run the API:

```

npm run start:dev

```

### Important Rule

Is necessary send the username at the requisition header

### Available endpoints

- [GET]/list-items
- [POST]/list-items
- [DELETE]/list-items/:id
- [PUT]/list-items/:id
