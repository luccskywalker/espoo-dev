# README

# 🐳 Run (with docker)

- `docker-compose up`

- `docker-compose exec espoo_server bundle exec rspec`

- navigate to http://localhost:3000

- username: `admin@gamil.com` password: `123456`

# :heart: Run (standalone)
- `cd backend`
- `bundle install`
- `bundle exec rake db:create db:migrate db:seed`
- `export RAILS_MASTER_KEY: 'a667717bf0a47475b0582547379c816d'`
- `export DEVISE_JWT_SECRET_KEY: 'e26a21cfca4fdf67cc4e82385ba2d6ea4fb83ad1f8f5'`
- `bundle exec rspec`
- `bundle exec rails s -b 0`
