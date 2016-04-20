# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
The purpose of the backend is to process and store app information and logic.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The Model layer fetches and submits data to the database at the behest of the controller.
```

Which layer in the MVC pattern communicates with the model?

```bash
The Controller communicates with the model and tells it what to do.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Because we prefer Single-Page Applications (SPAs), where one page is updated dynamically (rather than changing among multiple views).
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Destroy.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Typically the Controller implements the various CRUD actions as methods.
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
Index (read), Create (create), Show (read), Update (update), and Destroy (destroy)
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1. The Routes file will direct the request to the appropriate controller for that resource.
2. The controller will make the request for inforation to the appropriate model for that resource.
3. The model will retrieve the information from the database and pass it back to the controller.
4. The controller will display it to the user.
```

What is the command to generate a new rails-api app?

```bash
rails-api new api_name [-OPTIONS]
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
rake db:drop, rake db:create, rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails generate scaffold Pet name:string age:integer
```

List two advantages of using serializers? (2 bullet points)

```bash
Serializers are useful because the (mostly) automate the process of creating JSON strings representing the objects in your app. It also makes testing easier than with other methods.
```
