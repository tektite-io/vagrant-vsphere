source 'http://rubygems.org'

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem 'vagrant', github: 'hashicorp/vagrant', ref: 'v2.2.7'
end

group :plugins do
  gemspec
end
