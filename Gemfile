source 'https://rubygems.org'

# Specify your gem's dependencies in chrono_model.gemspec
gemspec

group :development do
  gem 'debugger'
  gem 'pry'
  gem 'hirb'

  gem(
    case RUBY_VERSION.to_f
    when 1.8 then 'ruby-debug'
    when 1.9 then 'debugger'
    else          'byebug'
    end
  )
end

group :test do
  gem 'rspec'
  gem 'rake'
  gem 'fuubar'
end
