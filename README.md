# Todo list

This is a REST API, made with Ruby on Rails, for managing a Todo list.

It uses JWT for authentication and ActiveRecord for CRUD operations.

Described below are the functionalities we created:

| HTTP method | Endpoint | Functionality |
| -- | -- | -- |
| POST | /signup | Signup  |
| POST | /auth/login | Login  |
| GET | /auth/logout | Logout  |
| GET | /todos | List all todos and todo items  |
| POST | /todos | Create a new todo  |
| GET | /todos/:id | Get a todo  |
| PUT | /todos/:id | Update a todo  |
| DELETE | /todos/:id | Delete a todo and its items  |
| GET | /todos/:id/items/:iid | Get a todo item  |
| POST | /todos/:id/items | Create a new todo item  |
| PUT | /todos/:id/items/:iid | Update a todo item  |
| DELETE | /todos/:id/items/:iid | Delete a todo item |

This was made as a university project, and meant for learning about RESTful API development.  

## Team

| [![Stratis-Dermanoutsos](https://avatars2.githubusercontent.com/Stratis-Dermanoutsos)](https://github.com/Stratis-Dermanoutsos) | [![John-Athanasopoulos](https://avatars2.githubusercontent.com/John-Athanasopoulos)](https://github.com/John-Athanasopoulos) | [![JimChr-R4GN4R](https://avatars2.githubusercontent.com/JimChr-R4GN4R)](https://github.com/JimChr-R4GN4R) |
| --- | --- | --- |
| Ευστράτιος Δερμανούτσος | Ιωάννης Αθανασόπουλος | Δημήτριος Χρυσοχέρης |
| π19041 | π19005 | π19190 |

## Tutorial we followed

1. [Build a RESTful JSON API With Rails 5 - Part 1](https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one)
2. [Build a RESTful JSON API With Rails 5 - Part 2](https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-two)
3. [Build a RESTful JSON API With Rails 5 - Part 3](https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-three)

## Instructions for local deployment

1. Clone the repo

   ```zsh
   git clone https://github.com/Stratis-Dermanoutsos/todos-api.git
   ```

2. Get the gems (packages)

   ```zsh
   bundle install
   ```

3. Run the DB migrations

   ```zsh
   rails db:migrate
   ```

4. Start the server

   ```zsh
   rails s
   ```
