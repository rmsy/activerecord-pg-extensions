# frozen_string_literal: true

source "https://rubygems.org"

plugin "bundler-multilock", "1.2.0"
return unless Plugin.installed?("bundler-multilock")

Plugin.send(:load_plugin, "bundler-multilock")

gemspec

lockfile "rails-7.0" do
  gem "activerecord", "~> 7.1.3"
  gem "railties", "~> 7.1.3"
end

lockfile do
  gem "activerecord", "~> 7.1.0"
  gem "railties", "~> 7.1.0"
end
