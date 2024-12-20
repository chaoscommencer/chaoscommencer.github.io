
# In order to leverage Gemfile functionality, install bundler:
# gem install bundler

# Create a Gemfile for a project:
# bundle init

# Install gems according to the Gemfile definition:
# bundle install

# Declare the Rubygems source containing the gems listed in the Gemfile.
source 'https://rubygems.org'

# Enforce minimum required Ruby version and patch level.
ruby "2.7.1", :patchlevel => "83"

# Jekyll
# A simple, blog-aware, static-site generator.
gem 'jekyll', '~> 4.0.0'

# WDM - Windows Directory Manager
# This C library which monitors directories for changes leverages the Win32 API
# for enhanced performance.
# NOTE: Required to support Jekyll's watch functionality.
gem 'wdm', '~> 0.1.1' if Gem.win_platform?

# Groups exist for test, development, production...
group :development do
  # Rouge
  # A simple, easy-to-extend, drop-in replacement for the pygments syntax
  # highlighter.
  # NOTE: Only required for development.
  gem 'rouge', '~> 3.17.0'
end
