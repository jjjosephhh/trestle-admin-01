source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }
git_source(:gitlab) { |repo| "https://gitlab.com/#{repo}.git" }

ruby '3.1.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 7.0.4'

# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'

# Use Puma as the app server
gem 'puma', '~> 5.0'

# Asset bundling
gem 'sprockets-rails'

# Use SCSS for stylesheets
gem 'sassc-rails'

# CSS auto-prefixing
gem 'autoprefixer-rails'

# Use terser as compressor for JavaScript assets
gem 'terser'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Haml templating
gem 'hamlit', '3.0.3'

# SVG embedding
gem 'inline_svg'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  # Environment variables
  gem 'dotenv-rails'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

# Trestle admin framework and CMS
gem 'trestle',           github: 'TrestleAdmin/trestle'
gem 'trestle-auth',      github: 'TrestleAdmin/trestle-auth'
gem 'trestle-search',    github: 'TrestleAdmin/trestle-search'
gem 'trestle-tinymce',   github: 'TrestleAdmin/trestle-tinymce'

# gem 'trestle-cms',       gitlab: 'TrestleAdmin/trestle-cms',   branch: "rails-6"
# gem 'trestle-media',     gitlab: 'TrestleAdmin/trestle-media'
# gem 'trestle-tree',      gitlab: 'TrestleAdmin/trestle-tree'
# gem 'flexcontent',       gitlab: 'TrestleAdmin/flexcontent',   branch: "rails-6"
# gem 'trestle-snippets',  gitlab: 'TrestleAdmin/trestle-snippets'
# gem 'trestle-redirects', gitlab: 'TrestleAdmin/trestle-redirects'
# gem 'trestle-cms-blog',  gitlab: 'TrestleAdmin/trestle-cms-blog'

# AWS S3 storage
gem 'aws-sdk-s3', '~> 1.2'
gem 'dragonfly-s3_data_store'

# Automatic blog post excerpts
gem 'truncate_html'

# Elasticsearch
gem 'bonsai-elasticsearch-rails', '~> 6'
gem 'elasticsearch', '~> 6'
gem 'elasticsearch-model', github: 'elastic/elasticsearch-rails', branch: '6.x'
gem 'elasticsearch-rails', github: 'elastic/elasticsearch-rails', branch: '6.x'
gem 'chewy', '~> 6'
gem 'i18n', '~> 1.8.11'

# Google reCAPTCHA
gem 'recaptcha'

# Pardot client
gem 'faraday'
gem 'faraday_middleware'