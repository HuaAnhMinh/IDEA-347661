# frozen_string_literal: true

source 'https://rubygems.org'

gem 'aasm', '4.12.3'
gem 'abn'
gem 'abn_search'
gem 'active_model_serializers'
gem 'activerecord-cte', '~> 0.3.0'
gem 'activerecord-import'
gem 'active_record_union'
gem 'acts_as_commentable_with_threading'
gem 'acts_as_list'
gem 'acts-as-taggable-on', '~> 9.0'
gem 'addressable', '~> 2.8.0'
gem 'amazing_print'
gem 'attr_encrypted', '4.0.0'
gem 'bitmask_attributes'
gem 'bootsnap', '1.12.0', require: false
gem 'bootstrap-kaminari-views', '~>0.0.3'
gem 'browser'
gem 'bundler', '~> 2.4.17'
gem 'carrierwave', '~> 2.2'
gem 'carrierwave-aws', '~> 1.5'
gem 'cgi', '~> 0.3.6'
gem 'sprockets-rails', require: 'sprockets/railtie' # sprockets-rails has to be placed above chosen-rails in Gemfile because chosen-rails uses sprockets
gem 'chosen-rails', '1.10.0'
gem 'chronic'
gem 'cocoon'
gem 'coffee-rails', '~> 4.2.2'
gem 'countries', '4.1.3'
gem 'country_select', '6.0.0'
gem 'decent_exposure', '~>3.0.2'
gem 'deep_cloneable'
gem 'devise', '~> 4.8.1'
gem 'dry-initializer'
gem 'dry-matcher'
gem 'dry-monads', '~> 1.3'
gem 'ejs', require: false
gem 'execjs', require: false
gem 'fcm'
gem 'figaro'
gem 'filestack', '~> 2.9'
gem 'flag-icons-rails'
gem 'fusionauth_client', require: 'fusionauth/fusionauth_client'
gem 'geocoder'
gem 'gocardless_pro'
gem 'gon', require: false
gem 'google-api-client', '~> 0.45'
gem 'google-cloud-firestore', '~> 2.7'
gem 'grape', '~> 1.6.2'
gem 'grape_has_scope'
gem 'grape_logging'
gem 'grape-route-helpers'
gem 'hamlit', '2.11.0'
gem 'hamlit-rails'
gem 'hashie', '~> 4.1.0'
gem 'hashie-forbidden_attributes'
gem 'hiredis'
gem 'httparty', '~> 0.21.0'
gem 'icalendar'
gem 'inherited_resources'
gem 'ird-validator'
gem 'jbuilder'
gem 'jquery-rails', '~> 4.4.0'
gem 'jquery-ui-rails', git: 'https://github.com/jquery-ui-rails/jquery-ui-rails', tag: 'v7.0.0'
gem 'json-schema'
gem 'Rx.rb', git: 'https://github.com/ReactiveX/RxRuby', ref: 'e493b321a7a9157a15ff6239f2cbe45cf2d1efec'
# Intended use to generate Firebase Custom Token only. See:
# https://employmenthero.atlassian.net/wiki/spaces/DE/pages/2384101547/Technical+Proposal+Firebase+Authentication+Integration+for+ATS+Direct+Messaging
gem 'jwt', require: false
gem 'kaminari'
gem 'lograge'
gem 'loofah', '>= 2.3.1'
gem 'marcel', '~> 1.0.0'
gem 'mini_magick', '>= 4.9.4'
gem 'mixpanel-ruby'
gem 'mobility', '~> 1.2.5'
gem 'money-rails', '~> 1.15.0'
gem 'net-sftp'
gem 'net-ssh', '5.2.0'
gem 'nokogiri', '~> 1.14.3'
gem 'oj'
gem 'options', '~> 2.3.0'
gem 'paper_trail', '~> 13.0'
gem 'parallel', require: false
gem 'pg'
gem 'phony_rails', '~> 0.14.4'
gem 'platform-api'
gem 'postgresql_cursor', '~> 0.6.8' # Adopt PG cursors seamlessly for large-scale CSV exporting
gem 'prawn'
gem 'pry-rails'
gem 'puma', '~> 5.6.8'
gem 'pundit'
gem 'rack', '~> 2.2.6.4'
gem 'rack-cors', '1.0.6', require: 'rack/cors'
gem 'rails', '7.0.5.1'
gem 'rails-html-sanitizer', '>= 1.4.3'
gem 'rails-i18n', '7.0.7'
gem 'rails-observers'
gem 'ransack', '2.5.0'
gem 'recaptcha', require: 'recaptcha/rails'
gem 'redis', require: %w[redis redis/connection/hiredis]
gem 'redis-mutex', '4.0.1'
gem 'rest-client', '~> 2.0.1'
gem 'restforce', '5.2.3'
gem 'rgl'
gem 'ruby-kafka', '~> 1.0.0'
gem 'ruby-openai', '~> 6.3'
gem 'ruby-saml', '~> 1.16'
gem 'rubyXL'
gem 'salesforce_bulk_api', '1.0.0', require: false
gem 'sanitize', '~> 6.0.2'
gem 'sass-rails', '5.0.8'
gem 'scenic'
gem 'select2-rails', '3.5.11'
gem 'sentry-rails', '~> 5.9.0'
gem 'sentry-ruby', '~> 5.9.0'
gem 'simple_form'
gem 'sixarm_ruby_unaccent'
gem 'spreadsheet', '~> 1.1', '>= 1.1.4'
gem 'strong_migrations'
gem 'tinymce-rails'
gem 'twilio-ruby', '~> 5.31.2', require: false
gem 'twitter-text', '~> 1.14.7'
gem 'uglifier', '~> 4.2.0'
gem 'uuid'
gem 'versionist'
gem 'warden'
gem 'wicked'
gem 'zendesk_api', '~> 1.25'
gem 'zuora_api', '~> 1.11.2'

group :production, :staging do
  gem 'circleci', '~> 1.0.0', require: false
  gem 'octokit', '~> 4.2', require: false
  gem 'rails_serve_static_assets'
end

group :development do
  gem 'colorize', '0.8.1'
  gem 'flamegraph', require: false
  gem 'grape_on_rails_routes'
  gem 'i18n-tasks', '~> 0.9.34'
  gem 'seedbank'
end

group :test, :development do
  gem 'brakeman'
  gem 'bullet', '>= 7.0.7'
  gem 'coveralls_reborn', '~> 0.20.0', require: false # https://github.com/lemurheavy/coveralls-public/issues/1525
  gem 'cucumber-rails', '~> 2.6.1', require: false
  gem 'db-query-matchers'
  gem 'factory_bot_rails', '5.2.0', require: false
  gem 'letter_opener'
  gem 'listen'
  gem 'parallel_tests', '~> 4.2.1'
  gem 'pastel'
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 6.0.3'
  gem 'rubocop', '~> 1.57.1', require: false
  gem 'rubocop-performance', '~> 1.19.1', require: false
  gem 'rubocop-rails', '~> 2.21.2', require: false
  gem 'rubocop-rspec', '~> 2.24.1', require: false
  gem 'simplecov', '~> 0.21.2', require: false
  gem 'simplecov-json', require: false, group: :test
  gem 'spring', '~> 4.1.1'
  gem 'spring-commands-cucumber'
  gem 'spring-commands-parallel-tests'
  gem 'spring-commands-rspec'
  gem 'spring-watcher-listen'
  gem 'stackprof'
  gem 'steak'
  gem 'timecop'
  gem 'tty-prompt'
end

group :test do
  gem 'better_errors', '2.9.1'
  gem 'binding_of_caller'
  gem 'capybara', '3.39.2'
  gem 'database_cleaner-active_record', '~> 2.1.0'
  gem 'faker'
  gem 'fakeredis', git: 'https://github.com/guilleiguaran/fakeredis',
      ref: '509822e07289a7f78e340b8be757fae662c0e0de',
      require: 'fakeredis/rspec'
  gem 'json_matchers'
  gem 'json_spec'
  gem 'karafka-testing'
  gem 'knapsack_pro', '~> 5.7.0'
  gem 'launchy'
  gem 'rack_session_access'
  gem 'rails-controller-testing', require: false
  gem 'rb-fsevent', '~> 0.10'
  gem 'rspec-activemodel-mocks'
  gem 'rspec-collection_matchers'
  gem 'rspec-instafail'
  gem 'rspec-its'
  gem 'rspec_junit_formatter', '~> 0.4'
  gem 'selenium-webdriver', '4.1.0'
  gem 'shoulda-matchers', '~> 4.0.1'
  gem 'test-prof'
  gem 'vcr'
  gem 'webdrivers', '~> 5.3.1', require: false
  gem 'webmock', '~> 3.18.1', require: false
end

plugin 'bootboot', '~> 0.1.1'
Plugin.send(:load_plugin, 'bootboot') if Plugin.installed?('bootboot')
