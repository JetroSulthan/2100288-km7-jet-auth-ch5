### Collections and Endpoints

#### 1. Cars

- **GET** `/cars` - Retrieve a list of cars. Requires `{{token}}`.
- **GET** `/cars/all` - Retrieve a list of cars. Requires `{{token}}`.
- **GET** `/cars/:id` - Retrieve a car by ID. Requires `{{token}}`.
- **POST** `/cars/` - Create a new car entry. Requires `{{token}}`.
- **PUT** `/cars/:id` - Update a car entry by ID. Requires `{{token}}`.
- **DELETE** `/cars/:id` - Delete a car entry by ID. Requires `{{token}}`.


#### 2. Health Check

- **GET** `/health-check` - Check the health status of the API.

#### 3. Auth

- **POST** `/login` - Log in and retrieve a JWT token.
- **POST** `/register` - Register a new user.
- **GET** `/current-user` - Retrieve the current authenticated user. Requires `{{token}}`.

#### 4. Users

- **GET** `/users` - Retrieve a list of users. Requires `{{token}}`.
- **GET** `/users/:id` - Retrieve a user by ID. Requires `{{token}}`.
- **POST** `/users/` - Create a new user. Requires `{{token}}`.
- **PUT** `/users/:id` - Update a user by ID. Requires `{{token}}`.
- **DELETE** `/users/:id` - Delete a user by ID. Requires `{{token}}`.

