## After cloning:

1. bundle
2. create a database.yml file, following the database.yml.example file
3. add database.yml to .gitignore
4. create an application.yml file, following the application.yml.example file
5. change app name in a bunch of places, see below:

## Places to change app name:

- `config/environments/development.rb`
- `config/environments/production.rb`
- `config/environments/test.rb`
- `config/initializers/secret_token.rb`
- `config/initializers/session_store.rb`
- `config/application.rb`
- `config/environment.rb`
- `config/routes.rb`
- `Rakefile`
- `app/views/layouts/application.html.erb` in `<title>` tags
