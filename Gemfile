source 'http://rubygems.org'

gemspec

group :test do
  gem 'guard-rspec'

  if RUBY_PLATFORM.downcase.include? "darwin"
    gem 'rb-fsevent'
    gem 'growl'
  end
end

# for testing https://github.com/iloveitaly/spree_sale_products
# both extensions modify price assignment behaviour
# gem 'spree_sale_products', :path => '../spree_sale_products'
gem 'spree', '~> 1.2.3'