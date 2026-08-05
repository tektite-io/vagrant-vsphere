# frozen_string_literal: true

source 'http://rubygems.org'

group :development do
  gem 'pry-byebug', '~> 3.12.0'
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem 'vagrant', git: 'https://github.com/mitchellh/vagrant.git', ref: 'v2.4.9'
end

group :plugins do
  gemspec
end
