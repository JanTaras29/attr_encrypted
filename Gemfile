source 'https://rubygems.org'

gemspec

# support for testing with specific active record version
gem 'activerecord', "~> #{ENV['ACTIVERECORD']}" if ENV['ACTIVERECORD']
gem 'actionpack', "~> 4.0.0" if ENV['ACTIVERECORD'] && ENV['ACTIVERECORD'] > '4.0'
gem 'encryptor', '~> 1.3.1',  git: 'https://github.com/JanTaras29/encryptor', branch: 'openssl-fix'