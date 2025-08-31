# frozen_string_literal: true

source 'https://rubygems.org'
gem 'kamal', require: false
gem 'puma', '6.4.2'
gem 'rack-cors'
gem 'rails', '~> 8.0.2'
gem 'bootsnap', require: false
gem 'devise'
gem 'redis', '5.4.1'
gem 'sidekiq', '8.0.6'
gem 'solid_cable'
gem 'solid_cache'
gem 'solid_queue'
gem 'streamio-ffmpeg', '3.0.2'
gem 'thruster', require: false
gem 'tzinfo-data', platforms: %i[windows jruby]
gem 'rbs', '3.4.4'
gem 'ssh_key_switcher'
gem 'pg', '1.6.1'
gem 'enumerize', '2.8.1'
gem 'rubocop'
gem 'stimulus-rails', '1.3.4'
gem 'turbo-rails', '2.0.16'
gem 'vite_rails', '3.0.19'

group :development, :test do
  gem 'brakeman', require: false
  gem 'debug', platforms: %i[mri windows], require: 'debug/prelude'
  gem 'rubocop-rails-omakase', require: false
  gem 'ruby-lsp'
  gem 'hmvc-rails', '1.0.4'
end

group :development do
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
end
