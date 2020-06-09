A basic Ruby on Rails 6.0.3.1 app for testing https://github.com/rails/rails/issues/39580

To test create a .env file and set the following in it (obviously replacing the values with real DB credentials):

SECONDARY_BASE_URL=https://www.example.co
SECONDARY_DB_HOST=example.co
SECONDARY_DB_NAME=dbname
SECONDARY_USERNAME=username
SECONDARY_PASSWORD=password
