web: bundle exec rails server -p $PORT

release: heroku run rails db:migrate && heroku run rails db:seed
