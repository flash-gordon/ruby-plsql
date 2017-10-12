source 'http://rubygems.org'

group :development do
  gem 'juwelier', '~> 2.0'
  gem 'rspec_junit_formatter'
  gem 'pry-byebug'
end

group :test, :development do
  gem 'rake', '>= 10.0'
  gem 'rspec', '~> 3.1'

  unless ENV['NO_ACTIVERECORD']
    gem 'activerecord', '>= 3.2.3', '< 5.2.0'
    gem 'activerecord-oracle_enhanced-adapter', '>= 1.4.1', '< 1.9.0'
    gem 'simplecov', '>= 0'
  end

  platforms :ruby, :mswin, :mingw do
    gem 'ruby-oci8', '~> 2.1'
  end
end
