source 'http://rubygems.org'

gem 'rails', '3.0.5'

# Uncomment if you're using sqlite
gem 'sqlite3-ruby', :require => 'sqlite3'
#gem 'mysql'

gem 'hoptoad_notifier'

#--[ Utility ]------------------------------------------------------------------
gem 'httparty', '~> 0.7.4'
gem "json", "~> 1.4.6"
gem 'addressable', '~> 2.2.4'

#--[ Authentication ]-----------------------------------------------------------
gem 'devise'
gem 'omniauth', '>= 0.2.6'

# Automatic login provider selection
gem 'redfinger'
gem 'ruby-openid'
gem 'net-dns', '~> 0.6.1', :require => 'net/dns/resolver'

# Client libraries for authenticated services
gem 'twitter'
gem 'linkedin'
gem 'mogli'
gem 'foursquare2'   # https://gist.github.com/419219 <- github oauth docs!

#--[ Search ]-------------------------------------------------------------------
# If you're using the default sql-based search, you can comment this out.
gem 'thinking-sphinx', '~> 2.0.1', :require => 'thinking_sphinx'

#--[ Model ]--------------------------------------------------------------------
gem "paperclip"
gem "inherited_resources"
gem "responders"

gem 'acts-as-taggable-on', "~> 2.0.6"



#--[ View ]---------------------------------------------------------------------
gem "haml", "~> 3.0.18"
gem "compass", "~> 0.10.5"
gem "compass-960-plugin", "~> 0.9.13", :require => 'ninesixty'
gem 'jquery-rails', '>= 0.2.6'
gem 'formtastic', '~>1.1.0'

#--[ Controller ]---------------------------------------------------------------
gem 'will_paginate'

#--[ Middleware ]---------------------------------------------------------------
gem 'rack-jsonp'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
  # -- [ Testing ] -------------------------------------------------------------
  gem 'rspec-rails'
  gem "mocha"
  gem "fakeweb"
  gem "factory_girl_rails"
  gem 'faker'
  gem 'uuid'
  gem 'steak'
  gem 'launchy' 
  gem 'database_cleaner'
  gem 'faker'
  gem 'spork'

  # -- [ IRB ] -----------------------------------------------------------------
  gem 'awesome_print'
  gem 'drx'
  gem 'wirble'
  gem 'utility_belt'

  # -- [ Tools ] ---------------------------------------------------------------
  gem 'rcov'
  gem 'ruby-debug19'
  gem 'annotate'
  gem "nifty-generators"
end
