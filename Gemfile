source 'https://rubygems.org'

gemspec :name => "wrong"

group :development, :test do
  gem "rvm"
  gem "bundler"
  gem "rake"
  gem "minitest", "~> 1.7.2"  # built in to ruby distro
end

platforms :jruby do
  gem "jruby-openssl" # to silence annoying warning
end
