# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
// your response here
The purpose of a backend is to allow for CRUD commands: creating, reading, updating, and deleting data. It helps us communicate with stored data and returns them to the viewer.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
// your response here
The C in the MVC pattern represents the controller which finds the corresponding models and orders them to do things.
```

Which layer in the MVC pattern communicates with the model?

```md
// your response here
The M in the MVC pattern presents the model which does things that the controller tells it to do.
```

Why don't we use views in our interpretation of the MVC pattern?

```md
// your response here
Because we don't teach them here.
And it's also becoming outdated I guess.
```

What does C.R.U.D stand for?

```md
// your response here
Creating, Reading, Updating, and Deleting
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
// your response here
The Model in the MVC pattern executes the actual CRUD actions.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
// your response here
INDEX
SHOW
CREATE
UPDATE
DELETE
NEW
EDIT
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
// your response here
- The request gets passed to the server by the client
- The server communicates the request to the controller
- The controller finds the model that corresponds to the request and tells it what to do
- The model goes and fetches the data from the database
- The model passes the information to the controller who passes it to the server who displays it to the viewer
```

What is the command to generate a new rails-api app?

```bash
// your response here
bin/rails generate controller examples
```

What is the command to start an instance of a rails server?

```bash
// your response here
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
// your response here
- bin/rake db:create
- bin/rake db:migrate
- bin/rake db:seed
- bin/rake db:examples
- bin/rake db:drop
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
bin/rails generate scaffold PETS name:text age:integer

source: https://www.tutorialspoint.com/ruby-on-rails/rails-scaffolding.htm
```
