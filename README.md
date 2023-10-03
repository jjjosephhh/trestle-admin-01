# Trestle Admin Tour

```bash
# Make sure Postgresql is installed
brew install postgresql

# Install all dependencies in the Gemfile
# All of the open source dependencies are identical to
# those in the Pivotal project, and all closed source
# dependencies have been commented out
bundle install

# run the install generator to create the 
# initial configuration file and 
# customization hooks
rails generate trestle:install
```
