web: bundle exec rails server -p $PORT

release: heroku run rails db:migrate
release: heroku run rails db:seed
