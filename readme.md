## After cloning:

1. `$ bundle`
2. create a `database.yml` file, following the `database.yml.example` file
3. create an `application.yml` file, following the `application.yml.example` file.
   do a `$ rake secret` and copy the result into `application.yml` as the value to a 
   `secret_key_base` key (in the format the `application.yml.example` file shows)
4. change app name in a bunch of places:
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

5. Create a new github repo and then:
    - `$ git remote remove origin`
    - `$ git remote add origin [paste your git@github.com:username/repo_name.git here]`
    - `$ git push -u origin master`


## Todo/future features:

- include script to change app name globally or find better solution for this like
  templating or something.
