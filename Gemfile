source "https://rubygems.org"

ruby "3.2.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.3"

# Use postgres as the database for Active Record
gem 'pg', '~> 1.5', '>= 1.5.6'
# Load environment variables from .env file in development and test
gem 'dotenv-rails', groups: [:development, :test]
#serializer:
gem 'jsonapi-serializer'
#JSON Errors Handler:
gem 'jsonapi_errors_handler'
#Authentication
gem 'devise'
gem 'devise-jwt'
gem 'omniauth', '~> 2.1', '>= 2.1.2'
gem 'faraday-retry', '~> 2.2'
gem 'base64', '~> 0.2.0'
gem 'sawyer', '~> 0.9.2'
#enable CORS
gem 'rack-cors'
#json generation for rails
gem 'active_model_serializers', '~> 0.10.14'

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", ">= 5.0"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", ">= 4.0.1"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin Ajax possible
# gem "rack-cors"

group :development, :test do
  # RSpec for testing
  gem 'rspec-rails', '~> 6.1.0'
  # Factory Bot for test data creation
  gem 'factory_bot_rails'
  # Debugging tools
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end
