# Aesthetikempire

Rails Templates Minimal+ Devise

Quickly generate a rails app with the default [Wagon](https://www.lewagon.com) configuration
The following templates have been made for Rails 7.
Get a minimal rails app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.
Same as minimal **plus** a Devise install with a generated `User` model.

```bash
rails new \
  -d postgresql \
   -m https://raw.githubusercontent.com/lewagon/rails-templates/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
or create your project at the current local directory.
```bash
rails new . \
  -d postgresql \
  -m https://raw.githubusercontent.com/lewagon/rails-templates/master/devise.rb 
```

